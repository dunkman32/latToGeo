# latToGeo.js

LatToGeo library created for translate Latin/English characters to Georgian (Mkhedruli)

#Installation

Using npm:
```shell
npm i --save lattogeo
```
Using npm:
```shell
yarn add lattogeo
```

#Example

```js

import latToGeo from 'lattogeo'

const translate = () => {
    const lat = 'romelman Seqmna samyaro Zalita miT Zlierita'
    console.log(latToGeo(lat)) // რომელმან შექმნა სამყარო ძალითა მით ძლიერითა
}

translate()

```
