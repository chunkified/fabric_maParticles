# fabric_maParticles
A "poor man's" approach to an extensible particle system for FabricEngine written in KL
License: Public Domain in the 1980s sense. Do time travel if you need to learn about it. License may change for future versions.

Related thread on the FabricEngine's community forum: http://forums.fabricengine.com/discussion/comment/1429

Purpose: 
This particle system uses FabricEngine's Points entity to store positions and attributes of "particles". It does not include mesh genereation of any kind, but FabricEngine's debug shapes or inline drawing system can be used to visualize the particles. 
The system is meant as a common base for community work on a flexible, ideally FAST and easy to understand everlasting work in progress. In a perfect world every version uploaded to the master branch will be accompanied by a test "canvas" (a scene file runable in FabricEngine's standalone development environment) to demonstrate most, if not all features.

Vision:
This project is to create a balance between performance (PEX/multithreaded CPU and GPU use, if possible) and ease of use. When in doubt, ease of use should be favored over performance. Ideally users should be able to just "throw in a few nodes and get some AHA-effect". 

Personal goals:
I am using this project along my other experiments to learn KL, understand and master the power of Fabric and, last but not least, become a valued member of the Fabric community. 
Sigh. What a man doesn't do for some love!
