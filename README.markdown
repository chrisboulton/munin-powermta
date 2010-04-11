munin-powermta
==============

Introduction
------------

Various plugins to monitor/graph statistics from PowerMTA. (http://port25.com/)

* powermta_connections - Number of connections in to and out of PowerMTA
* powermta_queues - Number of messages in different PowerMTA queues
* powermta_traffic_ - Wildcard plugin for monitoring volume of mail (either by
  message or traffic) passing in and out of PowerMTA

Installation and Configuration
------------------------------

*Please make sure that the PowerMTA web interface is enabled*

Install as you would for a normal Munin plugin.

Configuration defaults to looking for a PowerMTA installation on
http://localhost:8080/ with no username/password. This can be changed in the
Munin configuration like so:

[powermta_*]
env.url http://localhost:8080
env.auth_user admin
env.auth_password somepass

Author
------

Chris Boulton <chris.boulton@interspire.com>
http://chrisboulton.net/
http://github.com/chrisboulton/munin-powermta

Version
-------
1.0

Copyright and License
---------------------

Copyright (c) 2010, Chris Boulton
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
3. All advertising materials mentioning features or use of this software
   must display the following acknowledgement:
   This product includes software developed by Chris Boulton.
4. Neither the name of Chris Boulton nor the
   names of its contributors may be used to endorse or promote products
   derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY CHRIS BOULTON ''AS IS'' AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.