# VR-fundamentals-concept-notebook
This repository contains documentation of VR fundamentals to help someone how the VR world operates, what are the related terms and concepts and how one can start developing VR apps.

### Principles of VR:

#### Optics:

Each lens helps focus on the screen extremely closer to our face because without the lenses we can’t see properly at such close proximity.

The lens is chosen such a way that it makes the best tradeoff between

Field of view, focal length, comfort, optical distortion and cost

Why VR headset have lenses? So as to focus on the display close to our eyes

#### Display:

High resolution is required and according to a study a resolution 16000x16000 pixel is required for a crisp image but for now we only have 1080.

Low persistence is needed so as to avoid motion blur and helps deliver sharp, consistent image

OLED displays that support low persistence are generally used

#### Tracking:

It allows computer to know where we are in space

All VR rely on chips of IMU(Inertial measurement unit). IMU allows high speed rotational tracking

But to detect the location of obect in space VR relies on cameras, lasers, magnetic fields or precise clock.

Positional tracking is crucial because that is how we control our VR world

### VR challenges:

Simulator sickness

Making people uncomfortable is related to when the body’s internal sense of motion mismatches what the brain understands from visuals.

### History of VR:

When image from two exact images were shown to each eye at the same time they fuse to form a view of single solid 3D object.(Stereoscope)

### VR paradigms:

Difference between a mobile VR and a desktop VR is 3-DOF and 6-DOF 

DOF(Degrees of Freedom)

3-DOF means ROTATION of the head is tracked in X, Y, and Z axis

6-DOF means ROTATION and MOVEMENT of the head is tracked in X, Y, and Z axis

#### How IMUs enable 3-DOF tracking:

The IMU is a powerful electronic chip that combines the data from an onboard accelerometer, magnetometer and gyroscope

Basically it uses the gravity,  earth’s magnetic field, and complex math to infer which way it is pointed and the direction it’s facing.

Sometimes the IMU is in the headset and sometimes the phone’s IMU is used but it is IMU only.

#### How to enable 6-DOF tracking:

There are many different ways to do 6-DOF tracking but let’s consider the major 6-DOF tracking here

Oculus Rift: It uses Constellation. Constellation is a collection of many IR LEDs placed on the VR headset that blinks very fast and are captured by a camera then using these frame motions and IMU it calculates the position. It is cheap and highly accurate.

HTC Vive: It’s system is called Lighthouse. It uses IR lasers. A laser tracking system takes readings by sweeping the area around you and combining the readings with IMU to track.

All of which comes under Optics and that’s why although there are thermal, acoustics, magnetic options major headsets use Optics.

Mobile:							Desktop:
IMU tracking						Optical and IMU tracking
Untethered 						Tethered
Less powerful						More powerful, hand controllers

#### VR development platforms:

There are two ways to achieve VR development-

Write code 

Use graphic based editor environment

Combination of both

Native development tools like OpenGl, DirectX are used to develop games with more flexibility but more development time.

Unreal, Cry, Lumberyard, Unity are some of the popular game engines that reduces development times for game development

WebVR is also another good choice for VR development

#### To get started:

Open the Unity app and import an existing project or Create a new one and start working with Unity by creating scenes.
