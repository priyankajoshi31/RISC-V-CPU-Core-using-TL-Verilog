# RISC-V_MYTH_Workshop

This repository contains all the information regarding the 5-day RISC-V based CPU Core Design MYTH (Microprocessor for You in Thirty Hours) Workshop, offered by for VLSI System Design (VSD) and Redwood EDA. The RISC-V CPU Core has been designed using Transaction Level Verilog(TL-Verilog) in addition with the Makerchip Platform. Find below the accompanying details.

Check the folders for assignments for particular days.


## Getting Started with the Makerchip Platform

1. Click on the below link to jump to the Makerchip platform : https://makerchip.com/ . Click on “Launch Makerchip IDE”.

![](Documentation/Makerchip_IDE/Makerchip.JPG)
    
2. A new new window opens. This comes with a shell to write TL Verilog Code.

![](Documentation/Makerchip_IDE/Makerchip_IDE.JPG)
    
3. In order to load a sample example code, click on Tutorials -> Examples. Under table of contents click on Pythagorean Theorem Pipeline, and then click on the blue color tab named “Pythagorean Theorem” to load the project.

![](Documentation/Makerchip_IDE/Tutorials.JPG)

![](Documentation/Makerchip_IDE/Examples.JPG)
    
4. List of various tabs available for the user:
     - The **Editor** tab shows the source code for the program.
     - The **NAV-TLV** tab shows the expanded form of the complete code that is used for debugging.
     - The **Log** tab shows the logs and the list of errors in the project, if any.
     - The **Diagram** tab shows the output schematic diagram generated for the source code. 
     - The **Waveform** tab shows us the output waveform generated out of the program.
          
5. In order to zoom in/out the diagram or the waveform , hoover the mouse over them and scroll up/down.
    
6. If you click on any signal on the waveform, it will get highlighted on the diagram and the NAVTLV tab as well , which we can look for debugging.
    
7. On the top right corner , there is Window like pane available which we can select to split the tabs on the screen, horizontally or vertically.

![](Documentation/Makerchip_IDE/Split_screen.JPG)
    
8. While present on the Editor tab, on the top right corner, Click on “E”. Then click on “Compile/Sim” to compile the program. (You can use “Ctrl+Enter” as a shortcut for the same).

    
9. There is also an option to check for comparision between the source code required for a design written in TL-Verilog and in System Verilog. Click on “Show Verilog” to see the results.
    
10. In order to save the project click on “Save as New Project” present on the top right corner. The saving of a project in Makerchip platform is kind of primitive, it doesn’t save the entire project file in any database. It just generates a kind of url , which we can bookmark/saved it outside, in order to  return back to it later.
    
11. Always make sure to clone your project before statring something new, so as to avoid the previous project file getting overridden. For this, Click on "Project -> Clone project(New URL)".




## Final CPU Core Implemetation Diagram
![](Day3_5/Final_Output_for_RISC-V_Implemented_CPU_Core.JPG)
