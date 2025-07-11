# Audible Pacer Script
Whether you would like a metronome for music, for working out, or for any other task, you can use this free and open source shell script. The simple script will generate a `.mp3` based off parameters you define.
# Dependencies
- [ffmpeg](https://www.ffmpeg.org/)
- [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) (or a similar shell)
- [cURL](https://en.wikipedia.org/wiki/CURL) (only for the installation process below; the script may be copied instead)
# Installation
```bash
curl -O https://raw.githubusercontent.com/happy-heron/audible-pacer-script/refs/heads/main/audible-pacer-script.sh; chmod +x audible-pacer-script.sh
```
# Parameters
1. The name of the file that the script will create.\
  (Default: `workout`)
2. The number of seconds that will elapse before another beat occurs, e.g. 120 bpm would be `0.5`.\
  (Default: `3`)
3. The amount in seconds of audio to be generated.\
  (Default: `30`)
