# Portfolio - Demos

# Spinnaker / OpenCV interface
- An API to control FLIR cameras that are compatible with their Spinnaker SDK.  This API simplifies common routines (camera start, shutdown, OpenCV conversion, etc...) into 1 line function calls.
  
# Object detection and classification library
- A library based on YoloV5 and TensorRT optimization for object detection and classification.  The primary intended application for this library is automotive.

# Thermal + RGB camera UI
- Flask based UI for camera viewing and control.  Communication via sockets between client UI and camera server.  Currently designed for use with FLIR cameras using above Spinnaker / OpenCV interface as well as the Luxonis DepthAI family of cameras.
