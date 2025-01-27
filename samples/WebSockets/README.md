# HTTP sample pack

Shows how to use the WebSockets related APIs in [System.Net.WebSockets](http://docs.nanoframework.net/api/System.Net.WebSockets.html).

## Samples

### WebSockets sample listener

[Sample1](./Websockets.Sample1) shows how to configure and start a WebSocket Server and Client.

## Hardware requirements

An hardware device with networking capabilities running a nanoFramework image.
This sample was tested with an STM32F769IDiscovery target board, but can be easily changed to any other target that has networking capabilities.

## Related topics

### Reference

- [System.Net.WebSockets](http://docs.nanoframework.net/api/System.Net.WebSockets.html)

## Build the sample

1. Start Microsoft Visual Studio 2019 (VS 2017 should be OK too) and select `File > Open > Project/Solution`.
1. Starting in the folder where you unzipped the samples/cloned the repository, go to the subfolder for this specific sample. Double-click the Visual Studio Solution (.sln) file.
1. Press `Ctrl+Shift+B`, or select `Build > Build Solution`.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select `Build > Deploy Solution`.

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select `Debug > Start Debugging`.

> **Important**: Before deploying or running the sample, please make sure your device is visible in the Device Explorer.
> **Tip**: To display the Device Explorer, go to Visual Studio menus: `View > Other Windows > Device Explorer`.
