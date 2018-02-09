# Hello, Android!

The project HelloAndroid is the first project for Google Android Basics Scholarship with Udacity.

The project consists of a simple layout with a combination of various views to depict a Contact information ‘page’ (or activity) for Udacity. The project currently serves as a simple experimentation with nesting RelativeLayouts and various views. It remains purposefully inefficient. Also, the icons (particularly those on the right side of the screen) while they are suggestive calls-to-action (i.e. clickable ImageButtons), they are currently inactive and will remain so as interaction with the ‘page’ is beyond the scope of this project.

When built and run the project displays on a mobile device (Nexus 5, in this case) like this:

### Screenshots

![alt text](https://github.com/AppsDJ/HelloAndroid/blob/master/udacity_portrait.png)
![alt text](https://github.com/AppsDJ/HelloAndroid/blob/master/udacity_land.png)


### On Layouts
Currently the portrait orientation uses an outer LinearLayout with inner nested RelativeLayouts, whereas the landscape orientation uses only nested RelativeLayouts. This is intentional for practice purposes only and not for efficiency.
This project will subsequently be converted to use the newer and more efficient ConstraintLayout.
