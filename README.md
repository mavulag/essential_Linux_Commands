# essential_Linux_Commands

## Creating files (e.g 1 to 10) inside specific path: 
for x in $(seq 1 10); do echo "This is file number $x." > /tmp/lima/stuff/file-$x; done
