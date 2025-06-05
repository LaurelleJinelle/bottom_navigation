# Bottom Navigation in Flutter
Bottom Navigation helps you navigate through different screen in your flutter app, and is always at the bottom of the screen, hence the name "Bottom Navigation"

In flutter, there is an already existing BottomNavigatorBar widget, which works inside the Scaffold widget. This is the widget you use whenever you want to specify bottom naviagtion

Some key attributes that the BottomNavigationBar has include;
1. items - This allows you to specify the tabs and icons that you want to be in your navigation bar. I like to think of it as a list of menu bottons. This is important because you can specify the nuber of icons, which by extension helps you spcify the number of screens in your mobile app. Another thing to note is that the order of icons/buttons, determines the index that would be passed in the onTap attribute.
2. currentIndex - This just helps you know which screen/tab you are currently on.
3. onTap - This is called when the user taps on any icon/button in the navigation bar. It contains the function that you have specified to handle the logic for moving to another screen.


In summary, bottom navigation helps you achieve seamless navigation through multiple screens of your mobile app.

To see a demo, feel free to clone this repository and run the main.dart file.
