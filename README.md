# CATS22Tweaker
This is a magisk module intended to:
- Decrease power usage when using the device.
- Prioritize foreground tasks so any potential performance hit only effects background tasks.
- (Optional) Enable the secondary display, which is by default disabled on aftermarket ROMs.
  
On the CAT S22 Flip. Other devices may or may not work. 
  
# Current functionality
An app is used to manage the secondary display. You can view the source here: https://github.com/B-CyberFunker/CATS22Present 
N/A

# Install
Download the zip and use Magisk to install. Reboot. 
If you're on the stock ROM or otherwise already have the secondary display enabled, use the "NoScreen" version. 

# To do
- Create a presentation screen.
- Set the GSI.Image_Running prop at or before boot.
- Make the presentation screen appear on screen lock and timeout.
- Test the current script to see how much power is saved (if any). 
- Make the presentation screen customizable.

# Build
Not required as the module is just a bunch of scripts at the moment. 
If you want to try the latest and greatest, simply download the zip of this repo and install it.
