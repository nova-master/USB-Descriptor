# USB-Descriptor
# USB Device Information Retrieval

This UEFI application demonstrates how to retrieve information from a USB device, specifically focusing on obtaining the USB device descriptor and serial number.

## Introduction

The application locates USB devices using the UEFI USB I/O Protocol and then filters the devices based on certain characteristics, such as vendor ID and product ID. It aims to find a USB pen drive with a specific vendor ID (0x0781) and product ID (0x558a).

## Usage

To use this application:

1. Build the UEFI application with appropriate tools.
2. Load the compiled UEFI application onto a UEFI-compatible system.
3. Run the application, and it will attempt to locate the specified USB pen drive.
