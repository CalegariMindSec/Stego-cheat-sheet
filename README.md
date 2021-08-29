# **Stego cheat sheet**
***

## **TOOLS**
***

### 1 - Steghide

#### **Description:**

Steghide is a steganography program that hides data in various kinds of image and audio files , only supports these file formats : JPEG, BMP, WAV and AU. It’s also useful for extracting embedded and encrypted data from other files.

#### **Easy install:**

`sudo apt install steghide`

#### **Useful commands:**

`steghide extract -sf file` --> Extract data from a file

`steghide info file` --> Displays information about whether there are embedded files or not
***

### 2 - Zsteg

#### **Description:**

Detect stegano-hidden data in PNG & BMP

#### **Easy install:**

`gem install zsteg`

#### **Useful commands:**

`zsteg -a file` --> Run every detection method on the file

`zsteg -E PAYLOAD file` --> Extract specified payload
***

### 3 - Exiftool

#### **Description:**

ExifTool is a free and open source software program for reading, writing and manipulating image, audio, video and PDF metadata.

#### **Easy install:**

You can find an easy install [here](https://exiftool.org/install.html)

#### **Useful commands:**

`exiftool file` --> Show file metadata
***

### 4 - Stegoveritas

#### **Description:**

Capable of a wide variety of simple and advanced tricks, this tool can check file metadata, create transformed images, brute force LSB, and more.

#### **Easy install:**

`pip3 install stegoveritas`

#### **Useful commands:**

`stegoveritas -meta file` --> Check file for metadata information

`stegoveritas -extractLSB file` --> Extract LSB data from the image
***

### 5 - Sonic Visualizer

#### **Description:**

Spectrogram stegonography is the art of hiding an image hidden within the spectrogram of an audio file. So whenever it comes to audio stego, it's always worth analyzing the audio spectrogram. To do this, we use Sonic Visualizer.

#### **Easy install:**

You can find an easy install [here](https://www.sonicvisualiser.org/download.html)
***

## Recommendation

There are many stego tools on the internet, but here I've put the ones I consider to be the main ones. If you want to learn more about these tools, I recommend making [this](https://tryhackme.com/room/ccstego) free room on TryHackMe. 
