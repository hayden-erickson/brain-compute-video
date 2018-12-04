Can we create our brains in software? Our brain contains roughly 100 billion
neurons each with about 7,000 connections. That's 2000 times greater than the
number of stars in the galaxy.

Everything about you from your personality, memories, likes and dislikes, and
aspirations are contained within those connections. But the brain is not just a
bundled mess of randomly connected neurons. In fact, our brains show a vast
amount of regular structure. Specifically, our neocortex. This is the part of
the brain that makes us human and gives us the ability to find complex patterns
and make predictions about our future and possible outcomes.

Our neocortex is the newest part of the brain and is what all mammals share.

[[ show wrinkly cortex ]]

However, ours is the largest among all mammals and its why we have large
foreheads.

[[ show forehead diagram ]]

Neocortex literally means new crust and it comprises 76% of our entire brain.

[[ show dictionary blurb ]]

For something that only mammals have that is pretty incredible. Most of our
brain is the part that only mammals have and we have more of it than all other
mammals.

The craziest part of all this it's regular structure. We may have billions of
neurons, but our neurons are organized into little groups called columns and we
have a few hundred million of them.  These "discrete functional units" all have
the same basic structure. 

[[ show cortical column simulation ]]
visualization of microcircuitry
http://bbp.epfl.ch/project/media/Fullcomp.mp4

These sub units are further organized into regions of hierarchies which create
a tree like structure.

This hierarchy allows us to create mental models of the
world which are composed of ever increasing sub
parts. A house is one thing, but it's made up of walls, doors, and windows. A
door is one thing, but is made up of hinges, wood, a knob, and a
frame. We could go on like this forever!

[[ show tree of hierarchical house ]]

We have known the importance of connections in encoding information in our
brains for quite a while which has lead to many computer based simulations
including neural networks which are responsible for most of the things we think
of as AI. Just like our neurons have synaptic connections of varying strength,
the artificial neurons in a neural network do too. The strength of each
artificial neuron connection is represented by a number which is used along
with some activation function to create that neuron's output value which is
then fed into other neurons. What a neural network "Learns" is the
strengths of all its connections and it uses those connections to take some
input like an image and output something useful like what is in an image and
where.

So why don't we have robots running around that are indistinguishable from humans?
Well one reason is pure scale. We may have artificial networks of neurons
capable of learning amazing things like how to generate movement commands of a
hand, how to remove unwanted items from images leaving no trace, how to turn
voice into text and so on, but all these examples are very narrow. Any existing
neural network can only do one specific task and if the data used to train that
network is biased or inadequate in some way, the network still won't be very
good. Further, The most advanced neural networks we have currently take hours, days or
even weeks to train and require hefty computing resources like GPU's to do so.
In order to make a brain capable of the flexibility of a human using only
artificial neural networks would require thousands or millions of these
networks all interconnected and we simply don't have a feasible way of running
them all at once or even an idea of how they should be connected.

But this doesn't mean we're not trying! 

The blue brain project is a swiss based organization utilizing experimental
data to create simulations of neurons. They are able to simulate small networks
of neurons using supercomputers and verify their models against real observations. 
Their goal is to create a "closed loop" in which a simulated animal (possibly a
human) is hooked to a simulated brain in a simulated environment. Doing so
allows researchers to perform experiments that could not be done otherwise.
They could study the activity patterns of as many neurons as they want and see
how the activity changes in response to the environment or internal factors
such as oxygen levels and fluid composition. Given an accurate enough
simulation it may be possible to simulate certain mental disorders and even
find cures. Not only that, but knowing how the brain processes information
enables us to make our devices smarter and more flexible. Neural networks,
responsible for almost all modern advances in computing like self driving cars,
facial recognition, and alpha go zero, are based on the architecture of our
brains.


This is the DARPA SyNAPSE
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/DARPA_SyNAPSE_16_Chip_Board.jpg"></img>

It holds 16 IBM TrueNorth chips. But these aren't like regular processors. They
are event based which means they react to input in order to perform
computation. A normal processor is always looking for something to do,
continuously running processes on your computer like your web browser, text
editor, or desktop. If your processor isn't working it's not happy because it's
underutilized. But the truenorth chips are more than happy to due absolutely
nothing until necessary which is why they consume 1/10,000th the power of a
normal core. Neurons in your brain are triggered by sensory input and other
neurons. They don't just continually sit there and fire off signals trying to
figure out what you're going to wear tomorrow because that would be a WASTE OF
ENERGY. 

So why don't we use these to simulate the brain? Well let's see, how many of
these boards would we need?

	SyNAPSE
	16 TrueNorth chips

  IBM TrueNorth
  4096 cores

  --- per core ---
  256 neurons

  --- per neuron ---
  256 synapses

  --- total synapses / chip ---
  268,000,000

On one SyNAPSE board we can simulate
4,294,967,296 connections = Synapses ~ 2 ^ 32


But remember we said the brain has 2,000 times more connections than stars in
the galaxy so we would Still need ~ 262,000 boards. This amount of connected
SyNAPSE chips does not exist, but the air force is using them in a project
called Blue Raven.
<blockquote>
	...64 million neurons and 16 billion synapses connections, while only
	consuming 40 watts. The system fits in a 4U-high (7in) space in a
	standard server rack.
</blockquote>

There are about 30 to 80 thousand server racks in a standard data center so in
order to simulate the number of connections in our brain using this
configuration we would need about 1,562 servers which is much smaller than a
normal data center. So that might be one option.
    
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Von_Neumann_Architecture.svg/510px-Von_Neumann_Architecture.svg.png"/>

[[ NEAT may be one way to solve the connection problem ]]

