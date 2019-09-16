# Electrical and electronic circuit multiobjective optimization
This project is dedicated to the optimization of (any) electrical and electronic circuits and components using evolutionary and heuristic algorithms incorporated with HSPICE.

We provide Optimer which is a user graphical interface for circuit design and optimization. Optimer benefits from following features:
   - Does not have new syntax;
   - Does not need any extra coding, just implement your circuit code for HSPICE simulation;
   - Has easy to use and managed settings for optimization algorithm, circuit parameters, and objectives (circuit specifications);
   - Can save state for later usage;
   - Gives a whole defined values in report file very easily;
   - Utilizes the most powerful multiobjective optimization algorithm (NSGA 2);
   - Utilized the most accurate circuit simulator (HSPICE);
   - Accepts unlimited number of circuit parameters (e.g. R, C, L, Transistor W and L, Value of voltage and current sources, etc.);
   - Accepts unlimited number of circuit objectives (circuit specifications, e.g. Gain, Noise, Power dissipation, Matching, Balance, Stability, Linearity, THD, Transient Response, etc.);
   - Can manage parallel optimization projects;
   - Has netlist editor;
   - And so on ...


To use Optimer, first make an account with https://www.circuitoptimization.com and then download the setup file and run it to install Optimer on your system. Optimer works in Windows operating system. After installation, using site credentials, login to the application and follow the steps below to create new optimization project:


   1- Optimer: File -> New -> Project

   Create or choose a folder to store optimization project. After that, a new window will be appeared.
   
   
   2- Netlistor:

   a) Choose and set NSGA2 options and parameters;
   b) Choose HSPICE simulator address;
   c) Create or choose main circuit netlist file;
   d) Choose or create report file;
   e) Set circuit parameters;
   f) Set optimization objectives;
   g) Save the created state;
   h) Run optimization.
   
   
   3- Investigate the optimization results

   Look at report file and sort data according to your need to find best results which suit your circuit objectives.
