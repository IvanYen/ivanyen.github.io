## Anaconda

* What is Anaconda:

  * Virtual Environment
  * Package management for Python

* Usefule Conda commands:

* ```
  # update conda in your default environment 
    $ conda upgrade conda
    $ conda upgrade --all
  # create a new environment with conda
    $ conda create -n [my-env-name]
    $ conda cerate -n [my-env-name] python=[python-version]
  # activate the environment you created
    $ source activate [my-env-name]
  # take a look at the environment you created
    $ conda info
    $ conda list
  # install a package with conda and verify it's installed
    $ conda install numpy
    $ conda list
  # take a look at the list of environments you currently have
    $ conda info -e
  # remove an environment
    $ conda env remove --name [my-env-name]
  ```

* Launch Jupyter Notebook:

* ```
  # launch Jupyter Notebook
    $ jupyter notebook
  ```


