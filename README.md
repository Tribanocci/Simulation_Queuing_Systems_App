# Simulation_App

## Descprition of the App
This is a Windows application developed using the Windows Forms framework in C++/CLI. The application utilizes a graphical user interface (GUI) created with Windows Forms to gather the required input data for simulating the performance of a queuing system. The queuing system can be modeled using either the M/M/n/K model or the Flow Model.

The simulation algorithm for the queuing system is implemented in C++ using the Object-Oriented Programming (OOP) paradigm.

The application is composed of several files. These include the header and cpp files for the simulation algorithm. The input required for the SimulationModels.cpp file is obtained through the Windows Form interface. The structure of the Windows Form is defined in MyForm.h, and its corresponding functionalities are implemented in the MyForm.cpp file. This separation allows for a clear organization of the GUI design and the simulation logic.
## Purpose of **Enhance_UI branch**
In this branch, a new project of developing an more appealing and modern UI interface with Ribbon (imported from [Fluent.Ribbon]([https://github.com/fluentribbon/Fluent.Ribbon](https://github.com/fluentribbon/Fluent.Ribbon)) repo) will take place

## Running the App

To successfully build and deploy the application, follow these steps:

1. **Install Microsoft Visual Studio (_NOT_ VS Code)**.
   
2. **Install the following workloads**:
   - "Desktop development with C++"
   - ".NET desktop development"

3. **Open the project file**:
   Launch Microsoft Visual Studio and open the project file named "Simulation_App.sln".

4. **Build the App**:
   Build the application by clicking on the Play button located at the top of the IDE.

By following these steps, you can effectively set up and utilize the Simulation App for simulating queuing system performance.

