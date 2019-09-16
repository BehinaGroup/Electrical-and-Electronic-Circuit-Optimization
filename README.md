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

# Optimer
Optimer is a graphical user interface with all options of optimization algorithm settings and circuit variables. Optimer is very easy to use. To use Optimer:
   1. First make an account with https://www.circuitoptimization.com
   2. Download the setup file and run it to install Optimer on your system. Optimer works in Windows operating system.
   3. After installation, using site credentials, login to the application and follow the steps below to create new optimization project:
   4. Optimer: File -> New -> Project :
      - Create or choose a folder to store optimization project;
      - After that, a new window will be appeared.
   5. Netlistor:
      - Choose and set NSGA2 options and parameters;
      - Choose HSPICE simulator address;
      - Create or choose main circuit netlist file;
      - Choose or create report file;
      - Set circuit parameters;
      - Set optimization objectives;
      - Save the created state;
      - Run optimization.
   6. Investigate the optimization results :
      - Look at csv report file and sort data according to your need to find best results which suit your circuit objectives.
