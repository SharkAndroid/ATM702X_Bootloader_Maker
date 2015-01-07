actions_bootloader_maker
========================
- This program compiles Bootloader(FW) for gs702a platform that has Actions ATM7029 processor.
- ONLY FOR WINDOWS OS.

How to compline?
================
- Go to:
/ATM7029_A_4.4/rootfs/fwmisc/
- Copy into this folder misc files from your device:
config.xml,
gpiocfg.xml,
pinctrl.xml
and remove README.txt.
- Run Make_Bootloader.exe.
- Wait 10 seconds.
- Bootloader compiled.

Copyrights
==========
* Copyright (C) 2014 Actions-Semi, Inc.
* Copyright (C) 2014 SharkAndroid.
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*     http://www.apache.org/licenses/LICENSE-2.0
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.