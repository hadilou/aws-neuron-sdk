.. _mxnet-tutorial-setup:

MXNet Tutorial Setup
====================

#. Launch an Inf1.6xlarge Instance:
    .. include:: /neuron-intro/install-templates/launch-inf1-dlami.rst

#. Set up a development environment:
    * Enable or install MXNet-Neuron: :ref:`install-neuron-mxnet`.
    

#. Run tutorial in Jupyter notebook:
    * Follow instruction at :ref:`Setup Jupyter notebook <setup-jupyter-notebook-steps-troubleshooting>` to:
    
      #. Start the Jupyter Notebook on the instance
      #. Run the Jupyter Notebook from your local browser

    * Connect to the instance from the terminal, clone the Neuron Github repository to the Inf1 instance and then change the working directory to the tutorial directory:

      .. code::

        git clone https://github.com/aws/aws-neuron-sdk.git
        cd aws-neuron-sdk/src/examples/mxnet

    * Locate the tutorial notebook file (.ipynb file) under ``aws-neuron-sdk/src/examples/mxnet``
    * From your local browser, open the tutorial notebook from the menu and follow the instructions.