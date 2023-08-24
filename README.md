<h1 align="center">XM Decoder</h1>
<h4 align="center">A utility to decrypt Ximalaya .xm audio files</h4>

### Introduction

This repository is a fork of [Diaoxiaozhang's Ximalaya-XM-Decrypt](https://github.com/Diaoxiaozhang/Ximalaya-XM-Decrypt). The original tool was designed to decrypt Ximalaya's .xm audio files, and this fork introduces various enhancements and improvements to the original code, adding the abilitiy to make sure the output files are in the desired format.

### Prerequisites

- Ensure you have `ffmpeg` installed and accessible from the command line. This is necessary for the audio format conversion feature.  
- Always maintain a backup of your original `.xm` files before using this tool.  
- It's essential for the `xm_encryptor.wasm` file to be in the same directory as the main script for the decryption process to work.  

### Usage
  
python main.py -i /path/to/input/directory -o /path/to/output/directory -f mp3  
  
### Options:  
-i, --input: (Required) Path to the input directory containing the .xm files to decrypt.   
-o, --output: Path to the output directory where decrypted files will be saved. Default is ./output.   
-f, --format: The desired output format for the decrypted files. Supported values are mp3, m4a, flac, and aac. Default is mp3.  

### Disclaimer  
This tool is intended for personal and educational use only. Always respect copyright laws and platform terms of service when using this or any other related tool.
