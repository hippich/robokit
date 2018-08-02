### electron-typescript-robokit

![RoboKit](docs/img/RoboKit.png)

An electron app for transforming a device (i.e. Mac, Raspberry Pi, etc.) into a voice-driven robot.

Note: This a work in progress.

[Demo Video - YouTube](https://youtu.be/r_Vzp8tXdkI)

#### Config

- duplicate `data/config-example.json` and rename it `config.json`  
- add your Bing STT subscription key
- add your LUIS credentials
- (optional) upload `docs/LUIS-knowledge-graph.json` to LUIS to configure a new NLU app

#### Building

```
yarn
yarn start
```

#### Dependencies

OSX  
```
brew install sox
```

#### UI

Use the UI buttons to trigger Speech to Text listening and Midi playback.

#### Notes

RoboKit uses:
- Snowboy ([https://www.npmjs.com/package/snowboy](https://www.npmjs.com/package/snowboy)) for **hotword** detection.
- Pixi.js ([https://www.npmjs.com/package/pixi.js](https://www.npmjs.com/package/pixi.js)) for screen animation

#### License

[MIT](LICENSE.md)
