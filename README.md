# JenkinsProject

  # What is Jenkins?
  
  Jenkins is a free and open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous       integration and continuous delivery.
  
  # Install Plug-ins:
  
  JUnit Plugin (1.50)
  
  Plugin is missing: echarts-api (4.9.0-3)
  
  Indirectly dependent plugins:
  
  Email Extension Plugin (2.83)
  
  Failed to load: JUnit Plugin (1.50)
  
  Pipeline (2.6)
  
  Failed to load: Lockable Resources plugin (2.11)
  
  Workspace Cleanup Plugin (0.39)
  
  Failed to load: Matrix Project Plugin (1.19)
  
  Lockable Resources plugin (2.11)
  
  Failed to load: Matrix Project Plugin (1.19)
  
  Matrix Project Plugin (1.19)
  
  Failed to load: JUnit Plugin (1.50)
  
  # Installation Path
  
  Bash completion has been installed to:
  /usr/local/etc/bash_completion.d

  Emacs Lisp files have been installed to:
  /usr/local/share/emacs/site-lisp/git
  
  Jenkins Workspace Path:
  /Users/abaqus/.jenkins/workspace
  
  # Features of Jenkins:

  I) Easy installation
  
  ii) Easy Configuration
  
  iii) Plugins
  
  iv) Extensible
  
  v) Distributed
  
  # Jenkins Start & Stop Command: 

  brew services start jenkins-lts (Jenkins Start)

  brew services start jenkins-lts(Jenkins Stop)
  
  # Jenkins Master-Slave Architecture

  CI —> Continous Integration
  
  CD —> Continuous Delivery / Continuous Deployment

  Continuous Integration is the practice of running  your tests on a non-developer machine.
  
  automatically every time someone pushes new code into the source repository.

  Continuous delivery is like a preparation process. The process of making the code to be deployable.

  Continuous deployment is the actual process of deployment into the production server and makes it available for the intended users.
  
  # What are all the way to build the projects in Jenkins?

  i) BuildNow (Manual)

  ii) Periodically Schedule (Based on the time) —> The time format has to follow the link https://crontab.guru/

  iii) Based on the another projects build downstream project



<img width="1440" alt="Screen Shot 2021-06-08 at 8 11 15 AM" src="https://user-images.githubusercontent.com/39657409/121471332-1f004980-c9dd-11eb-9ceb-377ca1850a12.png">
<img width="1305" alt="Screen Shot 2021-06-09 at 6 14 17 PM" src="https://user-images.githubusercontent.com/39657409/121471375-30495600-c9dd-11eb-965d-a64d306e1a08.png">
<img width="1436" alt="Screen Shot 2021-06-09 at 8 10 32 PM" src="https://user-images.githubusercontent.com/39657409/121471414-3fc89f00-c9dd-11eb-93ef-c35ad258caa3.png">
<img width="1440" alt="Screen Shot 2021-06-09 at 8 17 31 PM" src="https://user-images.githubusercontent.com/39657409/121471431-4820da00-c9dd-11eb-9bf1-a11b4e8c7de4.png">
<img width="1439" alt="Screen Shot 2021-06-10 at 9 02 40 AM" src="https://user-images.githubusercontent.com/39657409/121471449-540c9c00-c9dd-11eb-8162-2d46e55022bb.png">

 ## Install Delivery Plugin -> Build -> Deploy->Test -> Release

<img width="1440" alt="Screen Shot 2021-06-10 at 9 05 50 AM" src="https://user-images.githubusercontent.com/39657409/121471476-6090f480-c9dd-11eb-955f-3add6b26554e.png">
<img width="1437" alt="Screen Shot 2021-06-10 at 11 12 45 AM" src="https://user-images.githubusercontent.com/39657409/121471576-903ffc80-c9dd-11eb-8365-07a36e919637.png">
