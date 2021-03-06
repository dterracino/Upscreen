========================================================================
    Upscreen 2.0
========================================================================

// General Description

Upscreen is a screenshot utility using the imgur API.

This program gets information from the clipboard, if it's an
image file, saves it as a bitmap, converts it to PNG, and uploads
the image to the imgur image hosting service. After uploading
it will open the editor page at the default web browser.

/// Usage

This program is built mainly for screenshots, though this can be used on any image.
If you want to upload a screenshot, press the PrtScn key (get screenshot),
and Ctrl + Shift + PrtScn key (upload screenshot).

If you want to use this on a regular image (on the web), copy the image to clipboard
and again, press Ctrl + Shift + PrtScn key to upload.

/// Compilation and Testing

This is compiled, built, and tested on MSVS 2010 and MSVS 2012 RC
You must supply your own anonymous API key from imgur (it's free!), see app.config

/// License

Copyright (c) 2010-2012, Ruel Pagayon
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
	* Redistributions of source code must retain the above copyright
	  notice, this list of conditions and the following disclaimer.
	* Redistributions in binary form must reproduce the above copyright
	  notice, this list of conditions and the following disclaimer in the
	  documentation and/or other materials provided with the distribution.
	* Neither the name of the author nor the names of its contributors 
	  may be used to endorse or promote products derived from this software 
	  without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS "AS IS" AND ANY 
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED 
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, 
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT 
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, 
OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF 
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE 
OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF 
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.