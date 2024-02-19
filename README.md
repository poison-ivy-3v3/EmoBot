#            Emo
# Your Personal Companion Robot

Forked from CodersCafeTech.  With some additional instructions/fixes.

Using a default Raspberry Pi OS (Bullseye Full, 64-bit) clone the "EmoBot" project into the Desktop/ directory.

Enable interfaces on the Pi with:

   - sudo raspi-config

'Interface Options' > 'I2C' > Ensure it's enabled.

'Interface Options' > 'SPI' > Ensure this is enabled also.

'Advanced Options' > 'Expand the file system' > Expand the filesystem and reboot.

Install dependencies:

   - pip3 install adafruit-circuitpython-servokit RPi.GPIO spidev Pillow

Download some .wav files and add them to a new directory called /home/pi/Desktop/EmoBot/sounds/ and name them:

   - happy.wav
   - angry.wav
   - excited.wav
   - sad.wav

Launch the python script that brings your robot to life:

   - python3 final.py
