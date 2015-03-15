# Abstract #
The intent of this project is to provide keyboard layouts for Mac keyboards that are used with Microsoft Windows (either natively or in a virtual machine)

<font color='red'>FEEL FREE TO SUBMIT YOUR LOCALIZED MAC KEYBOARD LAYOUT</font>

# Howto #
## Building the keyboard layout ##
  * Download and install [The Microsoft Keyboard Layout Creator](http://msdn.microsoft.com/en-us/goglobal/bb964665.aspx) on your Microsoft Windows (virtual) machine
  * Download the KLC file of your choice from the [Subversion repository](https://code.google.com/p/mac-keyboard-layouts-for-windows/source/browse/#svn/trunk)
  * Open the KLC file using the the Microsoft Keyboard Layout Creator (File --> Load Source file...)
  * Build the Setup files (Project --> Build DLL and Setup package)

![http://mac-keyboard-layouts-for-windows.googlecode.com/svn/wiki/images/MicrosoftKeyboardLayoutCreator.png](http://mac-keyboard-layouts-for-windows.googlecode.com/svn/wiki/images/MicrosoftKeyboardLayoutCreator.png)

## Installation ##
  * Depending on your System Architecture, use one of the Setup packages you've just created

  * 32bit System: filename\_i386.wmi
  * 64bit System: filename\_amd64.wmi
  * Itanium: filename\_ia64.wmi

## Known Issues ##
  * FN-Key cannot be assigned
