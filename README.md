Got a specific torque, backlash, mounting-interface, or CAD requirement? [Open an engineering request](https://github.com/SigGearDrive/SigGear-cad-models/issues/new/choose) or contact [wangwanrong@siggear.com](mailto:wangwanrong@siggear.com) – our engineers will reply within 24 hours.

# SigGear CAD Models

Official mechanical-integration resources for SigGear precision reducers, gear motors, and integrated robot joint actuators.

## Start Here

- [SigGear product documentation](https://siggeardrive.github.io/SigGear-product-docs/)
- [Robot joint actuator products](https://siggeardrive.github.io/SigGear-product-docs/products/robot-joint-actuators/)
- [Cycloidal joint modules](https://siggeardrive.github.io/SigGear-product-docs/products/cycloidal-joint-modules/)
- [Robot joint actuator selection guide](https://siggeardrive.github.io/SigGear-product-docs/selection-guides/robot-joint-actuator-selection-guide/)
- [Request CAD, sample, or quotation](https://siggeardrive.github.io/SigGear-product-docs/request-cad-sample-quote/)

## CAD Product Frameworks

The following product directories use the standardized `STEP`, `Preview`, and `Version` structure. A directory marked `template_only` does not contain a released public CAD model yet.

### Cycloidal Joint Modules

- [CPM-78-39](cycloidal-joint-modules/CPM-78-39/)
- [CPM-80-25](cycloidal-joint-modules/CPM-80-25/)
- [CPM-100-25](cycloidal-joint-modules/CPM-100-25/)

### Robot Joint Actuators

- [SG-6010C](robot-joint-actuators/SG-6010C/)
- [SG-6010D](robot-joint-actuators/SG-6010D/)
- [SG-8021](robot-joint-actuators/SG-8021/)

Each product directory contains release-status metadata. Check `Version/release-info.yml` before assuming a STEP file or preview image is available.

## Application Scenarios

These CAD resources are intended for mechanical layout, fit checks, prototype design, and supplier evaluation in applications such as:

- Humanoid robot hip, knee, ankle, shoulder, elbow, and wrist joints
- Quadruped robot leg actuators
- Industrial and collaborative robot arms
- Robotic grippers, end effectors, and dexterous-hand mechanisms
- AGV and AMR wheel-drive systems
- Medical-device and laboratory-automation motion modules
- Micro-robotics and compact precision mechanisms
- Servo motor and BLDC motor drive assemblies

## Available Resources

Depending on the product and release status, this repository may include:

- STEP and other common 3D CAD formats
- Outline and mounting-interface models
- Reducer and actuator envelope references
- Integration examples for robot joints and compact drive systems

Public file availability varies by model and configuration. Detailed production drawings, tolerance-controlled interfaces, and customer-specific files are supplied after engineering review.

## Engineering Notes

Public CAD files are provided for preliminary integration and reference. Final dimensions, tolerances, shaft and flange interfaces, cable exits, fasteners, bearings, motor configuration, encoder arrangement, and controller layout may vary by model or customer-specific configuration.

Before freezing a mechanical design, confirm the exact product model, reduction ratio, rated and peak torque, backlash target, mounting orientation, duty cycle, environmental conditions, and required interface dimensions with SigGear.

## Request a Missing or Customized CAD Model

Please provide:

- Product model or required product family
- Application and installation position
- Required torque and output speed
- Reduction ratio and backlash target
- Maximum diameter, length, and weight
- Shaft, flange, bolt-circle, and mounting requirements
- Motor, encoder, driver, connector, and cable-exit requirements
- Preferred CAD format
- Prototype quantity and estimated annual quantity

[Open an Engineering Request](https://github.com/SigGearDrive/SigGear-cad-models/issues/new/choose)

## Related Engineering Resources

- [Robot joint SDK](https://github.com/SigGearDrive/SigGear-robot-joint-sdk)
- [ROS2 resources](https://github.com/SigGearDrive/SigGear-ros2)
- [Product documentation](https://siggeardrive.github.io/SigGear-product-docs/)

## Contact

For detailed drawings, customized mounting interfaces, product selection, samples, or mechanical-integration support, contact:

[wangwanrong@siggear.com](mailto:wangwanrong@siggear.com)
