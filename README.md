# Pre-requistes
### Visual Studio IDE
* The project is coded using the Asp.NET Core Framework and hence require that an Visual Studio IDE either [Visual Studio Community 2019](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Community 2022](https://visualstudio.microsoft.com/downloads/) be used to run the project. 
* Do also ensure that with you have selected the '**ASP.NET and Web Development**' workload when installing the IDE.  

### Additional SDKs
The project is coded using the [.NET Core 3.1.415 SDK](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-3.1.415-windows-x64-installer) as it has Long Term Support(LTS) and require the [Asp.NET Core 3.1.21 Runtime](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-3.1.21-windows-x64-installer) to run the project.

# Running the Project
1. Open the `2101WebPortal.sln` file with a Visual Studio IDE
<br />![Open Solution Image](https://res.cloudinary.com/dj6afbyih/image/upload/v1637216507/ict1004/odkv89lttlexndkhxexd.jpg)
2. Right-click the Project (`2101WebPortal.csproj`) & Click `Build 2101WebPortal`
<br />![Right Click Build Project](https://res.cloudinary.com/dj6afbyih/image/upload/v1637216507/ict1004/odkv89lttlexndkhxexd.jpg) 
3. Once the Output Console display that there is `0 failed`, Click on the green play icon to Run the project.
<br />![Run Project](https://res.cloudinary.com/dj6afbyih/image/upload/v1637216507/ict1004/odkv89lttlexndkhxexd.jpg)

# Seed Data
To aid the testing of the system, we have seeded some data into the database for demostration purposes. The information of the seed data can be viewed in the [Wiki](https://github.com/cweiwenr/ICT2101-team-p3-3/wiki/Seed-Data).

# Development Workflow

> + Main branch
>> + Dev branch
>>> Checkout to individual feature branches
>>>> + Work on Feature
>>>> + Commit, push and reference issues
>>>> + Create PR
>>> + Code Review
>>> + Merge PR and handle conflicts
>> + PR to Main for final prototype release

# User Acceptance Testing
The team conducted UAT on the complete system. The State Diagram and Use Case Diagrams have been updated from the M2 report as shown below for the UAT. 

### Use Case Diagram
![WBTestImagePreview](https://res.cloudinary.com/dc6eqgbc0/image/upload/v1638108353/M2_-_use_case_diagram_llqutc.png)

### Full System State Diagram
![WBTestImagePreview](https://res.cloudinary.com/dc6eqgbc0/image/upload/v1638108358/newest_state_-_Copy_of_Copy_of_Page_1_1_rfu02u.png)

### Unit Test Cases
The test cases used for the black box testing can be found in the [Wiki](https://github.com/cweiwenr/ICT2101-team-p3-3/wiki/Test-Cases-for-User-Acceptance-Testing)

### UAT Test Demo
[![WBTestImagePreview](https://res.cloudinary.com/dj6afbyih/image/upload/v1638179472/Screenshot_2021-11-29_at_17.49.17_ed4gwl.png)](https://www.youtube.com/watch?v=kCtZK9qRJxc "ICT2x01 team3-p3 UAT")

# White Box Testing
The team decided to conduct unit testing on the `ChallengeController` class using the built-in testing framework, XUnit offered with Visual Studio IDE. This is because the `ChallengeController` is required to interact with the Database Context class and the Model class to perform create, update and delete operations.

### Unit Test Demo
[![WBTestImagePreview](https://res.cloudinary.com/dj6afbyih/image/upload/v1638017614/ict1004/Screenshot_2021-11-27_at_20.53.09_kdpfxz.png)](https://www.youtube.com/watch?v=74vZE54VEos "ICT2X01 P3-3 White Box Testing")

### Unit Test Statistics

### Test Cases
| S/N | Test Name                                                               | Method Being Tested | Expected Outcome |
| --- | ----------------------------------------------------------------------- | ------------------- | ---------------- |

