# wordlists
Very small wordlist including the most popular fist names (from 1970-2022) in Germany.

The list contains each name in upper- and lowercase (```Maria``` / ```maria```).

Had some nice results with combination attacks ```hashcat -a 1 (...)```

I usually shuffle alphabetic wordlists before I run them against big hashfiles
```plain
sort -R GER-Firstnames_1970-2022.dict > GER-Firstnames_1970-2022RDM.dict
```
Good luck!
