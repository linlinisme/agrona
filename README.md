Agrona
======

Agrona provides a library of data structures and utility methods that are a common need when building high-performance 
applications in Java and C++.

For the latest version information and changes see the [Change Log](https://github.com/real-logic/Agrona/wiki/Change-Log). 

Utilities Included:

* Buffers for working with on and off heap memory with memory ordering semantics.
* Open addressing Maps with int/long primitive keys to object reference values.
* Open addressing Maps with int/long primitive keys to int/long values.
* Open addressing Sets for int and long primitives.
* Lockless Queue implementations for low-latency applications.
* Off-heap ring and broadcast buffers for IPC communication.
* Basic Agent framework.
* Signal handling to support "Ctrl + c" in a server application.
* Scalable Timer Wheel.
* Basic code generation from annotated implementations that can vary on primitive types.
* Off-heap counters implementation for application telemetry.

Many of these utilities are used in the [Aeron](https://github.com/real-logic/Aeron) 
efficient reliable unicast and multicast message transport .

License (See LICENSE file for full license)
-------------------------------------------
Copyright 2014 - 2015 Real Logic Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Build
-----

### Java Build

You require the following to build Agrona:

* Latest stable [Oracle JDK 8](http://www.oracle.com/technetwork/java/)

Full clean and build and install into local maven repository

    $ ./gradlew
