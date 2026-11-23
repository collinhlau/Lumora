# Third-Party Notices

Lumora uses the open-source components listed below. Copyright in each component belongs to its authors, and each is distributed under its own license.

This file ships with the software. If you have an installer, you will find it inside the application resources; in the source repository it sits at the project root.

---

## epub.js 0.3.x

- License: BSD-2-Clause
- Project: https://github.com/futurepress/epub.js

```
Copyright (c) 2014-2024 Future Press
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

## PDF.js (pdfjs-dist) 4.x

- License: Apache License 2.0
- Project: https://github.com/mozilla/pdf.js

```
Copyright 2012 Mozilla Foundation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## JSZip 3.10.x

- License: MIT (used here under the MIT terms; upstream also offers GPL-3.0-or-later)
- Project: https://github.com/Stuk/jszip

## React / React DOM 18.x

- License: MIT
- Project: https://github.com/facebook/react

## Electron 33.x / 22.x

- License: MIT
- Project: https://github.com/electron/electron

Electron bundles Chromium and Node.js, distributed under BSD-3-Clause and MIT respectively; their license information is in `LICENSES.chromium.html` inside the package.

## iconv-lite 0.6.x

- License: MIT
- Project: https://github.com/ashtuchkin/iconv-lite

---

## MIT License, in full

The following text applies to every component marked MIT above:

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## On DRM

This project contains **no** DRM (digital rights management) circumvention or decryption functionality, and does not accept contributions that add any. When a DRM-protected file is encountered, Lumora reports it and stops parsing, showing only the metadata it can read.

The software claims no rights over the content you import. Please use only files you have the right to read.

## Fonts

The interface bundles no font files; it only references font names provided by the operating system (such as New York, Songti SC, and PingFang SC). No third-party commercial font licensing is therefore involved.
