### v0.6.0

- New: ability to change video/audio speed and change each frame timestamp ([#10][10])
- New: ability to set the video output rotation ([#8][8])
- Improvement: new frame dropping algorithm, thanks to [@Saqrag][Saqrag] ([#9][9])
- Improvement: avoid format validation on tracks coming from PassThroughTrackTranscoder, thanks to [@Saqrag][Saqrag] ([#11][11])

### v0.5.0

- New: video cropping to any dimension. Encoder will crop the exceeding size. ([#6][6])
- New: `AspectRatioResizer` to crop to a given aspect ratio. ([#6][6])
- Breaking change: `MediaTranscoder` renamed to `Transcoder`. ([#6][6])
- Breaking change: `MediaTranscoderOptions` renamed to `TranscoderOptions`. ([#6][6])
- Breaking change: `MediaTranscoder.Listener` renamed to `TranscoderListener`. ([#6][6])
- Improvement: use [EglCore](https://github.com/natario1/EglCore) to replace GL logic. ([#5][5])
- Improvement: bug fixes and a new demo app to test transcoding options easily ([#4][4])

[Saqrag]: https://github.com/Saqrag

[4]: https://github.com/natario1/Transcoder/pull/4
[5]: https://github.com/natario1/Transcoder/pull/5
[6]: https://github.com/natario1/Transcoder/pull/6
[8]: https://github.com/natario1/Transcoder/pull/8
[9]: https://github.com/natario1/Transcoder/pull/9
[10]: https://github.com/natario1/Transcoder/pull/10