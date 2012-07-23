Tutorial - Docking a HIV Protease Inhibitor
===========================================

Indinavir is a HIV Protease Inhibitor. Going to dock against...a HIV Protease (iPDB code of 1hsg).

Follow the `PyRx tutorial`_ to run a docking experiment, and carry out a virtual screen. The notes below give extra information (or corrections) on each step of the tutorial.

.. _PyRx tutorial: _static/PyRx2010_rvsnALP_7122010.pdf

.. note:: Part 1 of the tutorial using **AutoDock**, but Part 2 uses **Vina**. Make sure you are using the correct wizard in each case.

Part 1 Exercise 1
-----------------

* In the very first step, when you click *Next*, you need to wait about 2 minutes for the file to download
    * Change address to http://pyrx.sf.net/sample.tar.gz
    * (If that doesn't work, choose local file and use `sample.tar.gz`_)
* "Click on the arrow next to hsg1" should be...
    "Click on the plus sign next to hsg1"
* Note that using the Molecules tab you can...
    * Display/hide a molecule
    * Display/hide a particular chain
    * Label a particular protein residue
* Can zoom with mouse wheel (after clicking on the 3D view)
* Full screen very useful (Esc to exit)
* Right click on a map (e.g. hsg1.A.map), and choose Display (MayaVi)
    * In the MayaVi Panel, right click on Surface, and choose Hide/Show
    * Right click on it again, and choose Add Module, Isosurface
    * Once you are finishing, right click on IsoSurface, and choose Delete

.. _sample.tar.gz: _static/sample.tar.gz

Part 1 Exercise 2
-----------------

* Choose "Local (requires local AutoDock binaries)" at the bottom of the screen
    * (We have installed both Autodock and Vina locally)


Part 1 Exercise 3
-----------------

* You will know when they are selected because it will list them at the bottom of the screen
    * (as in the screenshot in the tutorial)

Part 1 Exercise 4
-----------------

* Play around with the bounding box, then click Reset
* The Grids already exist, but let's run AutoGrid anyway
    * Instead of clicking Forward, click Run AutoGrid
    * It takes around 30s

Part 1 Exercise 5
-----------------

* Run AutoDock
    * Takes about 5 minutes

* FYI:
    * dlg = docking log file
    * On Windows 7, all log files, etc. are placed in C:/Users/myname/.mgltools/PyRx

Part 1 Exercise 6
-----------------

* Click on Binding Energy to sort the ligands
    * The one with the most negative binding energy is the strongest binder
* You can right click on a row, and choose Creating Clustering Histogram


Part 2 Exercise 1
-----------------

* Instead of opening "Desktop/PyRx2010/3D.sdf"
     Use 3D.sdf from here_ (download and save it on your Desktop).
* After you choose "Convert All to AutoDock Ligand"
    * Right-click in the Ligands folder, and choose Refresh
    * The list of ligands should appear

.. _here: _static/3D.sdf

Part 2 Exercise 2
-----------------

* When selecting the Molecules, instead of selecting them all, select only 5 or so.
    * Each docking takes about a minute on these machines
* (You can ignore the text about computer clusters for this tutorial)

Part 2 Exercise 3
-----------------

* ...we are not going to cover this now

