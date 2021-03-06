# CFD background stimuli generation

This code takes input images from the [Chicago Face Database](https://chicagofaces.org/) (which must have had their backgrounds rendered transparent from the original white).
It then combines them (in all possible ways) with some pre-set backgrounds to create stimuli that have a person in the foreground and a specific environemnt in the background .


Please fill in the directories in `directories.py`.

To run with a ratio of, e.g., 0.17 send the `-r` flag followed by `0.17`:
```
python create_stimuli.py -r 0.17
```

Once the script has run, the stimuli will be in the directory you have chosen along with a CSV file: `stimuli.csv`, which contains useful details per stimulus. 


The author of this code repository is Dr. Olivia Guest and this work was conducted under the joined research collaboration with the Transparency in Algorithms Group of the CYENS Centre of Excellence, Nicosia, Cyprus. The primary active repository is originally published in https://github.com/oliviaguest/CFD-backgrounds.
