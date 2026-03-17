make sure you install vcredist from softwares

uninstall pytorch
pip uninstall torch torchvision torchaudio

install pytorch again
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

install ffmpeg
winget install ffmpeg

```bash
# (1) optional preprocessing (normalize audio/video)
python  video_preprocess.py  --file_path  path/to/your.mp4

# (2) extract WavLM features
# this code consdiers `sample_data' as input and output directory
python  extract_wavlm_features.py
```

