## Setting up FTC repository
1. Start off by forking and cloning the official [FtcRobotController](https://github.com/FIRST-Tech-Challenge/FtcRobotController) repository
2. Open the project in Android Studio using "Project from version control"
   - In your fork click the code button and copy the link
   - Paste that link in the option to import form version control and wait
3. You should have a base repository that you can write code
   - FtcRobotController.TeamCode.java.org.firstinspires.ftc.teamcode
### Installing dependencies
- [FTCLib Installation Instructions](https://docs.ftclib.org/ftclib/installation)
- Follow the steps in these instructions to install FTCLib
- [RoadRunner Installation 0.5.X](https://learnroadrunner.com/installing.html#method-1-downloading-the-quickstart)
  - RoadRunner has multiple versions they run, 1.0.0 and 0.5.X
  - 1.0.X lacks documentation and therefore isn't good for our needs
  - 0.5.X has LRR(learnroadrunner), this isn't the official documentation which is why its so much better than the official 1.0.X documentation
  - For this reason, we can't use the roadrunner quickstart repository for our needs
  - RoadRunner also includes FTCDashboard so you won't have to install that dependency on its own
- EasyOpenCV doesn't require installation
- [RRPathGen](https://learnroadrunner.com/tool/rrpathgen.html#rrpathgen) is the easiest way to write paths and this is the link to it, downloaid the .exe file and run it through terminal
___

- Sync gradle
- Now your repository is set up and you can write your subsystem code in FtcRobotController.TeamCode.java.org.firstinspires.ftc.teamcode
- Make sure to orgnaize your code into subsystems, commands, vision, and auton
