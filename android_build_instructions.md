# System requirements
- A 64-bit Intel machine running Linux with at least 8GB of RAM. More than 16GB is highly recommended.
- At least 100GB of free disk space.
- You must have Git and Python installed already.

Most development is done on Ubuntu. Other distros may or may not work; see the Linux instructions for some suggestions.
Building the Android client on Windows or Mac is not supported and doesn't work.

# Install depot_tools
- Clone the depot_tools repository:

    ```git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git```
- Add depot_tools to the end of your PATH (you will probably want to put this in your ~/.bashrc or ~/.zshrc). Assuming you cloned depot_tools to /path/to/depot_tools:
``` export PATH="$PATH:/path/to/depot_tools"  ```
   - 注意：此处的/path/to/是指depot_tools所在的路径
