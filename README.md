# DnD-characters
Crowdsourced dataset of character names from Dungeons &amp; Dragons players
Via Aiweirdness.com

Dataset crowdsourced via google form between September 15 2017 and May 1 2018.
Number of entries: 18,928 (unfiltered; duplicates not removed)

Original fields: 
"Character name"
"Character race (human, orc, halfling, etc)"
"Character class (wizard, bard, cleric, etc)"

Also included in the dataset: 1,980 crowdsourced character names, races, and classes from an ongoing collection of D&D character bios

output.txt : 100MB of generated character names, races, and classes from a char-rnn ( github.com/karpathy/char-rnn ) trained for 3.8 epochs on the input.txt dataset. Training parameters: -rnn_size 512 -num_layers 3 -seq_length 30 -dropout 0.0

Dataset will be posted when the blog post goes live at AiWeirdness.com this week
