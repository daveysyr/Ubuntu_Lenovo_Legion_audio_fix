# Ubuntu_Lenovo_Legion_audio_fix
This is what worked for me to get the audio working with Ubuntu 24.10 on a Lenovo Legion Pro 7 16IRX9H Intel® Core™ i9-14900HX × 32

Initial install had the login splash sound working OK, but the audio in youtube and other sources wasn't working.  The audio was visible visually within the system (e.g. sound level meter) but there was no output from the speakers.  I know that the speakers work OK because there is a login splash sound, which played really nicely, but then no audio from within apps.

The output is from a few hours of trying various things via Chat GPT and finally getting it all working more by luck/trial error than skill.

Finally, once the fix is applied, the first boot seems to take a couple of minutes.  Subsequent boots are much faster.  I analysed the blame file on the slow and the faster boots and the first boot seemed to be scanning the audio options, but subsequent boots didn't seem to do this, or certainly didn't take as long to do it.

You should have boot sound after the fix and also audio from Firefox/VLC/etc should work OK.

Please test fully - speakers, headphones, HDMI and let me know if it worked on your machine.
