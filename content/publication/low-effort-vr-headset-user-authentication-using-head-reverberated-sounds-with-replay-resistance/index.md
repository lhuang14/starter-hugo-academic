---
title: Low-effort VR Headset User Authentication Using Head-reverberated Sounds with Replay Resistance
publication_types:
  - "1"
authors:
  - Ruxin Wang
  - Long Huang
  - Chen Wang
doi: "https://doi.org/10.1109/SP46215.2023.00127"
publication: 2023 IEEE Symposium on Security and Privacy (SP)
publication_short: ""
abstract: While Virtual Reality (VR) applications are becoming increasingly common,
  efficiently verifying a VR device user before granting personal access is still a challenge.
  Existing VR authentication methods require users to enter PINs or draw graphical passwords using controllers.
  Though the entry is in the virtual space, it can be observed by others in proximity and is subject to critical security issues.
  Furthermore, the in-air hand movements or handheld controller-based authentications require active user participation and are not time-efficient.
  This work proposes a low-effort VR device authentication system based on the unique skull-reverberated sounds,
  which can be acquired when the user wears the VR device. Specifically, when the user puts on the VR device or is wearing it to log into an online account,
  the proposed system actively emits an ultrasonic signal to initiate the authentication session.
  The signal returning to the VR device's microphone has been reverberated by the user's head,
  which is unique in size, skull shape and mass. We thus extract head biometric information from the received signal for unobtrusive VR device authentication.
  Though active acoustic sensing has been broadly used on mobile devices, no prior work has ever successfully applied such techniques to commodity VR devices.
  Because VR devices are designed to provide users with virtual reality immersion, the echo sounds used for active sensing are unwanted and severely suppressed.
  The raw audio before this process is also not accessible without kernel/hardware modifications.
  Thus, our work further solves the challenge of active acoustic sensing under echo cancellation to enable deploying our system on off-the-shelf VR devices.
  Additionally, we show that the echo cancellation mechanism is naturally good to prevent acoustic replay attacks.
  The proposed system is developed based on an autoencoder and a convolutional neural network for biometric data extraction and recognition.
  Experiments with a standalone and a mobile phone VR headset show that our system efficiently verifies a user and is also replay-resistant.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-05-22T22:33:10.650Z
---
