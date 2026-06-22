Welcome to the repository for SubArc: An Inexpensive, High Resolution, Open Source, Absolute Magnetic Rotary Encoder!

UPDATE: All work on this project has been stopped to pursue other projects.

In this repository, there are the files for the 3D models of the most recent SubArc PCB and Calibration Stand version. There are the SubArc python executable programs and the microcontroller (Arduino standard) code. Additionally, a specification sheet, a mounting tutorial, and other in-depth documentation are also listed.

At this time, SubArc is no longer under development. That being said, the current SubArc version does output 20 bit resolution at under 150 arc seconds of average accuracy, and can be vigilantly used for low-speed applications due to an extremely limited sampling rate. More importantly, the research done here can hopefully lay the groundwork for future encoders of the same principle.

The following improvements were to be made to release an initial beta-version of SubArc:

1) Fix occasional accuracy spike bugs
2) Increase position calibration file search algorithm efficiency
3) Increase sampling rate to 5000 Hz with updated hall sensor array
4) Create through-bore version for easy mounting on machinery

However, due to the complex nature of fixing these issues and my desire to create other new project ideas, I've stopped working on this project.

If you would still like to build your own alpha version SubArc and need assistance, or if you are looking to improve on this research, feel free to contact me at: franklucci636@gmail.com

Current SubArc specification details:

You can customize the SubArc ring and readhead in your PCB software to change the resolution and accuracy

Standard resolution is 20-bits, with an 8mm bore, 55mm diameter, 100 magnets, and 6 hall sensors
