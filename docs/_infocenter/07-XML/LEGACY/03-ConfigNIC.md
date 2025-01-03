---
layout: default
title: Configure NIC for Virtual Machine
parent: DarwinLegacyKVM.xml
grand_parent: XML Import/Usage
nav_order: 4
---

# Configure Virtual Machine NIC
#### <span style="color: #ffab52;">This is required to download macOS via recoveryOS</span>, as well as will be the general ethernet connection in the Virtual Machine.

## Using the Default Network

Select the "Add Hardware" button and choose the Network category on the left-hand side. You can now see your network source settings

For the default network you simply have to set the model depending on your target Mac OS X Installation.

### For Mac OS X 10.11 (El Capitan)+ utilize the ``vmxnet3`` ethernet adapter model.

<a href="https://raw.githubusercontent.com/royalgraphx/DarwinKVM/main/docs/assets/VManLegacyAddNICvmxnet3.png"><img src="../../../../assets/VManLegacyAddNICvmxnet3.png" alt=""></a>

### For older OS X Targets, utilize the Intel e1000 ethernet adapter model.

<a href="https://raw.githubusercontent.com/royalgraphx/DarwinKVM/main/docs/assets/VManLegacyAddNICe1000.png"><img src="../../../../assets/VManLegacyAddNICe1000.png" alt=""></a>

## You can now continue to the next <a href="../04-Review">page</a>.
