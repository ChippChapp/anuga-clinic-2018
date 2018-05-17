# ANUGA Clinic 2018
Repository to contain the material for the 2018 CSDMS ANUGA Clinic, The aim of the clinic is to present the basic ideas of producing an ANUGA domain, which entails creating an appropriate trangulated mesh, setting up intial conditions, and boundary conditions, operators such as flow inlets and then run (evolve) the simulation. Within the constraints of a jupyter notebook we will also see how to extract data from an `sww` file (the standard ANUGA output file) and visualise the output.  

The clinic is composed of 3 jupyter notebooks:

* [Notebook 1: Introduction to ANUGA](notebooks/notebook1.ipynb)
  - Here we introduce the idea of creating a `domain` which contains the mesh and quantities needed to run the simulation, and encapsulates the methods for setting up the initial conditions, the boundary conditions and the method for evolving the solution. 

* [Notebook 2: Merewether Flood Case Study](notebooks/notebook2.ipynb)
  - Here we look at a case study of a flood in the community of Merewether.  We will add a flow using an `Inlet_operator` and extract flow details at various points by interagating the `sww` file which is produced from each ANUGA run. 

* [Notebook 3: Create a simple erosion Operator](notebooks/notebook3.ipynb)
  - Still in development

## Colaboratory

These notebooks have been designed to run in the google `colaboratory` environment, which provides a jupyter notebook environment running on a virtual machine in the cloud. To use this environment you need a google account so that your copies of teh notebooks can be saved on google drive. 

Once you have your google account, you can start interacting with the notebooks by openning up the notebook and then following the `View in Colaboratory` at the top of each notebook. This will start up a virtual environment associated with your google account where you can run the code in the notebook (and save any changes you might make).

## More Examples

If you are interested in learning more about ANUGA, the github repository has [documentation](https://github.com/GeoscienceAustralia/anuga_core/tree/master/doc), [example code](https://github.com/GeoscienceAustralia/anuga_core/tree/master/examples) and over 30 [validation tests](https://github.com/GeoscienceAustralia/anuga_core/tree/master/validstion_tests).
