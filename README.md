install:

git clone https://github.com/juj/emsdk.git
cd emsdk

# Fetch the latest registry of available tools.

./emsdk update

# Download and install the latest SDK tools.

./emsdk install latest

# Make the "latest" SDK "active" for the current user. (writes ~/.emscripten file)

./emsdk activate latest

# Activate PATH and other environment variables in the current terminal

source ./emsdk_env.sh

run:

npm start
