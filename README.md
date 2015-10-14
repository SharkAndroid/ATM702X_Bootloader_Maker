ATM702X_Bootloader_Maker
========================
- This program compiles Bootloader(.fw) for Ainol devices that has Actions ATM702X(7029,7025) processor.
- ONLY FOR WINDOWS OS!

How to compline?
================
- Go to:
/ainol_atm702x_bootloader/rootfs/fwmisc/ (where x is a cpu version).
- Copy into this folder misc files from your device:
config.xml,
gpiocfg.xml,
pinctrl.xml.
- Change "BRAND" and "DEVICE" in fwimage_linux.cfg file to your.
- Run Make_Bootloader.exe.
- Wait 10-15 seconds.
- Bootloader(.fw) compiled.

Copyrights
==========
* Copyright © 2014, Actions-Semi, Inc.
* Copyright © 2014, SharkAndroid(iBullRay).
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*     http://www.apache.org/licenses/LICENSE-2.0
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.