# Welcome #

This is the source code for all the examples and games in the book "Beginning Android Games", written by Mario Zechner, published by Apress in April 2011. The book is available directly from [Apress](http://www.apress.com/9781430230427), from [Amazon](http://www.amazon.com/Beginning-Android-Games-Mario-Zechner/dp/1430230428/ref=sr_1_1?ie=UTF8&s=books&qid=1299265138&sr=8-1) and various other outlets.

# Quickstart Video #
<a href='http://www.youtube.com/watch?feature=player_embedded&v=fWHi31gqedY' target='_blank'><img src='http://img.youtube.com/vi/fWHi31gqedY/0.jpg' width='425' height=344 /></a>

# Setting Up the Development Environment #
For the code to run you will need:

  * The Oracle [Java SDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
  * The [Eclipse IDE for Java Developers](http://www.eclipse.org/downloads/)
  * The latest [Android SDK](http://developer.android.com/sdk/index.html)
  * The Android Development Tools (ADT) plugin for Eclipse.

Installing the JDK and Eclipse is straight forward. For the former just execute the setup program, for the later unzip the zip file to a folder of your choice and run the Eclipse executable.

Installing the Android SDK and the ADT plugin is described [here](http://developer.android.com/sdk/installing.html) and [here](http://developer.android.com/sdk/eclipse-adt.html). The book also explains how to set everything up.

# Getting the Code #
The first thing you want to do is downloading the code. For this you'll need to install a Subversion client.

  * Windows: [Tortoise SVN](http://tortoisesvn.tigris.org/)
  * Linux/Mac OSX: command line installation of Subversion

Once you have your prefered SVN client, just point it at http://beginning-android-games.googlecode.com/svn/trunk/ and check out all the Eclipse projects for each chapter.

# Importing the Projects to Eclipse #
Next you want to import the projects into Eclipse

  1. Open Eclipse and create a new workspace (File -> Switch Workspace -> Other... then just select a (new) empty directory)
  1. Wait for Eclipse to reload, close the "Welcome" View (click the "x" in the upper left corner).
  1. Goto File -> Import, in the dialog select General -> Existing Projects into Workspace.  Then click "Next".
  1. In the next dialog select the root directory which is the one you downloaded the projects to. Once selected you should see a list of projects marked for import.
  1. Check "Copy projects into workspace" and then finish the operation by clicking "Finish".
  1. Once Eclipse is done importing the projects you should see the projects in your package explorer.
  1. If the projects contain errors you have to go to Project -> Clean, select "Clean all projects" in the upcoming dialog, and press the "OK" Button. This will rebuild all the projects and make sure that all Android specific resources are created.
  1. profit :)

# Running the examples #
That's the easy part! I assume you either have a device connected or created an emulator already as explained in the book (or the [Android developer guide](http://developer.android.com/guide/developing/devices/managing-avds.html)).

  1. Right-click on the project you want to run and select Run As -> Android Application
  1. In the upcoming dialog (if you have multiple devices/emulators connected) select the device/emulator you want to run the project on
  1. The project should now run happily on whatever device/emulator you selected.

# Reporting Problems #
In case you stumble upon a potential bug (no code is perfect) please use the [issue tracker](http://code.google.com/p/beginning-android-games/issues/list) and file an issue. Just fill out the template so i can reproduce the problem and i'll have a look at it. The fixed version will be commited to SVN and you can simply fetch an update  with your SVN client.

# Discussion #
For discussion of the book and its code use the forums over at http://badlogicgames.com/forum/viewforum.php?f=21. Share your games, questions and ideas!