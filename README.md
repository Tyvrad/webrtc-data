# WebRTC Data
This repository contains a dataset of dumps from the Google Chrome webrtc-internals.
Measurements were conducted with 2 and 3 clients, represented by the corresponding directory.

For each configuration (2/3 clients), two sets of data are available.
- bw_low:	Measurements with bandwidths ranging from 0.25 Mbit/s to 2 Mbit/s
- bw_high:	Measurements with bandwidths ranging from 0.25 Mbit/s to 50.0 Mbit/s

Each of the directories contains a series of measurements identified by a timestamp.
One possibility to parse the data is using the parser provided by https://github.com/Tyvrad/simple-webrtc