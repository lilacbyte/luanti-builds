# luanti release builder

for linux, it just makes binaries and a .deb file

## what it does

1. checks upstream Luanti releases daily
2. if a new version is found, it builds and releases server + desktop artifacts

## packaging

- server build uses `BUILD_SERVER=TRUE` and `BUILD_CLIENT=FALSE` build flags
- desktop build produces `.deb`, sorry make a pr if you want other distros :heart:
