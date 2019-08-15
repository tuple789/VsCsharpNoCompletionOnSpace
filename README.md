# VsCsharpNoCompletionOnSpace
This is an extension for Visual Commander, that will automatically toggle the completion mode of Intellisense in C# at startup.

Normally, The toggle the completion mode in Visual Studio for C# automatically get set to complete when you press space. You can of course 
press the toggle buttons to cancel that behaviour, however you have to do it EVERYTIME you launch a new instance of visual Studio, as there
is no way to save that behaviour.

This extension makes sure you will never have to press that button again.

## Install:

- First install the Visual Commander extension:
https://marketplace.visualstudio.com/items?itemName=SergeyVlasov.VisualCommander

- Download DisableSpaceCompletion.vcmd

- Install DisableSpaceCompletion.vcmd by going in Visual Studio:
  - Vcmd menu -> Import -> choose DisableSpaceCompletion.vcmd
  - Vcmd menu -> Extensions -> make sure Disable Space Completion is ticked (tick it on and off just to be sure)
  - RESTART VISUAL STUDIO (very important otherwise it might not work)
  
This is my first extension, but so far it works great, i hope you enjoy it.




