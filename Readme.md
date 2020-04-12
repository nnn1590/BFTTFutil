# BFTTFutil
A tool for encrypting\decrypting BFTTF\BFOTF from\to TTF\OTF

## Features
* __Encrypt TTF(TrueTypeFont)\OTF(OpenTypeFont) to BFTTF\BFOTF__
* __Decrypt BFTTF\BFOTF to TTF\OTF__
* __Platforms supported(for encryption obviously, you can run this only on mono): NX(Switch), CAFE(Wii U), WIN(MS Windows???)__

## Build
1. Install mono
2. Run `msbuild`
3. Done!

## Usage
`$ mono bfttfutil.exe mode infile outfile`

## Modes:
* __-enc_nx //Encrypts BFTTF\BFOTF for use with NX(Switch)__
* __-enc_cafe //Encrypts BFTTF\BFOTF for use with CAFE(Wii U)__
* __-enc_win //Encrypts BFTTF\BFOTF for use with WIN(MS Windows???)__
* __-dec //Decrypts BFTTF\BFOTF to a normal font__
