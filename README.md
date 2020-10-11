# sky130-3d-render

The idea of this repository is to create nice 3D renderings of integrated circuit structures based on open-source design data. For this, I have used [gds3xtrude](https://codeberg.org/tok/gds3xtrude) and [Blender](https://www.blender.org/).

## Scene 1

This file is based on the cell "sky130_fd_sc_hdll__dlrtp_4" from the [Skywater 130 nm PDK](https://github.com/google/skywater-pdk), which is a "delay latch, inverted reset, non-inverted enable, single output". nMOS devices are configured as orange light sources, pMOS devices emit a teal-colored light.

The original GDS layout file sky130_fd_sc_hdll__dlrtp_4.gds included in this repository is published under following license:

    Copyright 2020 SkyWater PDK Authors

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
