# Instructor guide for AZ-040T: Automating Administration with PowerShell

## Purpose of this document

Modified on 4/29 1:22pm

This document is for Microsoft Certified Trainers (MCTs) who are teaching the **AZ-040T: Automating Administration with PowerShell** course.

### Course design

This course has 11 modules that cover the use of PowerShell to automate the administration and management of Windows operating systems, Microsoft Azure services, and Microsoft 365 services. The initial modules introduce Windows PowerShell and describe its use in local systems administration. The course then explains the use of the PowerShell pipeline, PSProviders, and PSDrives. The next few modules cover the use of Common Information Model (CIM) and Windows Management Instrumentation (WMI) cmdlets, variables, arrays, hash tables, and PowerShell scripts. The final modules cover the use of PowerShell to manage remote computers, Azure resources, Microsoft 365 services, and background jobs and scheduled jobs.

### Course timing

The following tables depict the approximate daily timings for a five-day course delivery. The number of slides is an *approximation*; changes will occur over time. Duration is depicted in *h:mm*.

#### Day 1

Topic | Duration | Start time | End Time
- | -: | -: | -:
Overview | 0:30 | 9:00 AM | 9:30 AM
Module 01 (44 slides) | 1:20 | 9:30 AM | 10:50 AM
Break | 0:15 | 10:50 AM  | 11:05 AM
Lab 01 | 1:00 | 11:05 AM | 12:05 PM
Lunch | 1:00  | 12:05 PM | 1:05 PM
Module 02 (42 slides) | 1:25 | 1:05 AM | 2:30 PM
Break | 0:15 | 2:30 PM | 2:45 PM
Lab 02 | 1:00 | 2:45 PM | 3:45 PM
Module 03 (68 slides) | 1:00 | 3:45 PM | 4:45 PM
Wrap-up | 0:15 | 4:45 PM | 5:00 PM

#### Day 2

Topic | Duration | Start time | End Time
- | -: | -: | -:
Overview | 0:30 | 9:00 AM | 9:30 AM
Module 03 (68 slides, continued) | 1:00 | 9:30 AM | 10:30 AM
Break | 0:15 | 10:30 AM  | 10:45 AM
Lab 03 | 2:00 | 10:45 AM | 12:45 PM
Lunch | 1:00  | 12:45 PM | 1:45 PM
Module 04 (27 slides) | 0:50 | 1:45 PM | 2:35 PM
Lab 04 | 0:30 | 2:35 PM | 3:05 PM
Break | 0:15 | 3:05 PM | 3:20 PM
Module 05 (36 slides) | 1:10 | 3:20 PM | 4:30 PM
Wrap-up | 0:15 | 4:30 PM | 4:45 PM

#### Day 3

Topic | Duration | Start time | End Time
- | -: | -: | -:
Overview | 0:30 | 9:00 AM | 9:30 AM
Lab 05 | 0:45 | 9:30 AM | 10:15 AM
Module 06 (41 slides) | 0:45 | 10:15 AM | 11:00 AM
Break | 0:15 | 11:00 AM  | 11:15 AM
Module 06 (41 slides, continued) | 0:35 | 11:15 AM | 11:50 AM
Lab 06 | 0:45 | 11:50 AM | 12:35 PM
Lunch | 1:00  | 12:35 PM | 1:35 PM
Module 07 (78 slides) | 1:30 | 1:35 AM | 3:05 PM
Break | 0:15 | 3:05 PM | 3:20 PM
Module 07 (78 slides, continued) | 1:00 | 3:20 PM | 4:20 PM
Wrap-up | 0:15 | 4:20 PM | 4:35 PM

#### Day 4

Topic | Duration | Start time | End Time
- | -: | -: | -:
Overview | 0:30 | 9:00 AM | 9:30 AM
Module 08 (46 slides) | 1:30 | 9:30 AM | 11:00 AM
Break | 0:15 | 11:00 AM  | 11:15 AM
Lab 08 | 1:00 | 11:15 AM | 12:15 PM
Lunch | 1:00  | 12:15 PM | 1:15 PM
Module 09 (33 slides) | 1:30 | 1:15 PM | 2:45 PM
Break | 0:15 | 2:45 PM | 3:00 PM
Lab 09 | 1:00 | 3:00 PM | 4:00 PM
Wrap-up | 0:15 | 4:00 PM | 4:15 PM

#### Day 5

Topic | Duration | Start time | End Time
- | -: | -: | -:
Overview | 0:30 | 9:00 AM | 9:30 AM
Module 10 (43 slides) | 1:00 | 9:30 AM | 10:30 AM
Break | 0:15 | 10:30 AM  | 10:45 AM
Module 10 (43 slides, continued) | 0:30 | 10:45 AM | 11:15 AM
Lab 10 | 1:00 | 11:15 AM | 12:15 PM
Lunch | 1:00  | 12:15 PM | 1:15 PM
Module 11 (28 slides) | 1:15 | 1:15 PM | 2:30 PM
Lab 11 | 0:30 | 2:30 PM | 3:00 PM
Break | 0:15 | 3:00 PM  | 3:15 PM
Closing | 0:45 | 3:15 PM | 4:00 PM

## Prepare to teach

