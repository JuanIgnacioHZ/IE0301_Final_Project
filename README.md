# IE0301_Final_Project
Final project for embedded system laboratory (Fall 2023), it implements a library for monocular depth estimation with AI for an Nvidia Jetson Nano, also allows network streaming of video in order to see the results in other computer.

The code was modified from original examples to fit the project requirements.

File description:

    - depthnet.cpp: AI software used for estimating monocular depth distance.
    - gstUtility.cpp: Modified version of GStreamer used for taking advantage of hardware acceleration.
    - gst-watch.c: Script for watching the network video streaming.
    - imx219.c: Serial camera driver.
    - imx219_mode_tbls.h: Camera mode tables.
    - tegra210-camera-rbpcv2-imx219.dtsi: Jetson Nano device tree.

Developed in group with other students of the school:

    - Allan Alvarado
    - Victor Loux
    - Juan Ignacio Hernández
