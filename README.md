OSSEC v2.8 Copyright (C) 2014 Trend Micro Inc.

# Information about OSSEC 

OSSEC is a full platform to monitor and control your systems. It mixes together 
all the aspects of HIDS (host-based intrusion detection), log monitoring and 
SIM/SIEM together in a simple, powerful and open source solution.

Visit our website for the latest information.  [www.ossec.net](http://www.ossec.net)



## Current Releases 

The current stable releases are available on the ossec website. 

* Releases can be downloaded from: [Downloads](http://www.ossec.net/?page_id=19)
* Release documentation is available at: [docs](http://www.ossec.net/doc/)

## Development ##

The development version is hosted on GitHub and just a simple git clone away. 

[![Build Status](https://travis-ci.org/ossec/ossec-hids.png?branch=master)](https://travis-ci.org/ossec/ossec-hids)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/1847/badge.svg)](https://scan.coverity.com/projects/1847)


## Quick install 

```
# (cd /tmp/ && wget https://github.com/ossec/ossec-hids/archive/2.8.1.tar.gz && mv 2.8.1.tar.gz ossec-hids-2.8.1.tar.gz && tar xfz ossec-hids-2.8.1.tar.gz && cd ossec-hids-2.8.1 && sudo ./install.sh )

```

Then follow the prompts.  You should still Read the Documentation [here](http://ossec.net/doc/).

## Credits and Thanks ##

* OSSEC comes with a modified version of zlib and a small part 
  of openssl (sha1 and blowfish libraries)
* This product includes software developed by the OpenSSL Project
  for use in the OpenSSL Toolkit (http://www.openssl.org/).
* This product includes cryptographic software written by Eric 
  Young (eay@cryptsoft.com)
* This product include software developed by the zlib project 
  (Jean-loup Gailly and Mark Adler).
* This product include software developed by the cJSON project 
  (Dave Gamble)


