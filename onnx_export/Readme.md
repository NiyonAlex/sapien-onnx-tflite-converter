## Install packages
```
pip install -r requirements.txt
```

## Export to ONNX
To export the model to ONNX, run the following script:
```bash
python export_onnx.py pose03b
```
The available models are `seg03b`, `seg06b`, `seg1b`, `depth03b`, `depth06b`, `depth1b`, `depth2b`, `normal03b`, `normal06b`, `normal1b`, `normal2b`, `pose03b`, `pose06b`, `pose1b`.