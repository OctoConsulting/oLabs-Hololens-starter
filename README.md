# oLabs-Hololens-starter
 This repo provides a springboard to jump into new app development for the Hololens 2.
 
 Everything that you need to start a new H2 app is included: proper UWP settings, essential logos, basic UIs, etc.
 
 
 ## Required Software Versions
 
 * Unity 2020.3.10f1
 * [MRTK Feature Tool](https://docs.microsoft.com/en-us/windows/mixed-reality/develop/unity/welcome-to-mr-feature-tool)


## Procedure 
* Pull down the repo and unzip into an approptiate directory
* Add this directory via Unity Hub and open the project
* Unity will complain about a bunch of stuff missing and offer the opportunity to go into Safe Mode, or Ignore the errors: Ignore the Errors and let Unity open
* Once Unity is open, launch the MRTK Feature Tool so you can install what was missing
* Insert picture here
* When everything has been imported, UNnity will open the MRK configurator window -> Select: Unity OpenXR plugin (recommended)
* Select: Show XR Plugin Management Settings, this will open the settings window and switch to the Windows tab of XR Plugin Management and you should see a yellow warning triangle. Select this triangle and then hit Fix All in the window that opens. Close that window when its done and the triangle should go away.
* With Setting still open, switch to the Player settings, and adjust Product Name, Package name, etc as required for your new project.
* If the MRTK Configurator window doesnt update, you can hit Skip this step to proceed.  Basically, just scoot through the rest of the windows ( all important settings have already been made )
* Any and all errors should be cleared. Go ahead and open the `HololensApp` scene file and get started developing.