The next sections cover the main course components and how you can use them in class. This includes Microsoft PowerPoint slides, module-review questions, reference links, demonstrations and practice exercises, and labs. You have a lot of flexibility in how you use this content to create the best learning experience for your students.

### PowerPoint slides

PowerPoint slides supplement the course material to help you teach the course. Be sure to review the materials in the main course content to ensure you’re covering topics fully. If you simply repeat the content of the slides to the students, you won't have enough content to fill the scheduled time. The following list describes some of the points to remember about the course PowerPoint slides:

- The **AZ-040T00A_M00.pptx** file provides information for your first day of class. It includes a brief agenda, lists the course's modules, and provides a brief overview of the lab objectives. We recommend that you customize this file according to your specific situation, such as modifying some of the slides to match the information you want to present. For example, you could expand the information about the Windows system administrator role and discuss it in more detail with your students.
- The PowerPoint files include slides that are designated as demonstrations. The course includes a good deal of hands-on guidance that is combined with additional information to create a richer learning experience for the student.

### Azure subscriptions

You’ll perform the labs and demonstrations on a virtual lab environment by using an authorized lab hoster (ALH). To complete some of the labs and demonstrations in this course, students need an Azure subscription. The Azure subscription might be in the form of an Azure Pass that your learning provider will offer. Alternatively, the ALH might have their own Azure subscription for the course.

> **Note:** The Azure Pass effectively functions in the same way as the publicly available Microsoft Azure trial subscription, which you can create at the [Create your Azure free account today](https://aka.ms/create-azure-free-account) website. This means that there are limitations on what you can do with the pass. What's included with the Microsoft Learning Azure Passes can change over time. It's possible these changes might impact some of the demonstrations and labs. During your review of the course materials, you should ensure that you can use the Azure Pass and enabled Azure subscription to sufficiently complete the course labs and demonstrations.

> **Note:** Generally, it is the responsibility of the learning provider to order Azure Passes for students when they’re ordering courseware licenses in support of their virtual classroom offerings. Each ALH provides specific ways of using Azure. Some ALHs might use Azure Passes and others will have preconfigured Azure subscriptions available with the course. You can also refer to the [Access to Microsoft Learning Azure Passes for Students of Authorized Microsoft Learning Partners](https://aka.ms/mocazurepass) website to request Azure passes for yourself and your students. If you need to request these passes, ensure that you do so at least two weeks before the class starts. After receiving the passes, each student will need to activate their pass.

### Labs

All the modules in this course include labs. The lab guides are available in the Microsoft Learning GitHub repository for AZ-040T. Most of the labs include PowerShell commands that students will enter in the PowerShell command prompt. These commands are also available in .txt files on the **LON-CL1** virtual machine. If students find it too time-consuming to enter several commands, you can ask them to copy and paste them from the .txt files.

### Demonstrations

The student materials contain the high-level steps for all the course's demonstrations. The Notes sections of the PowerPoint files include the detailed tasks that you can use to perform demonstrations as needed. You might choose to have your students follow along as you perform the demonstrations.

### Module-review questions

Each module includes module-review questions. You can supplement the module-review questions with your own questions, and you can modify the additional questions to your students' skills and experience levels. You can use the module-review questions in several ways, including the following:

- As a group, the entire class can discuss the questions before progressing to another section.
- You can cover the questions individually, as you cover the appropriate material.

### Reference links

The course content for the students includes many reference links. You should:

- Use the reference links to validate that the content is still current, before you teach the course.
- Pay attention to capabilities and limits; for example, preview features and virtual machine sizes.
- Let students know they can use the reference links after the course to review and confirm what they learned.

## Course resources

There are a several resources to help you learn about PowerShell. We recommend that you bookmark the following websites:

- [Microsoft Learn:](https://aka.ms/Microsoft-learn-home-page) Free role-based learning paths and hands-on experiences for practice
- [PowerShell Documentation:](https://aka.ms/powershell-documentation) Articles and how-to guides about using Windows Server
- [Azure PowerShell documentation:](https://aka.ms/azure-powershell-documentation) Articles and sample scripts for using Azure PowerShell
- [Get started with PowerShell for Microsoft 365:](https://aka.ms/get-started-with-powershell-for-microsoft-365) Information on using PowerShell to manage Microsoft 365

## Connect with others

- [Microsoft Learn Community:](http://aka.ms/mctcentral) Your one stop for all things MCT. Stay up to date with the latest MCT news, learn about upcoming events, find job opportunities, or connect with other MCTs around the world. You can also ask questions and discuss a variety of topics, including courseware and certification with Microsoft, and connect with other MCTs through the MCT Central Forums.
- [MOC Courseware Support:](https://aka.ms/moccoursewaresupport) If there are problems with a course or you need to log a support ticket, contact the Official Support channel for MOC courses. Support agents monitor this channel, and it's the quickest way to log your courseware-related issues. 

## Feedback

These courses are different from the traditional MOC courses that we've provided in the past. We've provided a framework for you to work with, and you should take time to prepare and think about the value that only you can bring to training. We hope to partner with you to provide an exceptional student experience, and we welcome your feedback.

Best of luck!

PowerShell Courseware Development Team
 
