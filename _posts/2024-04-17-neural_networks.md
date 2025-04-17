## Trying to Undertsand Neural Networks

Neural networks are still somewhat of a *magix box* to me, so in this post will be my notes and takings from the fastai chapter on neural networks.

### History of Neural Nets
It all started in 1943 with Mchulloch and Pitts paper "A Logical Calculus of the Ideas Immanent in Nervous Activity" in which they proved a additon and thresholding could represent a real neuron.


![](/images/neuron.png "Image of neuron")

They proved a single layer of neurons couldn't understand simple mathematical functions but with multiple layers its understanding grew.

### Basics of parallel processing
PDP or parallel Distributed Processing, was described to be closer to how the brain works, and as such may be better at tasks the brain finds easy.

As stated in the fastai textbook parallel processing requires
> <ol>
>  <li>A set of processing units</li>
>  <li>A state of activation</li>
>  <li>An output function for each unit</li>
>  <li>A pattern of connectivity among unitsm</li>
>  <li>A propagation rule for propagating patterns of activities through the network of connectivities</li>
>  <li>An activation rule for combining the inputs impinging on a unit with the current state of that unit to produce an output for the unit</li>
>  <li>A learning rule whereby patterns of connectivity are modified by experience</li>
>  <li>An environment within which the system must operate</li>
></ol> 

  Okay, I think im starting to get this, the way I see it there are a bunch of nodes (units) which are either on or off based upon their relationship with the nodes around them kind of like a really *really* complicated game of telephone. I definitely have a way to go with understand this all, but some of the magic air contained within neural nets has become a lot more understandable to me.
