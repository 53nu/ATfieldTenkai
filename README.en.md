# ATfieldTenkai — AT-Field

[한국어](README.md) · [English](README.en.md)

**An interactive visual in which an open-palm gesture deploys an AT Field and a graphic interface.**

[Project story on Notion](https://53nu.notion.site/AT-Field-MediaPipe-TouchDesigner-415b42633c8c8174ae5efd57dba98865) · [Project video](https://www.instagram.com/1015_53nu/reel/DVXcv0QjyT-/) · [Project downloads](https://github.com/53nu/ATfieldTenkai/releases)

## Overview

Inspired by the AT Field in Neon Genesis Evangelion, this project connects MediaPipe with TouchDesigner. MediaPipe Gesture Recognition detects an open palm and triggers the AT Field together with typography, a spectrum visualization, and GUI elements.

## Implementation and visual design

- **Input and response:** Camera-based hand gestures act as triggers for the visual effects.
- **GUI elements:** Noise TOP, Feedback TOP, and the Graph component from the Palette contribute to the interface.
- **Typography:** Mincho-style lettering and Helvetica interpret graphic elements from the original work.
- **Composition:** The camera feed, AT Field, and graphic panels share a single composition.

The Notion page brings together the production description and video preview.

## Technology

TouchDesigner · MediaPipe Gesture Recognition · Noise TOP · Feedback TOP · Graph

## Download and run

This repository contains the project introduction. Distribution files are managed in [Releases](https://github.com/53nu/ATfieldTenkai/releases).

1. Download `ATfieldtenkai.zip` from the [release page](https://github.com/53nu/ATfieldTenkai/releases/tag/v1.0) and extract it.
2. Open the included TouchDesigner project.
3. Check the camera input and MediaPipe connection, then open your palm to observe the response.

Running the project requires TouchDesigner and a camera input environment. Check project-specific setup and external file paths in the distribution.

## Context and contact

This is an unofficial fan-made project inspired by Evangelion, created for artistic experimentation. For project inquiries, contact [@1015_53nu on Instagram](https://www.instagram.com/1015_53nu/) by DM.
