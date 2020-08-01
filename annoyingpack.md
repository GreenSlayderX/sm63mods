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
`SEED` - a string containing 20 values, separated by "|" characters; every character with an even index number (first, third, fifth, seventh, ninth etc.) is a `1` or `0` and corresponds to a certain advert. If the value is `1`, that advert will be able to appear. Following that number is a "|", then three characters `xxx`, which represent the chance (0% to 100%) for that certain advert to appear every time a random advert is queued to appear. Advert designs:

Advert #1: First 5 characters (`x|yyy|`), design: <link1>

Advert #2: Characters 6-10 (`x|yyy|`), design: <link2>

Advert #3: Characters 11-15 (`x|yyy|`), design: <link3>

Advert #4: Characters 16-20 (`x|yyy|`), design: <link4>

Advert #5: Characters 21-25 (`x|yyy|`), design: <link5>

Advert #6: Characters 26-30 (`x|yyy|`), design: <link6>

Advert #7: Characters 31-35 (`x|yyy|`), design: <link7>

Advert #8: Characters 36-40 (`x|yyy|`), design: <link8>

Advert #9: Characters 41-45 (`x|yyy|`), design: <link9>

Advert #10: Characters 46-49 (`x|yyy`), design: <link10>
  
<b>Please always include 49 characters in the SEED string and only use numbers and the "|" in the format stated above. The mod will behave unexpectedly if you do not adhere to these conventions. In addition, if you disable an advert, please set it's chance to 000.</b>

Examples:

`1|010|1|010|1|010|1|010|1|010|1|010|1|010|1|010|1|010|1|010` - Default seed.

`1|020|0|000|1|020|0|000|1|020|0|000|1|020|0|000|1|020|0|000` - Second, fourth, sixth, eighth and tenth advertisments are unable to appear.

`1|050|1|050|0|000|0|000|0|000|0|000|0|000|0|000|0|000|0|000` - Only the first two adverts can appear.


### Lagback
WIP
