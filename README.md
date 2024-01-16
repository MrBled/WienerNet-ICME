# Anonymous ICME 2024 WienerNet Suppl. Mat.
Here we present denoised image sequences as well as single frames examples.

## Denoised Videos.
We present three scenes for each noise level. Each scene contains the following sequences:
1. The original sequence.
2. The noisy sequence.
3. Denoised using FastDVDNet.
4. Denoised using our non-blind denoiser (WienerNet NonBlind)
5. Denoised using our blind denoiser (WienerNet Blind)
6. Denoised using our blind denoiser and deepflow motion compensation (WienerNet Blind + MC) 

### Video Links
[MP4 Sequences: NOISE STD = 20 (Anonymous MS Sharepoint)](https://1drv.ms/f/s!AhKO8wUz4hy9iBGgcWsWB9JllTYs?e=USQnCp)\
[MP4 Sequences: NOISE STD = 40 (Anonymous MS Sharepoint)](https://1drv.ms/f/s!AhKO8wUz4hy9iBUXaBORpTL4K_FI?e=jGXHfm)\
**Note:** Please download and view the sequences in full quality outside of sharepoint.
# Single-Frame Examples
Uncompressed, single frame examples at Gaussian noise levels of STD=20 and STD=40. All examples have been denoised using WienerNet Blind.
## WienerNet Denoised Frame Samples at sigma=20
Ground-truth\
![](samples_sig20/GT_00000010.png)\
Noisy PSNR: 22.34 dB\
![](samples_sig20/NOISY_00000010.png)\
Denoised PSNR: 30.40 dB\
![](samples_sig20/00000010_denoise.png)\
Ground-truth\
![](samples_sig20/GT_00000010ham.png)\
Noisy PSNR: 23.57 dB\
![](samples_sig20/NOISY_00000010ham.png)\
Denoised PSNR: 35.56 dB\
![](samples_sig20/00000010_denoiseham.png)\
Ground-truth\
![](samples_sig20/GT_00000010mar.png)\
Noisy PSNR: 22.60 dB\
![](samples_sig20/NOISY_00000010mar.png)\
Denoised PSNR: 34.03 dB\
![](samples_sig20/00000010_denoisemar.png)


## WienerNet Denoised Samples at sigma=40
Ground-truth\
![](samples_sig40/GT_00000010.png)\
Noisy PSNR: 16.64 dB\
![](samples_sig40/NOISY_00000010.png)\
Denoised PSNR: 27.39 dB\
![](samples_sig40/00000010_denoise.png)\
Ground-truth\
![](samples_sig40/GT_00000010ham.png)\
Noisy PSNR: 17.73 dB\
![](samples_sig40/NOISY_00000010ham.png)\
Denoised PSNR: 32.75 dB\
![](samples_sig40/00000010_denoiseham.png)\
Ground-truth\
![](samples_sig40/GT_00000010mar.png)\
Noisy PSNR: 17.11 dB\
![](samples_sig40/NOISY_00000010mar.png)\
Denoised PSNR: 31.13 dB\
![](samples_sig40/00000010_denoisemar.png)

