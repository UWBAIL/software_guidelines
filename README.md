# software guidelines
This page is the software guidelines for UWBAIL team. This is an "open source" guideline. Everyone is welcome to discuss and suggest amendings.
## 1. Preface
1.1 The purposes of this guidelines are:
* To make lab softwares easily accessed by all lab members.
* To encorage collaborative developments to improve efficiency.
* Standarize software developing practices.
* Maintain central management by lab director and project managers.
1.2 The guidelines are in compliance with intellectual property policies of the University of Washington. The copyright of any work produced by UW employee does not belong to the individual, but to the cooperation. The lab director should have full access to any software, including its source codes, and reserves the rights to revoke an individual's access to any software at any time. 
## 2. Software developer's guidelines
2.1 When starting a new research project, create a *private* repository, and then fork it to UWBAIL (i.e. grant UWBAIL full access). **This branch becomes a lab-managed branch.**
2.2 Only use software on lab-managed branch to produce results intended for formal reports (including group meeting reports)
2.3 When the function of a developing software becomes stable, merge into your "master" or "release" branch, and make sure the lab-managed branch is synchronized.
2.4 If your new project is not a standalone, all-new project, it is most likely dependent on an existing, up-stream major project. In this case, do not create new repository but instead, fork the upstream repository. New programs are considered as extensions to current programs.
2.5 Each developer is responsible for keeping the lab-managed branch updated with their own branch. Again, only lab-manahed branches are allowed on lab computers/servers.
