# HuntHelper-Resources
Images for HuntHelper

Dawntrail data can be viewed at: https://ireallywanttostayatyourhou.se/dawntrail


ARR-EW Images from: [cablemonkey.us/huntmap2/](!)  
Credit to Cable Monkey @ Goblin

<details>
    <summary>note to self - how to find map images</summary>
  
  saintcoinach cmd:  
  
  ```
  image ui/map/f1f1/00/f1f100_m.tex
  ```


is the map tex for central shroud. 

-> TerritoryType-> Name XivString	: f1f1   

-> Map		-> Id XivString		: f1f1/00

Hunt / open world maps seem to be   
````
7: SizeFactor: 100
````

then somehow you have to know to append

	- _m.tex for full size (2048x2048)
	- -s.text for half size ?

and the subfolder format ui/map/{id}/{id but without slashes} ...

this stuff isn't well documented...

godbert or spreadsheets helpful with assisting + saintcoinach

</details>
