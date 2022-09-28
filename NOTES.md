Had to install pkg-config 
```
 sudo apt install pkg-config
```

because of:

```
vscode ➜ /workspaces/doom-wasm (main ✗) $ ./scripts/build.sh 
make: make clean
make: *** No rule to make target 'clean'.  Stop.
configure: autoreconf -fiv
autoreconf: Entering directory `.'
autoreconf: configure.ac: not using Gettext
autoreconf: running: aclocal --force 
autoreconf: configure.ac: tracing
autoreconf: configure.ac: creating directory autotools
autoreconf: configure.ac: not using Libtool
autoreconf: running: /usr/bin/autoconf --force
configure.ac:40: error: possibly undefined macro: AS_IF
      If this token and others are legitimate, please use m4_pattern_allow.
      See the Autoconf documentation.
configure.ac:90: error: possibly undefined macro: AC_DEFINE
configure.ac:92: error: possibly undefined macro: AC_MSG_FAILURE
autoreconf: /usr/bin/autoconf failed with exit status: 1
configure: ./configure --host=none-none-none
configure: error: cannot find install-sh, install.sh, or shtool in autotools "."/autotools
make: make
make: *** No targets specified and no makefile found.  Stop.

```

```
python3 -m http.server 8000
```
