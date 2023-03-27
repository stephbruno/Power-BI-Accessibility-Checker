# Power-BI-Accessibility-Checker

Use the Power BI Accessibility Checker to understand whether your Power BI report meets minimum accessibility standards, and find where and how you can make improvements to the accessibility of your report. This checker looks at three top areas for accessbility: Tab Order, Alt Text, and Color Contrast. It also checks the color contrast of your report's selected theme.

Disclaimer:  This is version 1.  Please let me know if you run into any errors with it.

# Instructions
Download the Power BI Field Finder.pbit template file.  

1.  Open the Accessibility Checker.pbix file. You'll see the accssibility checks of the sample WoW 2023 Week 8 sample file. To have it run checks against your files, change the report parameters to point to a location on your computer (and optionally a specific file, or whether to include subfolders). For example, if you your pbix file is saved in C:\Test Files and is named "My Report", then the value for this parameter should be "C:\Files" and optionally you can include the name of yoru report.

2.  Click the Load button, and easily see your tab order and alt text on the following pages. Color contrast is a bit trickier, so for this version you can enter a hex code for a color that you'd like to compare against the colors on your visuals. This color is also compared against the colors of the selected theme.

3.  When you make changes to your pbix file, save it and refresh the Power BI Accessibility Checker.  If you'd like to analyze a different report, update the parameter to the file path and filename of another pbix file.

Further information can be found in this Workout Wednesday post: https://workout-wednesday.com/pbi-2023-w12/

# Sample File
The pbix used in the sample pbix file is based on the Workout Wednesday Week 8 file, and is included in this repo.

# Known Issues
- Currently working on how to compare two colors that are against each other in a single visual. 

# Latest Changes
1.0 - First version

