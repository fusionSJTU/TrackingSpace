sOcean: A Smart Multiple Model Software Project!
===================================

**sOcean** is a Python/Cpp software project for extended object kinematic/semantic state estimation from the Smart Sensor Fusion Research Laboratory at the University of Shanghai Jiao Tong University (SSF at SJTU). The estimation framework forms a **World Model** consisting of two major parts: i) **Dynamic World**: extended object multiple model tracking; ii) **Static World**: semantic object estimation for mapping and map learning.

In the Dynamic World, the focus is put on developing an extended object multiple model tracking framekwork for particularly autonomous systems. The framework deals with coordinate transform, input/output interface, measurement conversion, mesurement model, measurement noise design, dynamic model, process noise design, pre-processing, post-processing, track initialization/management, data segementation, data clustering, data association, KF-alike algorithms, multiple model approaches, intermediate representation, hybrid fusion and more.

In the Static World, the efforts are put on building a unified fusion map based on tracking static semantic objects and the fusion map can be learnt as time goes by with slow variations. The fusion map platform can accommondate various sensor data of diverse modalities with a voxel system. 

To verify and validate the World Model, a real-time generic verification and validation metrics framework for autonomous systems is investigated, a cloud data center with formats of HDF5, MAT and Rosbag is established and a fusion data set collaborated with IEEE/ISIF using high quality annotation is collected using the SSF Data Vehicle. 

The Tutorial gives demonstrations on how the components behave in certain delicated ways.

The Example Arena presents students works on sOcean for simulation and real world scenario studies  

Some Use Cases are designed to imitate real world situations for aerospace/automotive applications.

.. note::

   sOcean from SSF at SJTU is now under active development.

Contents
--------

.. toctree::

   World Model
   Dynamic World
   Static World
   Metrics System
   Data Center
   Tutorial
   Example Arena
   Use Cases for Autonomy
   Contributors
   Copyright
