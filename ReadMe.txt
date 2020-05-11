//DISCLAIMER START

--**///****/////IMPORTANT - IF NOTHING ELSE READ THIS TIL DISCLAIMER ENḌ\\\\\****\\\**-- 

**WARNING -- MAKE SURE LISTENING LEVEL ARE LOW AND SAFE, ESPECIALLY WHEN DEALLING WITH HIGH TRACK COUNT, 
START WITH YOUR VOLUME ON 0 AND BRING IT UP SLOWLY UNTI YOU CAN HEAR ENOUGH TO HEAR ISSUES**
**IF TESTING TO FAILURE, MAKE SURE ALL FILES ARE SAVED AND YOUR COMPUTER IS BACKED UP.
WHILE THIS SHOULD NOT DAMAGE YOUR COMPUTER OR FILES, IT MAY BE A POSSIBILITY**
**THE AUTHOR IS NOT RESPONIBLE FOR ANY HEARING DAMAGE OR DATA LOSS/CORRUPTION AS A RESULT OF THIS PROJECT, 
SO TAKE USE AT OWN RISK**

DISCLAIMER END \\

Project Created with:

Software: Reaper
Verison: v6.10
Created: 11th May 2020
Last Updated: -

// Purpose:

To Stress test system CPU by testing how many tracks it can run with each track running the following plugins:
- RealEQ (VST)
- ReaSynth (VSTi)
- Convolution Amp/Cab Modeler (JS)
- ReaComp (VST)
- ReaDelay (VST)
- ReaVerb (VST)

\\

// Notes: 

While this won't reflect real world usage, as this uses stock plugins exclusively. 
This makes this a very Cross platform friendly test stress test. 
Works on anything that Reaper works on, which is most operating systems, including OSx, Windows XP-10, 
and linux Distros such as Ubuntu and Rasbian. I await the day I can make p h a t Beats on my toaster. 

//Method:

1: Load up one of the projects 
 - pick the one that you think your computer can handle. You can always add more tracks later.

2: Ensure the project is on loop and press play. 

3: Enable the Track FX on the TCP one by one. 
 - be aware of volume at all times.

4: Duplicate tracks if you exceed the project.

5: Note as to when you:
 Parameter A) Begin to hear audio artifacts in playback
 Parameter B) Reaper stops working or stops playback
 - For Example, when if at 33 tracks it sounds fine but 34 it starts to crackle, 
your system can handle 33 tracks with the "A" parameter. 
Same Method with parameter B, but with reaper/ System Failure. 

Method Finished \\

// Permissions and Credits

While I presume this part will be ignored anyway, I gives full express permission to use, edit, reproduce and redistribute
in anyway way the user wants. Crediting this Github and myself (James Horan) would be appreciated if used. 

Feel free to drop me a email with your results & computer specs at j.horan1512@gmail.com . I am not affiliated with Cockos.
