Марголин Илан.  2018.

В данном проекте реализована система управления движением мобильным роботом KUKA Youbot. 
часть написаная на C++ реализует Remote API и была взята с официальногосайта V-Rep(нужна для подключение C# проекта к V-Rep). 
Часть на C# написана мной и реализует методы и алгоритмы для обеспечения движения и
картографирования мобильным роботом KUKA Youbot.  

Порядок запуска программы со средой V-Rep 
1) Запустить вложенную в проект сцену (KukaYoubotRemoteApi(demo 5).ttt).
2) Запустить работу сцены в симуляторе.
3) Запустить VRepClient.sln
4) задать координату целевой точки в интерфейсе программы.
5) После запуска программы нажать последовательно кнопки "VrepAdapter" -> "Connect" -> "Drive".


П.С. проект "VrepClient" должен быть назначен как запускаемый проект.
П.П.С. Программа проверялась на работоспособность с прилогающейся версией робототехнического симулятора V-Rep. 


Margolin Ilan.  2018.

In this project, the motion control system of the KUKA Youbot mobile robot is implemented. 
The part written in C++ implements the Remote API and was taken from the official V-Rep website (needed to connect the C# project to V-Rep). 
The part in C# was written by me and implements methods and algorithms to ensure movement and
mapping by the KUKA Youbot mobile robot. 

The order of launching the program with the V-Rep environment 
1) Launch the scene nested in the project (KukaYoubotRemoteApi(demo 5).ttt).
2) Start the work of the scene in the simulator.
3) Run VRepClient.sln
4) set the coordinate of the target point in the program interface.
5) After launching the program, press the buttons "VrepAdapter" -> "Connect" -> "Drive" sequentially.


PS The "VrepClient" project should be designated as a startup project.
PS The program was tested for operability with the attached version of the V-Rep robotic simulator.
