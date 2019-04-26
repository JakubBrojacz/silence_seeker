# Silence_seeker

Silence_seeker is a bash script for detecting flat lines / signal drop in wav files

## Usage

```bash
silence_seeker infile1 infile2 ...
```

## Input files

Silence_seeker accepts only WAV Mono files with sampling rate of 16kHz

## Output

For each input file script prints:
```
[ file_name ][ valid ]
```
*or*
```
[ file_name ][ invalid ][ index_of_first_dropped_sample ]
```
and generates appropiate visualization of audio signal to file 
```
file_name.png
```
