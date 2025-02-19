# Lab2
## Description

In this lab, we wiill need to make the following changes based on the Projectportal example code: https://github.com/CS683/METCS683/tree/main/CodeExamples. 
You can choose to use either just activities or fragments with fragment manager or fragments with navigation components, preferrably fragments with navigation components (https://github.com/CS683/METCS683/tree/main/CodeExamples/ProjectPortalLabUseNavigation).  
- Modify the Project data class (Project.kt). Besides the project title and summary, we also want to know other information about the project such as:
  - Authors of the project
  - Project links: (e.g. youtube links, github links, etc)
  - Is this project your favorite project or do you like this project?
  - Keywords that can be used to search the project
  - Any additional information you would like to add
  - Hint: You should modify the Project data class to include the above information, e.g. boolean isFavorite/like, List links, List authors, etc.
- Modify the Project Detail and Edit UI (both the XML layout files and kotlin files, e.g. DetailFragment.kt and EditFragment.kt). Explore the design palette and pick the proper layout(s) and widgets to display these additional information (e.g. authors, links keywords) in the Detail screen and edit them in the Edit screen.
- Add a proper widget to let the user set (or unset) a project as their favorite project on the project detail screen. No need to set (unset) favorite in the edit screen. (Optional)
  - Hint: you can use Checkbox or Switch to show isFavorite or an image button to show a like button. To change its value, you can need to add another event listener in the detail page. For example, you can use CompoundButton.OnCheckedChangeListener. 
The callback function defined by this listener is onCheckedChanged(CompoundButton buttonView, boolean isChecked). It takes two parameters. 
The boolean parameter isChecked shows the new checked state of the button, which can be used to set isFavorite value. 
Check https://developer.android.com/reference/android/widget/CompoundButton.OnCheckedChangeListener for more details.

## What to submit: 
- On blackboard
  - A lab report fie in pdf or doc, including 
   - your github repo URL link
   - a description of how you designed and implemented the above requirements. Please also report any issues you have encountered and the screenshots to show the execution result. *Please specify what device or virtual device you used to execute your program.*
  - A zip file of your source code
- On github
  - Commit both your lab report (in pdf, doc or md) and code
