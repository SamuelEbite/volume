# Audio Volume Modifier

This program modifies the volume of an audio file by a given factor. It takes in three command-line arguments: the name of the input file, the name of the output file, and the scaling factor.

Getting Started

To use this program, compile the code and run the resulting executable with the following command-line arguments:

bash
Copy code
./volume input.wav output.wav factor
Here, input.wav is the name of the audio file to modify, output.wav is the name of the resulting modified file, and factor is the scaling factor to apply to the audio data.

Implementation Details

The program reads in the audio data from the input file and applies the scaling factor to each sample. The modified audio data is then written to the output file. The header of the input file is also copied to the output file to preserve any metadata or formatting information.

The audio file must be in the .wav format, and the header of the input file must be exactly 44 bytes long. If the input file is not in the correct format or cannot be opened, the program will terminate with an error message.

License

This program is licensed under the MIT License. See the LICENSE file for details.
