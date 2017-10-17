# software guidelines
This page is the software guidelines for UWBAIL team. This is an "open source" guideline. Everyone is welcome to discuss and suggest amendings.

## 1. Preface

1. The purposes of this guidelines are:
* To make lab softwares easily accessed by all lab members.
* To encorage collaborative developments to improve efficiency.
* Standarize software developing practices.
* Maintain central management by lab director and project managers.

1. The guidelines are in compliance with intellectual property policies of the University of Washington. The copyright of any work produced by UW employee does not belong to the individual, but to the cooperation. The lab director should have full access to any software, including its source codes, and reserves the rights to revoke an individual's access to any software at any time. 

## 2. Software developer's guidelines

1. An individual does not have the copyright of any lab-developed software. Distributing any software to anyone outside the lab is  **prohibited**, without approval from UW.

1. Do not put copyright information or lisences inside source code, unless it is approved for distribute.

1. Do not include your name in file/function names. Your contributions are tracked automatically by GIT system. 
    > It is allowed to include "author" information inside source code as comments.

1. Maintainability: Always include necessary comments inside your source code, anyone with similar backgroud should be able to read your source code without face-to-face tutorials.

1. Extensibility: Build your softwares in modules, and provide necessary interfaces so it can be easily used as dependency.

1. Efficiency: Dirty solutions should be avoided. Your software should run fast enough for the resourses it consumes.

## 3. Version control guidelines

1. To start a new research project, create a *private* repository, and then fork it to UWBAIL (i.e. grant UWBAIL full access). **This branch becomes a lab-managed repository.**

    > Lab-managed repository are visible at [github.com/UWBAIL](https://github.com/UWBAIL)
    
1. If your new project is dependent on an existing, up-stream project(i.e. if you need any existing code for your new project), **do not** create new repository but instead, work on a branch from the upstream repository.

    > e.g. If you work on flow velocimetry, it should be a branch of [UWBAIL/OCTA](https://github.com/UWBAIL/OCTA)

1. To add new feature, create a developing branch. Name the branch after your intended feature.

    > e.g. To add "mouse retina segmentation" feature, you should create a branch called "mouse retina seg" under [UWBAIL/OCTA](https://github.com/UWBAIL/OCTA)

1. When the developing branch becomes stable, make a pull request to merge into **lab-managed** "master" branch. It is recommended to request a code review in this pull request.

1. It is recommended to work on **lab-managed** repositories directly. If you choose to work on your own directory, you are responsible for keeping the lab-managed repository updated with your developing branch. 

1. Only **lab-managed** software are allowed to run on lab computers/servers.

1. Only **lab-managed** branches are allowed to produce results for formal reports (including group meeting reports).

1. Only **lab-managed *master* branch** software are allowed to produce the results for publications.

## 4. Software management on lab computers

1. Each OCT system has a designated system manager, System managers should have read/write access to lab-managed repositories.

1. To access lab-managed software, system manager should use github desktop and log-on with their github account.

1. It is system manager's responsibility to clone lab-managed repositories to OCT system computer, and add them to matlab/labview search paths.

1. Irrelavent softwares and un-managed developing branches are not allowed on lab computers.

## 5. Revisions of the guidelines

This guideline is open for discussion. Revisions can be made by making a pull request on this "software_guideline" repository.
