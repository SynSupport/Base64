README for BASE64

Descriptions
------------

BASE64.DBL
This code for the BASE64 conversion was created by Tod Phillips (January 22nd 2009).  It accepts the same
parameters as the Synergy-l BASE64 submission by Nigel White (August 17th 2008), plus optional parameters
to force MIME-style encoding of the returned Base64 string (used in SMTP routines in which a CRLF is required
after every 76th character).  William Hawkins has also contributed to the code by adding Synergy v9 parameter
syntax.

Updates
------------
8/19/2009       Fixed a bug that dropped the final character of the converted text if there were "remaining characters"
                in the original string.
9/20/2010       Updated for Synergy 9.5


Subroutines and functions to DECODE a Base64 string have been removed, but may be added at a future date.

For further information on BASE64 see http://en.wikipedia.org/wiki/Base64

Submission details
------------------

Author:         Tod Phillips
Company:        Synergex
Email:          tod.phillips@synergex.com
Date:           22nd January 2009
Minimum version:v8.1
Platforms:      OpenVMS or Unix or Windows

