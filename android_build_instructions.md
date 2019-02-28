# System requirements
- A 64-bit Intel machine running Linux with at least 8GB of RAM. More than 16GB is highly recommended.
- At least 100GB of free disk space.
- You must have Git and Python installed already.

Most development is done on Ubuntu. Other distros may or may not work; see the Linux instructions for some suggestions.
Building the Android client on Windows or Mac is not supported and doesn't work.

# Install depot_tools
- Clone the depot_tools repository:

    ```git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git```
    
- Add depot_tools to the end of your PATH (you will probably want to put this in your ~/.bashrc). Assuming you cloned depot_tools to /path/to/depot_tools:

    ```export PATH="$PATH:/path/to/depot_tools"```

   - 注意：此处的/path/to/是指depot_tools所在的路径
   
# Get the code
- Create a chromium directory for the checkout and change to it (you can call this whatever you like and put it wherever you like, as long as the full path has no spaces):

    ```mkdir ~/chromium && cd ~/chromium```
    
    ```fetch --nohooks android```
- When fetch completes, it will have created a hidden .gclient file and a directory called src in the working directory. The remaining instructions assume you have switched to the src director

   ``` cd src  ```
