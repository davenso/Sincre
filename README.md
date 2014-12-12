============
Sincre v1.0
============

---------------------
Projects Organization
----------------------
FrameProcessor Core
1.   FrameProcessor Static Library
2.   FrameProcessor Dynamic Library
Sincre Libraries
3.   Sincre Layer-A
4.   Sincre Layer-B
5.   Sincre Layer-AB WCF Service Library
Sincre Web Services
6.   Sincre Layer-AB Service
Sincre Endpoints
7.   Sincre WebFront

-------------------
Project Details
-------------------
FrameProcessor core:
 - Core image/video processing engine
 - Input: frames
 - Output: metadata datasets
- Algorithm: Scale-invariant feature detection and extraction

Sincre Layer-A:
 - Key frame extractor and cloud support services
 - Input: video
 - Output: key frames
 - Algorithm: HSV-based Histogram 

Sincre Layer-B
 - Hosts FrameProcessor core and Sincre Layer-A 
 - Invokes processing pipeline
 - Invokes messaging with search engine
 - Enforces fault-tolerance with search engine
 
Sincre Layer-AB WCF Service Library:
 - Edge functions 
 - Admin functions: ETL configuration
 - Layer-AB as a service 
 
Sincre Layer-AB Web Service:
 - Library web service
 - Developers API support

Sincre WebFront:
 - User web app

