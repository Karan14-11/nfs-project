# NFS (Network File System) Project

## Overview

This repository contains the source code for a Network File System (NFS) implemented in C. The project aims to provide a distributed file system that allows seamless file sharing and access across a network.

## Components

### Naming Server

The Naming Server is responsible for maintaining a directory of file paths and their corresponding locations on the network. It starts and waits for incoming storage servers to connect.

## Getting Started

### Prerequisites

- Ensure you have [C compiler](https://gcc.gnu.org/install/index.html) installed.

### Building

1. Clone the repository:

   ```bash
   git clone https://github.com/Karan14-11/nfs-project.git
   cd nfs-project

2. Starting the naming server 
    ```bash 
    cd storage_server
    make clean;make
    ./NMS
