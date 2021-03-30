---
layout: default
title: Testing
permalink: /testing/
---

## Testing

This page contains the testing plan for my senior capstone project. [Click here](https://jacksexauer.github.io/SeniorCapstone/index) to return to the main page.

### Testing Plan Overview
A large part of the what my testing plan will include depends upon what Hilcorp wants for their final deliverable. I am having a conversation with my contact, Troy Johnson, today at 3pm where will discuss what he wants the final version of this project to look like. There are essentially two options: the results of the project could be delivered as a report that discusses my findings, or the project can be delivered as a runnable Python script that can be reused by Hilcorp. If Hilcorp wants a Python script, then I will likely deliver a Python script, instructions for running the Python script, and a report discussing the findings from my runs of the script. The only part of this project that would need to be user tested is the final Python script, which would be invoked from the command line.

The rest of the testing of the project is for internal code, and this testing falls into two categories. The first category is general unit testing, which ensures that the program is working in the way that it is supposed to. A large part of the code for this project involves reading in an Excel file and preparing its data for a run through a machine learning model. This part of testing also includes any visual outputs, like graphs or charts, related to the data or model outputs. The second category is machine learning models. The testing for machine models is more about optimizing parameters and features to create the best model possible and not about making sure the code runs without error.
