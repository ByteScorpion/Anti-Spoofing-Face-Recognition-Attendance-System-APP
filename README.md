# Anti-Spoofing Face Recognition Attendance System APP
![]["Images/PYR.png"]

## Overview

The **Anti-Spoofing Face Recognition Attendance System APP** is a hybrid application combining Python and R to provide a robust solution for attendance tracking and data analysis. The system uses advanced face recognition and anti-spoofing techniques to ensure the authenticity of the attendees and provides a user-friendly dashboard for analyzing attendance data.

## Features

- **Face Recognition**: Utilizes InceptionResnetV1 models, pretrained on VGGFace2 and CASIA-Webface datasets. The system also supports other models such as Facenet512 and Human-beings.
- **Anti-Spoofing**: Implements MiniFASNet variants including MiniFASNetV1, MiniFASNetV2, MiniFASNetV1SE, and MiniFASNetV2SE, supported by Silent-Face-Anti-Spoofing developed by Minivision.
- **User Interface**: Built using PyQt for a seamless and interactive experience.
- **Data Analysis Dashboard**: Created with R's `shinydashboard` package to provide insightful analysis of attendance data.
