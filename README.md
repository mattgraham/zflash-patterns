# zflash-patterns
This is a collection of z-flash patterns for thezflash.com module. 1_lightshow.cls - 6_lightshow.cls are the default patterns that come with the module as it ships in October of 2021. 

Feel free to share your custom patterns via pull request and if possible an animated gif of the pattern. ie 

```
patternName_version.cls
patternName_front.gif
patternName_back.gif
```

## CLS Files
The files seem to be a fancy text document with the following, unverified methods:

```
STATE|POSITION
(ie 32 = Third Break On)

State:
0 - OFF
1 - OFF
2 - ON
3 - ON

Position:
2: Third Break
3: Left Front Low Beam
4: Right Front Low Beam
5: Left High Low Beam
6: Left High Low Beam
7: Left Front Turn
8: Right Front Turn
9: Left Rear Break
A: Right Rear Break
B: Both Fog Lights
C: Both Reverse Lights
D: Left Rear Turn
E: Right Rear Turn
F: Left Front Fog
0: Right Front Fog
```
