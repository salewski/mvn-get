# mvn-get

## Download a maven artifact (and its dependencies) from the command line.


# Overview

This is the README.md file for the `'mvn-get'` project, which will very likely
expand into an `'ads-mvn-tools'` project.

At the moment, this just contains a scratcher for today's itch: the
`'mvn-get'` program, which is at its core just a wrapper around a `'mvn'`
command invocation that uses the `maven-dependency-plugin`. It is useful "as
is", but will probably turn into a repo of the various maven-related tools
I've created over the years from my personal `~/bin/` directory.


# Usage
```
    $ mvn-get [OPTION...] groupId:artifactId:version[:type[:classifier]] [--] [MVN_OPTION...]
```

# Example:

```
    $ mvn-get org.apache.avro:avro:1.8.2
```


# License

GPLv2+: GNU GPL version 2 or later <http://gnu.org/licenses/gpl.html>

Unless otherwise stated by a different license notice in a particular file,
all files in the `mvn-get' project are made available under the GNU GPL
version 2, or (at your option) any later version.

See the [COPYING] file for the full license.

Copyright (C) 2019 Alan D. Salewski <salewski@att.net>

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.



[COPYING]:      https://github.com/salewski/mvn-get/blob/master/COPYING
