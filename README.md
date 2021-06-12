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

 <img width="1422" alt="Screen Shot 2021-06-10 at 7 52 53 PM" src="https://user-images.githubusercontent.com/39657409/121543148-53e4be80-ca26-11eb-8f94-29cb528a51a9.png">


<img width="1440" alt="Screen Shot 2021-06-08 at 8 11 15 AM" src="https://user-images.githubusercontent.com/39657409/121471332-1f004980-c9dd-11eb-9ceb-377ca1850a12.png">
<img width="1305" alt="Screen Shot 2021-06-09 at 6 14 17 PM" src="https://user-images.githubusercontent.com/39657409/121471375-30495600-c9dd-11eb-965d-a64d306e1a08.png">
<img width="1436" alt="Screen Shot 2021-06-09 at 8 10 32 PM" src="https://user-images.githubusercontent.com/39657409/121471414-3fc89f00-c9dd-11eb-93ef-c35ad258caa3.png">
<img width="1440" alt="Screen Shot 2021-06-09 at 8 17 31 PM" src="https://user-images.githubusercontent.com/39657409/121471431-4820da00-c9dd-11eb-9bf1-a11b4e8c7de4.png">
<img width="1439" alt="Screen Shot 2021-06-10 at 9 02 40 AM" src="https://user-images.githubusercontent.com/39657409/121471449-540c9c00-c9dd-11eb-8162-2d46e55022bb.png">

<img width="1437" alt="Screen Shot 2021-06-10 at 7 53 21 PM" src="https://user-images.githubusercontent.com/39657409/121543230-6101ad80-ca26-11eb-8f99-b450d9ac5c98.png">
<img width="1431" alt="Screen Shot 2021-06-10 at 7 53 33 PM" src="https://user-images.githubusercontent.com/39657409/121543311-6fe86000-ca26-11eb-8718-4975aa70514c.png">
<img width="945" alt="Screen Shot 2021-06-10 at 7 54 17 PM" src="https://user-images.githubusercontent.com/39657409/121543366-7c6cb880-ca26-11eb-9a38-364ae7abe28e.png">
<img width="1204" alt="Screen Shot 2021-06-10 at 7 54 33 PM" src="https://user-images.githubusercontent.com/39657409/121543441-8abad480-ca26-11eb-8210-34d33f2e6361.png">
<img width="941" alt="Screen Shot 2021-06-10 at 7 54 50 PM" src="https://user-images.githubusercontent.com/39657409/121543510-99a18700-ca26-11eb-9498-64cd8d5b627a.png">



 ## Install Delivery Plugin -> Code Commt ->  Build -> Test -> Release -> Deploy/Deliver
 
   Pipeline is a suite of Jenkins features, installed as plugins, which enable implementing and integrating continuous delivery pipeline into Jenkins.
   
   Jenkins provides 2 ways of developing pipeline code : Scripted and Declarative.

  Scripted Pipeline: It is based on groovy script as their domain specific language. One or more nodes blocks does the core work throughout the entire pipeline.

  Pipeline is a user-defined model of a CD pipeline. A pipeline’s code defines your entire build process, which typically includes stages for building an application, testing it     and delivering it. Also a pipeline block is a key part of Declarative pipeline syntax.

  ## Node
  A node is a machine which is the part of Jenkins environment and is capable for executing pipeline. Also a node block is a key part of Scripted Pipeline syntax.

  ## Stage
  A stage block defines a conceptually distinct subset of tasks performed through the entire pipeline( e.g.: Build, Test, Deploy stages) which is used many plugins to visualise or   present Jenkins Pipeline status.

 ## Step 
 A singe task. Fundamentally a steps tells Jenkins what do to at a particular point of time.  

 
<img width="1440" alt="Screen Shot 2021-06-10 at 9 05 50 AM" src="https://user-images.githubusercontent.com/39657409/121471476-6090f480-c9dd-11eb-955f-3add6b26554e.png">
<img width="1437" alt="Screen Shot 2021-06-10 at 11 12 45 AM" src="https://user-images.githubusercontent.com/39657409/121471576-903ffc80-c9dd-11eb-8365-07a36e919637.png">
