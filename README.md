# Record WAV files using your microphone with Python

## Install

```
git clone git@github.com:egorsmkv/microphone-recorder.git
cd microphone-recorder
```

### MacOS

```
brew install portaudio

pipenv install
pipenv shell

pip install --global-option='build_ext' --global-option='-I/usr/local/include' --global-option='-L/usr/local/lib' pyaudio
```

## Usage

```
python record.py
```

Next you can open the `recording.wav` using a media player.

