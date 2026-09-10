# Final Project Sketch — Maimai Motion Capture

## Topic / Concept

I want to make a motion capture project based on **maimai**.

The basic idea is to record someone playing maimai and transfer the movement onto a 3D avatar. I am interested in how maimai movement looks when it is separated from the arcade machine and treated more like choreography or performance.

I also want to see how much of the movement can still be recognized as "maimai" without showing the actual game.

## Why Maimai

Maimai is interesting to me because the movement is very visible and expressive.

Even though players are technically just following the same chart, different players move very differently. Some movements are optimized for efficiency, while others are more exaggerated or stylized.

I am also already familiar with the maimai community and watch a lot of gameplay/performance videos, so this is something I naturally want to explore.

Here are some gameplay videos:
- [Other players](https://www.bilibili.com/video/BV1cbjm62EWR/?share_source=copy_web&vd_source=92b1b3cede043ee6f18a980241287906)
- [My own](https://www.bilibili.com/video/BV1rvgg6xE5j/?share_source=copy_web&vd_source=92b1b3cede043ee6f18a980241287906)

## Context / Research

Maimai comes from Japanese arcade rhythm game culture. Because the player stands in front of a large circular machine and uses their whole upper body, playing it can look almost like a performance.

For research, I can:

- observe maimai players in arcades
- compare videos of different players playing the same chart
- talk to players about how they develop their movement/style
- record my own gameplay as an initial test

## Motion Capture

Right now I am considering **optical tracking**, probably with HTC Vive trackers.

I originally thought about using an inertial motion capture suit, but drift may be a problem, especially because maimai movement depends on relatively precise hand positions.

Vive trackers seem more suitable because they can give more stable positional tracking.

I may mainly track:

- hands / arms
- upper body
- waist

I probably do not need detailed finger tracking for the first version.

## Challenges

The biggest problem I expect is **retargeting**.

If the avatar has very different body proportions from the real player, the hands may no longer reach the correct positions. For example, a character with short arms may not match the original maimai movement well.

Other possible problems are:

- tracker occlusion
- calibration
- limited tracking space
- reconstructing the approximate position of the maimai machine
- keeping the motion natural after retargeting

For the first version, I will probably use a relatively human-proportioned avatar.

## Permissions / Resources

If I record another player, I will ask for permission before using their motion or video.

Possible resources:

- HTC Vive trackers
- base stations
- school mocap equipment
- Blender / Unity / Unreal
- a rigged 3D avatar

## Scope / Feasibility

I think this is feasible if I keep the first version small.

My current plan is:

1. Pick one short maimai chart or section.
2. Record one performance.
3. Capture the main body movement.
4. Retarget it onto a 3D avatar.
5. Recreate the approximate position of the maimai machine.
6. Test how the movement looks without the original gameplay footage.

If I have more time, I can compare different players or different avatars.