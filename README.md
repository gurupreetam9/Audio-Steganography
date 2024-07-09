# Audio-Steganography
APSSDC Project for Cyber Security with Kali Linux on Audio Steganography.

#README

1)Your audio file should be in '.wav' format. If it is in '.mp3' format you can convert it to '.wav' in 
       --> https://www.freeconvert.com/mp3-to-wav .

2)After Converting to '.wav' you need to check Channels, Sample Width(bytes), Sample Rate(Hz). 

  --> Verify the Properties:

     Channels: It should be 1 (for mono audio).
     Sample Width: It should be 2 (for 16-bit audio).
     Sample Rate: It should be 44100 Hz (standard for audio).

  --> Even if your audio file has different properties, don’t worry—I’ve included an option in my code to convert the properties as required for encryption.

3)Once the program prompts “Your file is ready for Encryption,” proceed to encrypt your audio file.

4)After successful encryption, you’ll receive a confirmation prompt: “Data hidden successfully…”

5)To decrypt the file, use the “Decryption.ipynb” script. You can retrieve the hidden text within the audio file using the provided passcode.
 
