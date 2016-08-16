Keras experiments
=================

Experiments done using the keras neural networks lib.

Python requirements listed in the ``requirements.txt`` file. And if you want to run it using the gpu (provided you have support for it and the required dependencies), you can do it with:

.. code:: bash

    THEANO_FLAGS="mode=FAST_RUN,device=gpu,floatX=float32,cuda.root=/usr/local/cuda/" ipython notebook


A ``test_gpu.py`` script is provided to validate if you are running it under the cpu or gpu. Run it in that same way to check if your gpu is working. (script copied from the Theano docs)
