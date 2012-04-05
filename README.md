#Slide Notification#

By [mateuszmackowiak](http://mateuszmackowiak.wordpress.com)

SlideNotification lets you send notifications that slide up from the bottom of a view in your iOS apps.

*showMessage - shows toast message and adds to que

*showMessage2 - shows Toast message

## Sample ##

![](https://github.com/mateuszmackowiak/SlideNotification/raw/master/pic/Screenshot_2.png) 
![](https://github.com/mateuszmackowiak/SlideNotification/raw/master/pic/Screenshot_3.png) 
## Usage ##

You simply use class method <code>showMessage</code> with message, durration and an color:

    NSString* w = @"this is a short message 2"; 
    [SlideNotification showMessage:w duration:[SlideNotification LONG] withColor:Blue];