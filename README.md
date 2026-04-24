<h1> OpenTransformer </h1>
<a>This is a testing loop transformer model that is designed to be massive and have deep thought, specificly for logical tasks. (Has no datset it is just a test architecture.)</a>
<h2>This model has the architecture feature that Mythos is rumored to have, <b>the looped transformer.</b></h2>
<p>This makes each block 30 layers, and the same weights are repeated 30 times to make a 900 layer model So the total # of parameters is 30 layers worth, but the effective depth is 600 layers. Also I will eventually add different modes for different number of blocks, such as a fast with uses 15 blocks, a normal with uses 30 blocks, and a thinking mode which uses 60 blocks</p>
<p>This model has 491,471,078,400 parameters, which means because the same data is being updated, it can be smarter with less data, meaning that its power increases faster per unit of training time that other models of its size, thus meaning that the training time can be significantly reduced.</p>
<p>This means that if you put this model against anoth 491B model it would finish training months later, however it would outpreform that model in nearly everything, expecialy logic and reasoning, long before the other model finished training.</p>
<h1>How this model works<h1>
<p>This model works with the looped tranformer, as I already mentioned, but this uses a standard MoE arhcitecture, just looped 30 times. To avoid having to type the code over and over again for each layer, I just used a loop to create the layers.</p>
<p>Pls excuse my spelling errors, my dear friend spell check does not work on this.</p>
<h3>If anyone uses this project to make a smaller model of their own, please contact me by tagging me, I would love to see it!</h3>
