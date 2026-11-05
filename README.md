# WheelOS Tool Kit

This repository owns developer and operational tools shared across WheelOS
products. Apollo-Lite consumes these tools through Bzlmod; `wheelos.repos`
selects the checkout for development, while release consumers use a published
module version.

The current packages are:

- `modules/tools/visualizer`: Qt-based Cyber message visualizer.
- `modules/tools/roadlog`: triggered recorder and its default configuration.

The Qt SDK is a host/container input. Its Bazel repository and build rules are
owned here with the visualizer, not by an integration product.
