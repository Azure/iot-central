# Awesome IoT Central [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Useful resources for creating solutions with [IoT Central](https://aka.ms/iotcentral) that make you say "Wow, this is amazing!"

## index
- [architecture guidance](#architecture-guidance)
- [connecting devices](#connecting-devices)
- [testing devices](#testing-devices)
- [companion experiences](#companion-experiences)
- [transformation and compute](#transformation-and-compute)
- [additional resources](#additiona-resources)

## architecture guidance
[iot-central-integration-guide](https://github.com/Azure/iot-central-integration-guide) - integration patterns and samples for using IoT Central as part of your overall IoT architecture

## connecting devices
A curated list of repositories that show how to code devices to take full advantage of IoT Central features, including its multi-hub high availability capabilities.

| Repository                                                                                                  | Description                                                                                                            | Type     |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-high-availability-clients](https://github.com/Azure/iot-central-high-availability-clients) | Full device client samples that illustrates how to code a high availability device client for use with IoT Central | Code |
| [iot-central-batch-telemetry-with-python](https://github.com/Azure/iot-central-batch-telemetry-with-python) | Samples showing how to send batch data to IoT Central (and IoT Hub) with Python using the Azure IoT hub REST interface | Code |
| [iot-central-file-upload-device](https://github.com/Azure/iot-central-file-upload-device) | Sample showing how to use the file upload feature of IoT Hub from within an IoT Central app | Code |
| [iot-central-web-mqtt-device](https://github.com/Azure/iot-central-web-mqtt-device) | A simple IoT device that runs fully contained in the web browser and communicates with Azure IoT Central over MQTT (using websockets) | Code |
| [iot_central_python_sample](https://github.com/Azure/iot_central_python_sample) | A simple sample device written in Python able to do bi-directional communication with IoT Central | Code |
| [iot-central-paad](https://github.com/Azure/iot-central-paad) | React-native phone app that uses your phone as a device in IoT Central.  App is available in the Android and IPhone stores | Code |


[⬆ back to index](#index)

## testing devices
A curated list of repositories that help debug and test device code.

| Repository                                                                                                  | Description                                                                                                            | Type     |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | -------- |
| [azure-iot-cli-extension](https://github.com/Azure/azure-iot-cli-extension#microsoft-azure-iot-extension-for-azure-cli) | A tool to view current state of the device twin | Code |
| [azure-iot-cli-extension](https://github.com/Azure/azure-iot-cli-extension#microsoft-azure-iot-extension-for-azure-cli) | A command line tool for debugging device/cloud messaging, including ability to cause fault and test device failover | Code |

[⬆ back to index](#index)

## companion experiences
A curated list of repositories that show how to build companion web and phone applications using IoT Central’s APIs.

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-companion-experiences-learning](https://github.com/Azure/iot-central-companion-experiences-learning) | Walks through building companion experiences with IoT Central | Learning Journey |
| [iot-central-contoso-drive-support](https://github.com/Azure/iot-central-contoso-drive-support) | An IoT Central companion experience that demonstrates how to build a custom web app for a support technician operating a fleet management solution | Code |
| [iot-central-contoso-drive-simulator](https://github.com/Azure/iot-central-contoso-drive-simulator) | An IoT Central companion experience that demonstrates how to build a web app that does device simulation (use with the Contoso-Drive Support application) | Code |
| [iot-central-aad-setup](https://github.com/Azure/iot-central-aad-setup) | Guidance on setting up an Azure Active Directory application to work with IoT Central | Guidance |
| [iot-central-aad-app](https://github.com/Azure/iot-central-aad-app) | A small codebase showing how to authenticate/authorize to use IoT Central control and data plane APIs | Code |

[⬆ back to index](#index)

## transformation and compute

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Azure/iotc-device-bridge](https://github.com/Azure/iotc-device-bridge) | Runnable as an Azure Function or Container, bridge transforms and sends unidirectional data using HTTP in cloud-to-cloud integrations with IoT Central | Code |

[⬆ back to index](#index)

## additional resources
- [Resources](https://github.com/Azure/iot-central/blob/main/additional_resources.md) - a collection of resources from across the web
