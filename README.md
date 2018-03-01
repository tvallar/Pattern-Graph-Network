# Pattern-Graph-Network
This is a experimental neural network for simplified dynamic angle scene recognition. I am designing it using techniques implemented in various neural network designs as inspiration but this project will be written from scratch. The structure of the network will change over the course of its design as I refine my original idea.

Currently I am working through my first design of the structure on paper but will begin coding once finished. I will also be adding an explanation of the theory portion of the idea with the first code commit.

# description
This neural network will be designed such that the image is broken into sections and then information such as color distribution will be retrieved. Following this, the sections will be run through an inital network that returns any shapes found in the sections (subject to change). Finally, the data and weights retrieved from both these parts will be used to trigger corresponding nodes in a fully connected graph, where each node is a basic image element, such as shapes, colors, etc.. With the directional unit vector as an input(s), each section of the original image will be classified. (Example: one section of the image was just blue and white with a unit vector pointing positively up so the most likely case is that section is the sky.)

The idea above is very unrefined and acts as inspiration for the intial design and will most certainly change as I move to the implementation stage.
