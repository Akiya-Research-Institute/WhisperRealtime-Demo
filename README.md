# UE5.1 demo project for `WhisperRealtime` plugin

This is a UE5.1 project for demonstration of [Whisper-based Real-time Speech Recognition](https://www.unrealengine.com/marketplace/product/d293a6a427c94831888ca0f47bc5939b), or `WhisperRealtime` for short, an Unreal Engine plugin for real-time speech-to-text transcription and alignment with multi-language support, based on OpenAI's Whisper model.

## System Requirements

- Windows 10 64bit
- Unreal Engine 5.1.0
- WhisperRealtime plugin v1.0.0 or above
- Microphone connected to your PC

If you want to run with GPU,

- CUDA: 11.6
- cuDNN: 8.5.0.96

## How to use this demo

1. Clone this repo: `git clone git@github.com:Akiya-Research-Institute/WhisperRealtime-Demo.git`
2. Open `WhisperRealtime-Demo/WhisperRealtimeDemo5.uproject`
3. Click `Content Drawer > Add > Add Feature or Content Pack...` 
4. Select `Third Person` on Blueprint tab and click `Add to Project`
5. Restart Unreal Editor.
6. Click `Play` on Unreal Editor.

## How to select microphone

Select from the Windows (OS) setting.

## Options

Demo project contains 3 maps which corresponds to the 3 features described in "How to use" section of the [manual](https://akiya-research-institute.github.io/WhisperRealtime-Manual/en/how-to-use-transcript/).