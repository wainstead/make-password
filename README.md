# make-password

Small Ruby script to generate random passwords in the vein of "correct
horse battery staple" using the EFF's dice word list.

See [EFF Dice-Generated Passphrases](https://www.eff.org/dice) and the
obligatory [XKCD](https://xkcd.com/936/) comic.

Usage: `ruby make-password.rb [number of words] [number of passwords]`

Example:
```
# Default: one password, five words long
$ ruby make-password.rb
frequent impulsive series step tapioca 

# Three words, six passwords
$ ruby make-password.rb 3 6
democracy jailbird pavement 
mace mankind prankish 
caucus composer providing 
bonus cofounder villain 
expansive twilight unskilled 
majesty overdrive raging 

# Two words, ten passwords
$ ruby make-password.rb 2 10
outpost unroll 
borax bouncing 
implosion tidings 
babbling outcome 
moonscape reaction 
driven obligate 
encrypt paycheck 
halt thieving 
parsnip video 
onset spotty 

```

Sometimes the suggested passwords can be quite evocative. Run the
script many times to find something you like and is memorable.


