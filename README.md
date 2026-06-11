# USB 2.0 Hub

A custom-designed 4-port USB 2.0 hub built around the GL850G USB Hub Controller.

## Overview

This USB hub features:

- 1 × USB C upstream port
- 2 × USB Type-A downstream ports
- 2 × USB Type-C downstream ports
- USB 2.0 High-Speed support (up to 480 Mbps)
- Plug-and-play operation

## Specifications

| Feature | Details |
|----------|----------|
| Hub Controller | GL850G |
| USB Standard | USB 2.0 |
| Maximum Speed | 480 Mbps |
| Upstream Ports | 1 |
| USB-A Ports | 2 |
| USB-C Ports | 2 |

## Schematic

<img width="1620" height="1152" alt="image" src="https://github.com/user-attachments/assets/ebe2cdf4-4d37-45ba-9b72-1c6a85950702" />


*Complete circuit schematic of the USB hub.*

## PCB Design

<img width="1512" height="1115" alt="image" src="https://github.com/user-attachments/assets/2fb9962c-b36c-481a-a63e-81e9e92ad909" />


## 3D Model

<img width="1356" height="981" alt="image" src="https://github.com/user-attachments/assets/30a6b971-10fe-4a01-993d-834e609cc570" />

<img width="1269" height="967" alt="image" src="https://github.com/user-attachments/assets/59c6e8c6-385b-4b89-b1c2-a93cb3e6b472" />


*3D visualization of the assembled PCB.*

## Hardware Architecture

```text
          Host PC
              │
              ▼
       USB Upstream Port
              │
              ▼
          GL850G
      USB Hub Controller
        ┌────┴────┐
        │         │
   USB-A Ports  USB-C Ports
      (2x)         (2x)
