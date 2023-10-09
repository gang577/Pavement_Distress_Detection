# Pavement_Distress_Detection

This repository contains Python bindings and sample applications for the DeepStream SDK.

SDK version supported: 5.1



This release only supports Ubuntu 18.04 for DeepStreamSDK 5.1 with Python 3.6.9 

Download the latest release package complete with bindings and sample applications from the release section.

Please report any issues or bugs on the DeepStream SDK Forums. This enables the DeepStream community to find help at a central location.

- [DeepStream Python Apps](#deepstream-python-apps)
  - [Python Bindings](#python-bindings)
  - [Sample Applications](#sample-applications)

Python Bindings
DeepStream pipelines can be constructed using Gst Python, the GStreamer framework's Python bindings. For accessing DeepStream MetaData, Python bindings are provided as part of this repository. 

<a name="metadata_bindings"></a>
## Python Bindings
DeepStream pipelines can be constructed using Gst Python, the GStreamer framework's Python bindings. For accessing DeepStream MetaData, 
Python [bindings](bindings) are provided as part of this repository. This module is generated using [Pybind11](https://github.com/pybind/pybind11).

<p align="center">
<img src=".python-app-pipeline.png" alt="bindings pipeline" height="600px"/>
</p>
