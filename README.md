# AAOS - Introduction

Automatic Astronomical Observatory Operating System

# Build Requirements

The following packages are needed to build the software

* autotools (autoconf, automake, libtool)
* doxygen (for creating the documentation, not started yet)
* tar
* libconfig >= 1.5 (for daemon servers)
* libcjson >= 1.7 (optional, if your want ASCOM device support)
* libcurl >= 7.6 (optional, if your want ASCOM device support)
* libgsl >= 2.5 (optional, for cubic spline interpolation)
* libsofa_c (optional, external IAU fundamental astronomy library for celetial coordinates transformation)  
* libudev >= 245 (optional, only available for Linux hosts)

# License

Copyright (C) 2015-2022 Free Software Foundation, Inc.

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301
USA.
