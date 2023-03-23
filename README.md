tequ-node-red-gstreamer-wd
=====================

Watchdog for tequ-node-red-gstreamer node.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install tequ-node-red-gstreamer-wd

## Information

Works paired with "tequ-node-red-gstreamer"-node
- Input should be connected to TCP output node where stream is coming from.
- Output should be connected to "tequ-node-red-gstreamer"-node input.
- Restarts "tequ-node-red-gstreamer"-node if stream fps goes to zero.

Dependencies:
- https://flows.nodered.org/node/node-red-contrib-msg-speed
