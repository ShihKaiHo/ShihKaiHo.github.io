# HFSS
>put some HFSS tricks just for remind

* wisely use copy and paste to create object
* Enalbe GPU
  ```
  [Tools] -> [option] -> [HPC and Analysis Options] -> [option] -> [Enable GPU]
  ```
* Enalbe multi CPU

        [Tools] -> [option] -> [Genennal Options] -> [Desktop Performace] -> [number of processors]
        [Tools] -> [option] -> [HPC and Analysis Options] -> choose local machine -> [Edit] -> [core] -> write  number of cores
  

* To get a cross-section from a 3D object (can be use to assign lumped port)
  ```
  click on object -> [Modeler] -> [Surface] -> [Section] -> [XY](desired direction)
  ```
* [patch antenna calculator](http://www.emtalk.com/mpacalc.php)
* [transmission line impedence calculator](http://chemandy.com/calculators/microstrip-transmission-line-calculator.htm)
* setting multi port power
  ```
  [HFSS] -> [Fields] -> [Edit Sources]
  ```
* Create Open Region
  ```
  right click on CAD UI -> Create Open Region
  ```
* get a quick snap on data
  ```
  right click on Result in Project Managment -> [Solution data]
  ```
