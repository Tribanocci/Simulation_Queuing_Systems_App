# Simulation_App

## Descprition of the App
This is a Windows application developed using the Windows Forms framework in C++/CLI. The application utilizes a graphical user interface (GUI) created with Windows Forms to gather the required input data for simulating the performance of a queuing system. The queuing system can be modeled using either the M/M/n/K model or the Flow Model.

The simulation algorithm for the queuing system is implemented in C++ using the Object-Oriented Programming (OOP) paradigm.

The application is composed of several files. These include the header and cpp files for the simulation algorithm. The input required for the SimulationModels.cpp file is obtained through the Windows Form interface. The structure of the Windows Form is defined in MyForm.h, and its corresponding functionalities are implemented in the MyForm.cpp file. This separation allows for a clear organization of the GUI design and the simulation logic.
## Purpose of **Enhance_UI branch**
In this branch, a new project of developing a more appealing and modern UI interface with Ribbon, imported from [Fluent.Ribbon](https://github.com/fluentribbon/Fluent.Ribbon) repo, will take place. 

### Project steps

The process of the UI enhancement, follow these steps:

1. **Import Fluent.Ribbon and incoporate tags**.
   
2. **Connect the back-end algorithm of the system's simulation with the App UI**:
   - "Input Data through graphical interface."
   - "Output result representation."

3. **Documentation and graphical interface for user-friendly App**:
   Addition of tooltips and graphical ibjects for making the input data more intuitive.

4. **Add new features and capabilities**:
   Explore posibilities for further enhancement.



