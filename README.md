# Awesome IoT Central [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Useful resources for creating solutions with [IoT Central](https://aka.ms/iotcentral) that make you say "Wow, this is amazing!"

## Index
-   [connecting devices](#connecting-devices)
-   [companion experiences](#companion-experiences)

## guidance
- [iot-central-integration-guide](https://github.com/Azure/iot-central-integration-guide) - integration patterns and samples for using IoT Central as part of your overall IoT architecture

## learning paths
- Coming Soon

## connecting devices
A curated list of repositories that show how to code devices to take full advantage of IoT Central features, including its multi-hub high avialibality capabilities.

| Repository                                                                                                  | Description                                                                                                            | Type     |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-high-availability-clients](https://github.com/Azure/iot-central-high-availability-clients)     | Full device client samples that illustrates how to code a high availability device client for use with IoT Central     | Code     |
| [iot-central-batch-telemetry-with-python](https://github.com/Azure/iot-central-batch-telemetry-with-python) | Samples showing how to send batch data to IoT Central (and IoT Hub) with Python using the Azure IoT hub REST interface | Code     |
| [iot-central-file-upload-device](https://github.com/Azure/iot-central-file-upload-device)                   | Sample showing how to use the file upload feature of IoT Hub from within an IoT Central app                            | Code     |

###### [⬆ Back to Index](#index) ######

## testing devices
- [iotc-twinviewer](https://github.com/iot-for-all/iotc-twinviewer) - tool to view current state of the device twin
- [azure-iot-cli-extension](https://github.com/Azure/azure-iot-cli-extension#microsoft-azure-iot-extension-for-azure-cli) - command line tool for debugging device/cloud messaging

## companion experiences
A curated list of repositories that show how to build companion web and phone applications using IoT Central’s APIs. 

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-aad-setup](https://github.com/Azure/iot-central-aad-setup)                             | Guidance on setting up an Azure Active Directory application to work with IoT Central                                                                     | Guidance |                                                                    |
| [iot-central-contoso-drive-support](https://github.com/Azure/iot-central-contoso-drive-support)     | An IoT Central companion experience that demonstrates how to build a custom web app for a support technician operating a fleet management solution        | Code     |
| [iot-central-contoso-drive-simulator](https://github.com/Azure/iot-central-contoso-drive-simulator) | An IoT Central companion experience that demonstrates how to build a web app that does device simulation (use with the Contoso-Drive Support application) | Code     |
| [iot-central-aad-app](https://github.com/Azure/iot-central-aad-app)                                | A small codebase showing how to authenticate/authorize to use IoT Central control and data plane APIs                                                     | Code     |


## transformation
- [Azure/iotc-device-bridge](https://github.com/Azure/iotc-device-bridge) - runnable as an Azure Function or Container, it transforms and sends unidirectional data using HTTP in cloud-to-cloud integrations with IoT Central

## compute
- Coming Soon

## documentation
- [Overview of Azure IoT Central](https://docs.microsoft.com/en-us/azure/iot-central/core/overview-iot-central)
- [Connect Azure IoT Edge Devices to an Azure IoT Central](https://docs.microsoft.com/en-us/azure/iot-central/core/concepts-iot-edge)
- [Docs](https://docs.microsoft.com/en-us/azure/iot-central/core/tutorial-connect-device-python) - Python SDKs and samples
- [Docs](https://docs.microsoft.com/en-us/azure/iot-central/core/tutorial-connect-device-nodejs) - Node.js SDKs and samples
- [Develop with Sphere and Azure RTOS](https://docs.microsoft.com/en-us/learn/modules/develop-secure-iot-solutions-azure-sphere-iot-central/) - Sphere tutorial
- [IoT Show](https://aka.ms/iotshow) - videos

## additional resources
- [Resources](https://github.com/Azure/iot-central/blob/main/additional_resources.md) - a collection of resources from across the web
