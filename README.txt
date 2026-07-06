@"
# Subtitle Pipeline

Local subtitle generation / timing pipeline using faster-whisper and FFmpeg.

## Setup

```powershell
py -3.13 -m venv whisper-env
.\whisper-env\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt