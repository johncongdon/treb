The /library/ directory's purpose is for you to put 3rd party PHP 
libraries that you are using.  Why is this different from /classes/? 
Mostly semantic, in that /classes/ is for your own code extensions 
that you create.   Whereas /library/ should hold 3rd party ones you 
are using.  This will help you to keep them separate in your mind & 
the code.  Also, since you can't rely on autoloading working with 
all the libraries, autoloading isn't enabled in the library folder.  
Include any of these libraries on the fly as needed.
