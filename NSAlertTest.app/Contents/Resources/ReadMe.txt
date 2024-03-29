NSAlertTest

"NSAlertTest" is a Cocoa sample application that demonstrates how to use the NSAlert class.
It covers all aspects of setting up an NSAlert for customization.
It's also useful for visually prototyping your alerts before actually writing any code.

As a bonus, it illustrates how to integrate a Help Book connected with the alert, complete with help anchors.

===========================================================================
Sample Requirements
The supplied Xcode project builds with Mac OS X 10.6 and runs on 10.5.x or later.

===========================================================================
About the Sample
"NSAlertTest" shows you how to customize and manipulate NSAlert in the following ways:

1. Alert styles using NSAlertStyle
2. Default, Second and Alternative button titles
3. Suppression checkbox using setShowsSuppressionButton
4. Accessory view using setAccessoryView
5. Help button with Help Book Support using setShowsHelp
6. Custom alert icon using setIcon
7. Message and informative text
8. Showing as an alert sheet


===========================================================================
Packaging List
AppDelegate.{h/m} -
	NSApp's main delegate, manages MyWindowController and helps open the sample's ReadMe from the Help menu.
    
MyWindowController.{h/m} -
	The NSWindowController object for the sample's main window.
    
background.png
	Used as the custom background for the NSAlert's accessory view.
    
moof.png
	Used as the custom icon for NSAlert.
    
ExtraAlertView.{h/m} -
	Custom NSView used as the accessory view and to draw a custom background image.


===========================================================================
Changes from Previous Versions
n/a


===========================================================================
Feedback and Bug Reports
Please send all feedback about this sample by connecting to the Contact ADC page.
Please submit any bug reports about this sample to the Bug Reporting page.

Developer Technical Support
The Apple Developer Connection Developer Technical Support (DTS) team is made up of highly qualified
engineers with development expertise in key Apple technologies. Whether you need direct one-on-one
support troubleshooting issues, hands-on assistance to accelerate a project, or helpful guidance to
the right documentation and sample code, Apple engineers are ready to help you.
Refer to the Apple Developer Technical Support page.

Copyright (C) 2011 Apple Inc. All rights reserved.