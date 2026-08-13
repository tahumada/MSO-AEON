# DECam AEON Target Submission

This folder contains tutorials and examples specifically focused on submitting observation requests to **DECam (Dark Energy Camera)** via the AEON API.

## Prerequisites

To run these tutorials, you will need your **LCO API Token**. 

If you haven't already, please refer to the [main repository README](../README.md) for instructions on how to locate your token and securely set it up in your local environment.

## Tutorials in this Folder

This directory contains the following guides:

1. **Submit One Target** 
   A walkthrough on how to format the JSON payload and submit a single, programmatic observation request to DECam.
   
2. **Submit Targets from a List** 
   A guide on how to automate bulk submissions. This tutorial includes a provided example list of targets to demonstrate how to iterate through a file and submit multiple requests to the queue at once.

3. **Submit Targets from a SISPI-compatible JSON File**
   A specialized tutorial showing how to parse a DECam SISPI-compatible JSON file (example provided) and submit those observations through the AEON API.

## To-Do

- [ ] Add a tutorial to convert JSON files to AEON requests for individual targets.
- [ ] Add a tutorial to convert JSON files to AEON requests for targets with offsets.

## Feedback & Contact

Feedback is highly welcomed! We want to make this process as smooth as possible for observers. 

If you have any questions, encounter errors, or have suggestions for improvements, please reach out to **Tomás Ahumada** at:
📧 `tomas.ahumada at noirlab dot edu`
