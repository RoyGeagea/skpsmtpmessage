# Introduction #

SKPSMTPMessage is a quick and dirty class which implements a basic SMTP client for the iPhone. If you just want to post a plain text or HTML message on the iPhone, use `-[UIApplication openURL:]` (these are not the droids you're looking for, move along, move along). However, if you're trying to attach a file to an email, or do other crazy stuff, you'll want to use this class.

# Integration with your App #

Add the NSStream+SKPSMTPExtensions.[m|h] and SKPSMTPMessage.[m|h] classes to your project. Refer to SMTPSenderAppDelegate.m for a quick example of how to use the class.

I'll document this code using Doxygen soon.

# Issues with the Code #

Please use the Issue Tracker, don't post issues into the comments here, as they will be deleted.

# How to Fix Your Problem #

[Read This](http://blog.skorpiostech.com/2009/02/11/skpsmptmessage-economics-of-open-source/)