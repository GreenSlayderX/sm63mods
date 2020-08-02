# Annoying Package
### Features
- Advertisments that pop up on your screen and cannot be closed!
- Lagback! Mario will occasionally & randomly teleport behind to where he was some time ago!
### Usage
1. Load in this code in the level title using a text editor (Notepad, Wordpad, Word Document): `code is here`
2. To use all the features at default settings, write `//ANNOY:ALL` in a sign. Mario will lagback, get advertisments posted on the screen, <more>.
3. For individual features & changing settings, keep reading.

### Advertisments
`//ANNOY:ADS SEED:<seed> MINDELAY:<mindelay> DELAYRANGE:<delayrange>`

`SEED` - a string containing 10 values, separated by "|" characters; every value represents the chance for that specific advert to appear. The seed looks like `a|b|c|d|e|f|g|h|i|j`, where `a` is the chance for the first advert to appear (advert designs listed below), `b` is the chance for the second advert to appear, and so on. Advert designs:

Advert #1: <design>

Advert #2: <design>
  
Advert #3: <design>
  
Advert #4: <design>
  
Advert #5: <design>
  
Advert #6: <design>
  
Advert #7: <design>
  
Advert #8: <design>
  
Advert #9: <design>
  
Advert #10: <design>
  
<b>Please only use numbers and the "|" separator when defining the SEED string. The mod will behave unexpectedly if you do not adhere to these conventions. In addition, make sure the sum of the chances is 100; if it is under or above 100, some adverts may be unable to appear.</b>

Examples:

`10|10|10|10|10|10|10|10|10|10` - Default seed.

`20|0|20|0|20|0|20|0|20|0` - Second, fourth, sixth, eighth and tenth advertisments are unable to appear.

`50|50|0|0|0|0|0|0|0|0` - Only the first two adverts can appear.

`99|1|1|0|0|0|0|0|0|0` - Only the first two adverts can appear; the third advert has an above-0 chance, but cannot appear because the sum of changes is over 100.

`99|0|0|0|0|0|0|0|0|0` - Either the first advert appears 99% of the time, or nothing will appear at all.

`MINDELAY` - the minimum delay between each time a random advert is queued. Default: 500

`DELAYRANGE` - a random number between 0 and this number is selected and added to the MINDELAY value; the final delay will be the resulting sum. Default: 150

<b>Examples:</b>
`//ANNOY:ADS SEED:20|0|20|0|20|0|20|0|20|0 MINDELAY:550 DELAYRANGE:150` - The first, third, fifth, seventh or ninth delay appears every 550-700 frames.
### Lagback
WIP
