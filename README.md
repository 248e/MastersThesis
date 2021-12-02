# MastersThesis
Thesis for my masters in Computer Science.

You can find here my written (in LaTeX) master’s thesis as a .pdf, the code in Swift for the app, both videos for the evaluation (one in German for a online survey with an old UI, one in English for a alpha test a Bulgarian startup did with a new UI, and an Extended Abstract for CS&P’21: 29th international Workshop on Concurrency, Specification and Programming. 


The Swift code for the app can be downloaded here: 
https://drive.google.com/file/d/18FhpLZ2FPQuDrYdETSjANarStrw8y3sB/view?usp=sharing


GitHub made some problems uploading it here, I guess it's the size. About 250 MB in total, of which the pods take up about 50 MB and the flower classifier around 200 MB. 
Git Large File Storag, an open source project, would perhaps allow uploading. 


MacOS Version 10.15.7 and Xcode 12.4 was used / is needed (or above). The iPhone SE (2nd generation) was taken as the basis because I also physically own it. 

Due to the pods do not start the project with Prototype.xcodeproj but with Prototype.xcworkspace

Code with camera functions has been disabled because otherwise it won't work via the simulator. Affected code has CAM as comment in the places. Affected classes for this are ViewController.swift and FloatingPanelviewController.swift (//comment out for CAM for simulator),
and also APIManager.swift (//FUTURE weather commented out).
