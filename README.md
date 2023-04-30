
# batch-tts
A bash script which uses edge-tts to output text-to-speech .mp3 files for all text files in a specified directory, with a specified extension. Automation job initialization as a background process is handled, and text-to-speech processing progress bars are provided as well.

## Installation

- Install [pip](https://www.python.org/downloads/) or [pipx](https://pypa.github.io/pipx/)
- Ensure that pip or pipx is in your system's `$PATH`
- Run terminal command: `pip install edge-tts` or `pipx install edge-tts`
- Download batch-tts script from repository
- Add batch-tts save directory or path to script itself to system `$PATH`, or have the path of its location prepared
- Ensure that your terminal has access to unix applications: tput, pv, sleep, mv, mkdir, echo, exit, and  the bash terminal. 

Please note that this was developed and tested on Archlinux, only!

## Usage

  If script is available in system's `$PATH`, run terminal command: `batch-tts <path/to/directory/containing/input/files> <input-format>`. If not, replace `batch-tts` with the path to the script. Outputted .mp3 files will then be located in a folder titled "audio-files" in the inputted directory, and all input files are moved to a folder titled "text-files" in the inputted directory.

## Demo

Please note that the following demo video is sped up to 10x speed.

https://user-images.githubusercontent.com/116528597/235375595-7ea9cd0c-00f0-4156-b9a3-012530489616.mp4

