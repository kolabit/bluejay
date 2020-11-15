# Table of Contents

<!-- TOC -->

- [Description](#Descr)
- [Pre-requisites](#Pre-req)
- [Build Instructions](#build-inst)

<!-- /TOC -->


# Description
Bluejay is the open source project based on Rock Pie E single board computer to convert GigE Vision video stream  to RTSP stream.
Bluejay uses Aravis project capabilities to acquire the video data from GigE Vision camera, uses Rockchip Rk3328 on-chip H264 encoder to compress the acquired data and then supply the H264 stream to RTSP server, built on GStreamer framework.

# Pre-requisites
* You need *ROCK Pie E* Single Board Computer to run the Bluejay sofwtare. See the ROCK Pi E description here: https://rockpi.org/#rockpie
* Download and install *Ubuntu Server 18.04 Bionic* on Micro SD card. https://wiki.radxa.com/RockpiE/downloads

# Build Instructions
* Get *Rockchip RK3328 MPP* sources here https://github.com/rockchip-linux/mpp.git
* Get *Aravis* sources here https://github.com/AravisProject/aravis.git
* Get *GStreamer RTSP Server* sources here https://gitlab.freedesktop.org/gstreamer/gst-rtsp-server.git



