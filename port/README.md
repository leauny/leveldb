This directory contains interfaces and implementations that isolate the
rest of the package from platform details.

该目录包含接口和实现，将软件包的其他部分与平台细节隔离开来。

Code in the rest of the package includes "port.h" from this directory.
"port.h" in turn includes a platform specific "port_<platform>.h" file
that provides the platform specific implementation.

软件包其他部分的代码包含该目录中的 "port.h"。
"port.h "又包含一个平台专用的 "port_<platform>.h "文件，该文件提供平台专用的实现。

See port_stdcxx.h for an example of what must be provided in a platform
specific header file.

请参阅 port_stdcxx.h，了解平台特定头文件中必须提供的内容。