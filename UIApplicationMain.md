###UIApplicationMain
Apply this attribute to a class to indicate that it is the application delegate. Using this attribute is equivalent to calling the **UIApplicationMain** function and passing this class’s name as the name of the delegate class.

If you do not use the attribute, supply a **main.swift** file with a main function that calls the **UIApplicationMain** function. For example, if your app uses a custom subclass of **UIApplication** as this principle class, call the **UIApplicationMain** function instead of using this attribute.