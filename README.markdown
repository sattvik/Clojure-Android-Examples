Examples for *Creating Android applications with Clojure*
=========================================================

This repository contains the example code to illustrate the techniques
described in *Creating Android applications with Clojure*.  You can use these
examples as templates for your own projects

Contents
--------

These examples are separated into the following directories:

* `basic`, corresponding to the basic configuration described in
  *[Creating Android applications with Clojure: Building with Ant][p2]*
* `slimmed`, corresponding to the slimmed configuration described in
  *[Creating Android applications with Clojure: Slimming things down with
  ProGuard][p3]*


[p2]: http://www.deepbluelambda.org/programming/clojure/creating-android-applications-with-clojure--building-with-ant
[p3]: http://www.deepbluelambda.org/programming/clojure/creating-android-applications-with-clojure--slimming-things-down-with-proguard


Instructions
------------

In order to use these examples, you must have installed the Android SDK and
installed the necessary components.  These examples were developed using
version 8 of the SDK (Android 2.2 ‘FroYo’).  For information on how
to accomplish this, please consult the [Android SDK documentation][sdk].

[sdk]: http://developer.android.com/sdk/index.html

You will need to copy the `local.properties.example` to `local.properties` in
each project directory and modify the line starting with `sdk.dir` to point to
where the Android SDK is installed.


License
-------

This repository is made available under the terms of the “MIT License” as
stated below.  This repository also contains binary versions of the Clojure
library, which are licensed separately under the terms of the Eclipse Public
License.  Clojure also includes the ASM bytecode engineering library, which is
licensed under the terms of a “BSD License” included below.

### Repository License

Copyright © 2011 Daniel Solano Gómez

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


### Clojure

Copyright © Rich Hickey.
All rights reserved.

The use and distribution terms for this software are covered by the Eclipse
Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php) which can
be found in the file epl-v10.html at the root of this distribution.  By using
this software in any fashion, you are agreeing to be bound by the terms of this
license.

You must not remove this notice, or any other, from this software.


### ASM License

Copyright © 2000-2005 INRIA, France Telecom
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holders nor the names of its contributors
   may be used to endorse or promote products derived from this software
   without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
