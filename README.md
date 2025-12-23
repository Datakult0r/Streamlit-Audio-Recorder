# Streamlit Audio Recorder

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://audiorecorder.streamlit.app/)
[![Generic badge](https://img.shields.io/badge/PyPI-pip_install_streamlit--audiorec-black.svg)](https://pypi.org/project/streamlit-audiorec/)
[![GitHub license](https://img.shields.io/badge/Licence-MIT-gr.svg)](https://github.com/stefanrmmr/streamlit-audio-recorder/blob/main/LICENCE)

![Screenshot 2022-05-16 at 16 58 36](image.png) <br/>

## Features & Specs
- Manage access to the user's microphone via the **browser's Media-API**
- Record, playback and revert audio-recordings in apps **deployed to the web**
- Download the final recording to your local system! - **WAV, 16 bit, 44.1 kHz**
- Directly return audio recording-data to Python backend! - **arrayBuffer format**<br>

## Setup & How to Use
**1.** PIP Install the component (download from PyPI)
```
pip install streamlit-audiorec
```
**2.** Import and Initialize the component (at the top of your script)
```python
from st_audiorec import st_audiorec
```
**3.** Add an Instance of the audio recorder to your streamlit app's code.
```python 
wav_audio_data = st_audiorec()

if wav_audio_data is not None:
    st.audio(wav_audio_data, format='audio/wav')
```
**4. Enjoy recording audio inside your streamlit app! 🎈**

Feel free to reach out to me in case you have any questions! <br>
Please consider leaving a `star` ☆ with this repository to show your support.
