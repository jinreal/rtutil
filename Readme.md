A runtime utility that simplify basic operations of language runtimes in linux.

# Language Runtime Support
|language/runtime|comment|
|-|-|
|gcc||
|g++||
|go||
|nodejs||
|python||

# Install
1. Download:
```
wget https://raw.githubusercontent.com/jinreal/rtutil/main/rt
```
2. Make `rt` executable:
```
chmod +x rt
```
3. Copy `rt` to binary directory(e.g. `/usr/local/bin`):
```
cp rt BINARY_DIRECTORY
```

# Usage
Run a c file:
```
rt main.c
```

Run a c++ file:
```
rt main.cc
```

Run a go file (project must be initialized using `go mod init`):
```
rt main.go
```

Run a node.js file:
```
rt main.js
```

Run a python file:
```
rt main.py
```

# Test Language Runtime & System
|language/runtime|version|
|-|-|
|gcc|12.2.0|
|g++|12.2.0|
|go|1.19.8|
|nodejs|20.11.1|
|python|3.11.2|

__system__: MX 23.2 (Debian GNU/Linux 12, kernel=6.1.0-17-amd64)