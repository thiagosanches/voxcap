# voxcap

VoxCap is a simple tool for narrating text and adding closed captions to your videos. Whether you're creating educational content or sharing information about technologies, VoxCap enhances the viewer's experience by providing both audio narration and text captions. The concept was to emulate the style of TikTok videos. There are probably cooler/better ways to do this, but I just wanted to give it a shot, and it turned out to be kinda fun!

![image](https://github.com/thiagosanches/voxcap/assets/5191469/7ebfda0e-4700-48e5-9ec1-956f74a084f8)

The primary objective is to utilize it with [OBS](https://obsproject.com/) by employing the Browser Source component.

## Requirements

- Web browser (tested on Mozilla Firefox).
- Google Cloud Text-To-Speech API key.

## How to use it ?

```
git clone https://github.com/thiagosanches/voxcap.git
```

- Open your OBS instance.
- Add a Browser source component and point to the [index.html](./index.html) (as a local source).
- Drag and drop it wherever you want. Personally, I toss it at the bottom of the video to hide the 'play' button. But, if you hit 'Interact' in OBS, you can click on the 'play' button to kick off both the audio and closed captions.
- Kick off your recording.

## How to set it up ?

You need to modify lines 61 and 62 by replacing the placeholder values with your API key and the desired text.

## Examples
- You can see this video [here](https://vm.tiktok.com/ZM6oLwN2n/) where it uses this little tool.

## TODO
- Please improve the code as soon as possible! I only did it as a Proof of Concept, but it definitely needs some love.
