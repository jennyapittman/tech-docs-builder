# tech-docs-builder
User interface to build MadCap Flare targets

Instructions:
The Tech Docs Builder allows you to choose which targets you want to build across multiple projects and to build them all at once.

1.  For the builder to work, place the builder.hta file in the Windows folder where your Flare projects live. The projects can be all in one main folder or in any number of subfolders.

2.  Make sure that each project is uniquely named and that each project has the same name as its immediate folder (e.g. EN-Remote-Support\EN-Remote-Support.flprj).

3.  Open builder.hta. Select one or more projects, and then click Next or press Enter.

4.  Select one or more targets, and then click Next or press Enter.

5.  Review your build summary. You can Copy Text to your clipboard, pasting the list in Word or another program to review your selections more easily.

6.  You can click any step to modify the results. Be sure to click Next or press Enter after making a change. If you want to clear all selections, click Reset All.

7.  Click Start Build Now or press Enter.

8.  The first time you run this script, it creates a Build.cmd file. Every time thereafter, it modifies that file. When the builder runs Build.cmd, a command line interface opens, and a BuildOutput.txt file is created.

9.  The builder starts building the files. You will see the progress of your builds as they are started and completed. If an error occurs during a build, the information from the build log displays.

10. If you want to cancel a build you've started, click Cancel Build. Your build will stop within five seconds.

11. If you want to see all build messages as they are generated, click See Full Build Log. To return to the summary, click Return to Step View.

12. When the command line interface closes, your selected builds should be complete. You will see a completion message in the builder. You can access your builds in the Output folder of each project - or wherever your targets are configured to save.

Note: If you close the command line interface or delete either Build.cmd or BuildOutput.txt before all builds are complete, the build cancels. If you do need to intentionally cancel a build in progress, it is better to click Cancel Build.
