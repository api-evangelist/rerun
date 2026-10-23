---
title: "Spotlight: 3D reconstruction is a data layer problem"
url: "https://rerun.io/blog/arkitscenes-data-layer"
date: "2026-07-27"
author: "Pablo Vela"
feed_url: "https://rerun.io/blog/rss.xml"
---
3D reconstruction runs on multimodal, multi-rate data, and handling that data is most of the work. This is a worked example of what Rerun's data layer removes from a real project: all 5,015 ARKitScenes scans converted into recordings that the viewer, the dataframe API, and the PyTorch dataloader read directly, no export step in between.
