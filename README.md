# Awesome IoT Central [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A collection of useful resources for creating solutions with [IoT Central](https://aka.ms/iotcentral) that make you say "Wow, this is amazing!"


## index
- [Architecture guidance](#architecture-guidance)
- [Connect and test devices](#connect-and-test-devices)
- [Companion and integrated experiences](#companion-and-integrated-experiences)
- [Transformation and compute](#transformation-and-compute)
- [Application DevOps](#application-devops)
- [Additional resources](#additional-resources)

## Architecture guidance
[iot-central-integration-guide](https://github.com/Azure/iot-central-integration-guide) - integration patterns and samples for using IoT Central as part of your overall IoT architecture

## Connect and test devices
A curated list of repositories that show you how to code, test, and debug devices to take full advantage of IoT Central features, such as its multi-hub, high availability capabilities.  

| Repository                                                                                                  | Description                                                                                                            | Type     |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-high-availability-clients](https://github.com/Azure/iot-central-high-availability-clients) | Sample code that shows you how to code a high availability device that connects to IoT Central. | Code |
| [azure-iot-cli-extension](https://github.com/Azure/azure-iot-cli-extension#microsoft-azure-iot-extension-for-azure-cli) | A command line tool for debugging device/cloud messaging, including ability to cause fault and test device failover. | Code || [iot-central-batch-telemetry-with-python](https://github.com/Azure/iot-central-batch-telemetry-with-python) | Sample code that shows you how to send batch data from a device to IoT Central or IoT Hub. Uses Python and the Azure IoT Hub REST interface. | Code |
| [iot-central-file-upload-device](https://github.com/Azure/iot-central-file-upload-device) | Sample code that shows you how to use the file upload feature of IoT Hub from within an IoT Central app. | Code |
| [iot-central-web-mqtt-device](https://github.com/Azure/iot-central-web-mqtt-device) | A simple IoT device that runs fully contained in the web browser. It communicates with Azure IoT Central over MQTT using websockets. | Code |
| [iot_central_python_sample](https://github.com/Azure/iot_central_python_sample) | Simple sample device code that shows you how to use Python for bi-directional communication with IoT Central. | Code |
| [iot-central-paad](https://github.com/Azure/iot-central-paad) | React-native phone app that uses your phone as a device in IoT Central.  The app is available in the Android and IPhone stores. | Code |
| [iot-central-micropython-client](https://github.com/Azure/iot-central-micropython-client)| A MicroPython sample for connecting devices to IoT Central. | Code |
| [iot-central-python-client](https://github.com/Azure/iot-central-python-client) | A Python sample for connecting devices to IoT Central. | Code |
| [iot-central-twinviewer](https://github.com/Azure/iot-central-twinviewer) | A tool to view current state of the device twin. | Code |

[⬆ back to index](#index)


## Companion and integrated experiences
A curated list of repositories that show how to build companion web and phone applications using IoT Central’s APIs, and integrate them into your IoT Central application using the External content tile.

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-companion-experiences-learning](https://github.com/Azure/iot-central-companion-experiences-learning) | Walks through building companion experiences with IoT Central. | Learning Journey |
| [iot-central-contoso-drive-support](https://github.com/Azure/iot-central-contoso-drive-support) | An IoT Central companion experience that demonstrates how to build a custom web app for a support technician operating a fleet management solution. | Code |
| [iot-central-contoso-drive-simulator](https://github.com/Azure/iot-central-contoso-drive-simulator) | An IoT Central companion experience that demonstrates how to build a web app that does device simulation. Use with the Contoso-Drive Support application. | Code |
| [iot-central-aad-setup](https://github.com/Azure/iot-central-aad-setup) | Guidance that describes how to set up an Azure Active Directory application to work with IoT Central. | Guidance |
| [iot-central-aad-app](https://github.com/Azure/iot-central-aad-app) | Code samples that show you how to authenticate/authorize to use IoT Central control and data plane APIs. | Code |
| [iot-central-industrial-OEE](https://github.com/Azure/iot-central-industrial-OEE) | Shows integrating an ADX dashboard into your IoT Central application using the External content tile.  ADX dashboard demonstrates OEE calculations for an industrial solutions.  | Code |

[⬆ back to index](#index)


## Transformation and compute
A curated list of repositories that show how transform data at both ingress and egress points within IoT Central.

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [iot-central-industrial-OEE](https://github.com/Azure/iot-central-industrial-OEE) | Shows using IoT Central's built in continuous data export (CDE) transformation capabilities.  | Code |
| [iotc-device-bridge](https://github.com/Azure/iotc-device-bridge) | The device bridge transforms and sends **unidirectional** data using HTTP in cloud-to-cloud integrations with IoT Central. Run either as an Azure Function or in a container. | Code |
| [iot-central-bidirectional-device-bridge](https://github.com/Azure/iot-central-bidirectional-device-bridge) | Transforms and sends/receives **bidirectional** data using AMQP in cloud-to-cloud integrations with IoT Central. | Code |
| [iot-central-compute](https://github.com/Azure/iot-central-compute) | A simple way to do compute and data transformation on data sent to IoT Central using Azure Functions. | Code |

[⬆ back to index](#index)

## Application DevOps
A currated list of repositories that show how to manage applications from development to production environments.

| Repository                                                                                          | Description                                                                                                                                               | Type     |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [howto-integrate-with-devops](https://docs.microsoft.com/en-us/azure/iot-central/core/howto-integrate-with-devops) | Guidance on using Azure DevOps pipelines and IoT Central's API to manage application lifecycles, from development to production.  | Guidance |
| [iot-central-CICD-sample](https://github.com/Azure/iot-central-CICD-sample) | Shows how to integrate IoT Central into an Azure DevOps pipeline for CI/CD. | Code |

[⬆ back to index](#index)

## Additional resources
- [Resources](https://github.com/Azure/iot-central/blob/main/additional_resources.md) - a collection of resources from across the web
