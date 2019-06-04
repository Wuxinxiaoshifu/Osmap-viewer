# Osmap viewer

This tool is a map points cloud viewer for maps saved with Osmap.

ORB-SLAM2 is an outstanding real-time monocular visual SLAM system.  The code was made as a proof of concept for the homonimous paper.  It generates maps from video.  Sadly, it lacks of means for serializing maps.

Osmap is an "add-on", an upgrade people can append to ORB-SLAM2 to save and load maps.

Osmap viewer is a viewer tool for visualizing map point clouds saved in a file with osmap.

Osmap viewer uses Osmap to deserialize map files, and OpenCV Viz to visualize them as point clouds.


## Beta

Right now Osmap viewer is in its initial stage.  It works on my system, I only tested it with Ubuntu 18.04 and OpenCV 4.  It should work in other versions of Linux and OpenCV.  If you try it, please tell me if you succeded building and running it.

It only shows MapPoints.

It includes Osmap code with a minor change I'll be able to eliminate with an improved version of Osmap. 


## Usage

"Osmap viewer" mapFile.yaml


## Future

It's not a heavy work, but I don't have time to do it.  I plan to append KeyFrames, spanning tree and check if I have to correct the initial view to match the one in ORB-SLAM2: Z points ahead, Y points downwards.
 

## Enjoy