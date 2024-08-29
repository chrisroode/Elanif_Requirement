# Dependencies
The purpose of this document is to document and plan known dependencies for the project.

## Language used
The primary language for this project will either be C or C++.  This is still to be determined.  Addiionally, for handling screen rendering, the project will depend on OpenGL (and/or derivatives like Metal) and GLSL shaders to optimize rendering of music notation.

Design is leaning towards the use of cmake to compile the project.

## Intended platforms:
This software is intended to be truly cross platform, running on Windows, MacOS, and Linux.  Additionally, this software should maintain support on older versions of these operating systems:
- back to Windows 7
- back to MacOS 10.15.
- research for Linux configurations to be determined.

## Dependencies:
The following dependencies are intended to be used in the project:

### nanogui:
Being a cross platform UI library with a small footprint, this will be used to handle control of the user interface elements.  nanogui also serves as a gateway to configure openGL within the project.  As a result, nanogui may be customized for this use case.


## Unknowns
Here are other areas of the project where dependencies are unknown.
### testing framework
This application MUST be tested.  The testing library is till TBD.
### lilypond and musescore
Lilypond and musescore are complete open source projects that are also music notation software.  There needs to be a feasibility study to determine if either of these projects could be used in this software.