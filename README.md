echo-server
===========

Instructions
------------

1. If you do not already have a github account, create one.
2. Fork this project.
3. Update the LICENSE file with whatever license you prefer.
4. Add a copyright, license, and warranty notice at the top of each source file
   you create.
 * If you use the LICENSE file included, the information you need to include at
   the top of each source file can be found in the *License* section of this
   README. Just change __your-name-here__ to your full name.
5. Add a hello world program written in C to the project. The program should
   compile with GCC on a x86\_64 GNU/Linux system running Debian Stable. It
   will be compiled with the following flags:

          gcc -std=c99 -pedantic -Wall -Werror -Wextra -O0 -g -ggdb hello.c -o hello
6. Create an echo server.  It should be accessible via TCP on 127.0.0.1:7777.
 * The application will be compiled on Debian GNU/Linux using GCC with the
   following command:

          gcc -std=c99 -pedantic -Wall -Werror -Wextra -O0 -g -ggdb echo.c -o echo
 * It will be tested with:

          telnet 127.0.0.1 7777
 * The application should read up to 1 packet worth of data, write that data
   back to the client over the established connection, and then close the
   connection.  The server does not need to support concurrent connections.
   However, it should support multiple connections in serial.
7. Extra Credit: Modify the echo server program to log to standard error the IP
   address and port that the client has connected from.
8. Add any notes regarding your solution to the *Solution Notes* section.
9. Bonus Points: Like you, we are pedantic nerds. Please let us know if you
   find anything during this process or in our instructions that could use
   improvement.
10. Submit a link to your completed solution as well as any questions to
   <rreiher@camber.com>.


Solution Notes
--------------

*Add solution notes here*


License
-------

This file is part of Echo-Server.

Copyright (c) 2013 __your-name-here__

Echo-Server is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option) any
later version.

Echo-Server is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
Echo-Server.  If not, see <http://www.gnu.org/licenses/>.
