For help files, please click http://www.cnblogs.com/chenxu520/p/4655738.html?utm_source=tuicool&utm_medium=referral

UIAutomation is a new set of UI automation testing technology launched by Microsoft from Windows Vista, referred to as UIA.
In the latest Windows SDK, UIA and MSAA and other components that support UI automation technology are released together, called the Windows Automation API.
UIA defines new interfaces and patterns for UI automation. They are TreeWalker/FindAll that support traversal and conditional queries on UI elements.
Defines the UIA Property for reading and writing UI element properties, including Name, ID, Type, ClassName, Location, Visibility, and so on.
A UIA pattern that defines the behavior of UI elements, such as Select, Expand, Resize, Check, Value, and so on.
Also introduced is the UIA Event interface, which allows the test program to be notified after certain events occur, such as new window open events.

The introduction in MSDN is very detailed, where is the MSDN documentation for UI Automation. Here: http://msdn.microsoft.com/en-us/library/ms753107.aspx

We only look at the key section: Using UI Automation for Automated Testing The above documentation can be found in a variety of complex situations.

But for a newcomer, the big and complete documentation makes it impossible to start. To this end, I have packaged various operations based on UI Automation based on the usual situation.
At present, this version 1.0.0.0 is still relatively rough, and you may encounter bugs and other situations in use. Please point out and improve together, thank you!
