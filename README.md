# Virtualization-of-radio

To run this project. Please do the following steps:

First install gnu-radio (https://github.com/gnuradio/gnuradio.git).

Then build signal processing blocks (https://github.com/gnuradio/gr-tutorial) for FBMC-frame extractor and fbmc sample collector. 
The code for these is shown in the repository.

To Sense the Spectrum. Run the following command.

Sudo python Spectrum_Sensing.py –aXG –bYG –g45 –d8 > rx.dat 

--where X and Y represents the frequency band, and the log file will be generated in your directory with name "rx.dat".

For further queries feel free to ask. (maliksaad84@gmail.com)
