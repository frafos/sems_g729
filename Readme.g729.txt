
 Linphone Bcg729 codec wrapper
 -----------------------------

 Copyright (c) 2007, Vadim Lebedev
 Copyright (c) 2010, Stefan Sayer
 Copyright (c) 2012, Damjan Georgievski

 This is a wrapper for Linphone G729 codec.

 How to build g729 module
 ------------------------

 1. Get and install bcg729 from:
 http://www.linphone.org/eng/documentation/dev/bcg729.html

 2. Build bcg729 library
 run make; make install from root library

 About Licensing
 ---------------

 There is two distinct parts to G.729 licensing: The software licensing
 and the codec (patents) licensing.

 A. Software licensing

 1. The g729 codec wrapper code is licensed under simplified BSD license (see g729.c).

 2. The bcg729 fully open source library from Belledonne Communications (GPLv2 or later).

 3. SEMS is licensed under GPL; the Intel IPP license is not a GPL compatible
    license. Under the GPL, you may use (modify, compile, link, run, etc) SEMS code
    included by the g729 module, but the GPL does NOT allow redistribution of
    binaries linked with code licensed under the IPP license terms.

    If you are interested in distributing SEMS binaries with the g729 module
    (g729.so), please contact info@iptel.org to obtain a commercial license (see 
    doc/COPYING for details).

 B. Codec licensing

 To use G.729 codec, in many countries you need to get a license to use the
 patents (at least until 2016 or so). The G.729 patent pool is managed by
 Sipro: http://www.sipro.com/
