Local Response Normalization is a normalization layer that implements the idea of lateral inhibition. Lateral inhibition is a concept in neurobiology that refers to the phenomenon of an excited neuron inhibiting its neighbours: this leads to a peak in the form of a local maximum, creating contrast in that area and increasing sensory perception. In practice, we can either normalize within the same channel or normalize across channels when we apply LRN to convolutional neural networks.

 
 

Where the size is the number of neighbouring channels used for normalization,  is multiplicative factor,  an exponent and  an additive factor
