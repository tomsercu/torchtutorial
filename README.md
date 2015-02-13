# torchtutorial
Repo for the torch nn module tutorials for the NYU Deep Learning class spring 2015

View the notebooks in your browser by pasting the link into http://nbviewer.ipython.org

If you don't have iTorch installed, I recommend opening the notebook in your brower, and have a terminal with th open, then just copy paste the skeleton code I provide into your th session.

# remarks
If you're just starting out with torch and you're familiar with python, this parallel will clear your mind:
+ python ~ lua
+ numpy ~ 'torch' package / the Tensor library. 
+ sklearn ~ 'nn' package

In fact torch is usually used to refer to the whole framework, but the torch package provides just Tensors as the fundamental object that almost all other packages use, similar to numpy arrays providing the basis for all of scipy and sklearn.
This is echoed on github: there's the [torch github](https://github.com/torch) page, which maintains [the torch7 repo](https://github.com/torch/torch7) and several repo's like [nn](https://github.com/torch/nn), [cunn](https://github.com/torch/cunn), [image](https://github.com/torch/image) etc.

# prerequisites
- lua basics. For example the first two tutorials of [soumith's nextml talk](https://github.com/soumith/nextml) and [learn lua in 15 minutes](http://tylerneylon.com/a/learn-lua/)
- torch Tensor basics

# More tutorials and material
There is plenty learning material for torch, albeit a bit scattered over different places. 
+ The most famous one is [Clement Farabet's tutorial](http://code.madbits.com/wiki/doku.php) / [code](https://github.com/torch/tutorials)
+ As I mentioned, [Soumith's nextml tutorials](https://github.com/soumith/nextml).
+ [Lua language reference](http://www.lua.org/manual/5.1/)
+ [torch cheatsheet](https://github.com/torch/torch7/wiki/Cheatsheet) has some tutorial links and a lot of info about packages specific to certain domains.

