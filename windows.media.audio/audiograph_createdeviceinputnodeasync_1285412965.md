---
-api-id: M:Windows.Media.Audio.AudioGraph.CreateDeviceInputNodeAsync(Windows.Media.Capture.MediaCategory,Windows.Media.MediaProperties.AudioEncodingProperties)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Media.Audio.CreateAudioDeviceInputNodeResult> CreateDeviceInputNodeAsync(Windows.Media.Capture.MediaCategory category, Windows.Media.MediaProperties.AudioEncodingProperties encodingProperties)
-->

# Windows.Media.Audio.AudioGraph.CreateDeviceInputNodeAsync

## -description
Creates a device input node for the indicated media and audio encoding properties.

## -parameters
### -param category
An enumeration value indicating the category of the media processed by this node.

### -param encodingProperties
An object representing the audio encoding properties for the device input node.

## -returns
An asynchronous operation that returns a [CreateAudioDeviceInputNodeResult](createaudiodeviceinputnoderesult.md) on completion. This object exposes a [Status](createaudiodeviceinputnoderesult_status.md) property, that indicates either that the operation was successful or the reason why the operation failed. The [DeviceInputNode](createaudiodeviceinputnoderesult_deviceinputnode.md) property provides a reference to the created input node on success.

## -remarks
The *encodingProperties* parameter specifies the sample rate at which the created node will operate. Only uncompressed PCM and float formats are allowed.

## -examples

## -see-also
[CreateDeviceInputNodeAsync(MediaCategory)](audiograph_createdeviceinputnodeasync_420106269.md), [CreateDeviceInputNodeAsync(MediaCategory, AudioEncodingProperties, DeviceInformation)](audiograph_createdeviceinputnodeasync_757181607.md)
## -capabilities
backgroundMediaRecording
