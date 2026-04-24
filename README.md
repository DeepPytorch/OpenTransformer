<h1> OpenTransformer </h1>
<a>This is a testing loop transformer model that is designed to be massive and have deep thought, specificly for logical tasks. (Has no datset it is just a test architecture.)</a>
<a> When this is completed it will be able to have variasble thinking depth and power at a fraction of the time to train.</a>
<h2>This model has the architecture feature that Mythos is rumored to have, <b>the looped transformer.</b></h2>
<p>This makes each block 30 layers, and the same weights are repeated 30 times to make a 900 layer model with only 1/30 of the training time. So the total # of parameters is 60 layers worth, but the effective depth is 3600 layers. Also I will eventually add different modes for different number of blocks, such as a fast with uses 15 blocks, a normal with uses 30 blocks, and a thinking mode which uses 60 blocks</p>
<p>This model has 491,471,078,400 parameters when you include looped blocks but it only takes the same time as a 16,382,369,280 parameter model. It also has 256 experts and 1,919,808,900 parameters per expert.</p>
<p>Because of the block layers, this model would only have to be trained on a massive GPU cluster nubering over 5000, however that is nothing compared to the 50's of thousands of high-end gpus required to train a different model of the same size.</p>
<h3>If anyone uses this project to make a smaller model of their own, please contact me, I would love to see it!</h3>
