# BFTTFutil
A tool for encrypting/decrypting BFTTF/BFOTF from/to TTF/OTF

## Features
* Encrypt TTF(TrueTypeFont)/OTF(OpenTypeFont) to BFTTF/BFOTF
* Decrypt BFTTF/BFOTF to TTF/OTF
* Platforms supported(for encryption obviously, you can run this only on mono): NX(Switch), CAFE(Wii U), WIN(MS Windows???)

## Build
1. Install mono
2. Run `msbuild`
3. Done!

## Usage
`$ mono bfttfutil.exe mode infile outfile`

## Modes:
* `-enc_nx`		// Encrypts BFTTF/BFOTF for use with NX(Switch)
* `-enc_cafe`	// Encrypts BFTTF/BFOTF for use with CAFE(Wii U)
* `-enc_win`	// Encrypts BFTTF/BFOTF for use with WIN(MS Windows???)
* `-dec`		// Decrypts BFTTF/BFOTF to a normal font
