# Emi's Render Time Predictor
This is a tool that helps you get a rough estimate of the render time for your animation based on how long the provided frame gap took for it to render. You should expect some inaccuracies due to different kinds of scenes taking a different time to render, but it helps with getting an idea of the time it will take.

## How to Install & Use
1. Download the 'EmiTools.py' from this Repository
2. Open Blender, then in the settings go to the Add-on tab and select 'Download from Disk'
   2.1 Select 'EmiTools.py'
3. on the right side panels, you should see a tab called "EmiTools". Select it.
4. Set the 'Start' and 'End' frames to whatever gap you want to know the render time for
5. Set the 'Frame Gap' to the amount of frames you want to sample for the render time
6. Press the 'Start Timer' button and wait for it to finish.
   
Once it's done timing the gap, you will get a pop-up at the bottom of your Blender application telling you the estimated time. You can also open the Blender console to see it.
