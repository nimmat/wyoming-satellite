# Changelog

## 1.2.0

- Add `--tts-played-command`
- Add `--mic-seconds-to-mute-after-awake-wav` and `--mic-no-mute-during-awake-wav`
- Send preferred sound format to server

## 1.1.1

- Bump to wyoming 1.5.2 (package fix)

## 1.1.0

- Bump to wyoming 1.5.1
- Send wyoming-satellite version in `info` message
- Ping server if supported (faster awareness of disconnection)
- Support `pause-satellite` message
- Stop streaming/wake word detection as soon as `pause-satellite` is received or server disconnects
- Mute microphone when awake WAV is playing

## 1.0.0

- Initial release

