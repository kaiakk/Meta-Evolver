# Meta-Evolver

Meta-Evolver is a tool for a visual representation of the various dynamic environment models that correlate in multi-layered system. Meta-Evolver provides the environment for testing dynamic spatial adaptation, where the environment is composed of algorithms and parametric definitions. This research uses advanced AI methods (meta-learning) and cutting-edge technologies including immersive environments and virtual reality (VR) to offer innovative methods of architectural creation. The ability to continuously learn and adapt from limited experience in a dynamic environment is an important milestone on the path towards building interactive spaces in modern architecture. We developed the tool Meta-Evolver for testing spatial adaptation in dynamic environments and integrated the ability for interaction with a human user. 

Meta-Learning Multi-Agent System Diagram

![Screen Shot 2021-01-19 at 21 43 59](https://user-images.githubusercontent.com/34107769/107146452-a3b45b80-6948-11eb-9408-746e7b334a10.jpg)


![Screen Shot 2021-01-19 at 21 43 59](https://user-images.githubusercontent.com/34107769/107146731-3f929700-694a-11eb-991c-976f8aa3fbcb.png)

*This research was supported by CTU grant SGS19/117/OHK1/2T/15.


Technical Documentation

SW dependencies

Blender 2.8

dependencies
AddRoutes
OSC, MIDI

install 
http://www.jpfep.net/pages/addroutes/
https://github.com/JPfeP/AddRoutes

AddRoutes.zip
enable add-on in Blender preferences

NodeOSC
https://floatbug.com/how-to-make-interactive-audiovisual-effect-in-5-minutes-using-blender-and-maxmsp/

NodeOSC.zip
https://gumroad.com/avantcontra


Several core modules:
–Blender Eevee Engine: responsible for real-time rendering
–NodeOSC, AddRoutes Blender addons: responsible for OSC data sending and receiving
–PureData: responsible for sound processing, NN, BCI
–BugOSC: OSC controller


![Active_Render 0856 4 1-9704](https://user-images.githubusercontent.com/34107769/192794862-44f493f6-005f-41a6-b7d1-d4f797d80d02.png)


