
<p align="center">
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExendjcjZjN2Z2cXllMHB3ZXBubTBqeHJmcnl4cms4OTI2ampsbTB5dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vCFdAw72pa8lYaWyNR/giphy.gif", width="300", height="300">
</p>

<h1 align="center"> DEDSEC_IMGWARE</h1>
<h4 align="center"> hide payload inside image file</h4>

### DESCRIPTION
IMGWARE is a powerful tool designed to embed binary or ELF malware into Image files without corrupting the original image. The injected IMAGE looks and behaves like a normal Image file but contains hidden malicious code that can be executed under specific conditions. The tool generates a Python script that demonstrates how the malware is extracted from the Image. This script can be integrated into your own code or dropper for further use. This tool is intended for educational and research purposes only.

### Features

  * Stealthy Injection: Embeds malware into a IMAGE file without altering its appearance or functionality.
  * Preserves Original Image: The injected Image remains fully functional and visually identical to the original.
  * Payload Extraction: Generates a Python script (extraction.py) to extract the embedded payload from the Image file.
  * Supports multiple formats: .png, .jpg, .jpeg, .gif, .bmp, .tiff, .webp, .svg
  * Cross-Platform: Works on Windows, Linux, and macOS.
    
### INSTALLATION
     git clone https://github.com/0xbitx/DEDSEC_IMGWARE.git
     cd DEDSEC_IMGWARE
     chmod +x dedsec-imgware
     ./dedsec-imgware

     or 

     sudo apt install ./dedsec-imgware.deb
     dedsec-imgware

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu

## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**
   
<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>
