
## npm i --save loadlazy
Lazyload image Library
Create Lazyload Gallary with loadlazy

## Features
 -Create Lazyload image gallary

 

## Command - Lines And Usage
```javascript
npm i --save loadlazy
```
  

## API:collision:

  

```javascript
import  Image  from  'loadlazy';
```


  
#### Create Gallary With loadlazy

```javascript
import React from 'react';
import { render } from 'react-dom';
import  Image  from  'loadlazy';
const imageTags = [
'water','snow','fire','rain','cat','dog','horse','lion','tiger','field','tree','palm','island','people','hand','world','temple',
'paris','rome','madrid','lisboa','berlin','food','drink',];
const Myimage = () => (
	<div style={{display: 'grid',gridGap:'20px',gridTemplateColumns: 'repeat(auto-fit, minmax(200px, 1fr))'}}>
	  {imageTags.map((item, index) => (
		<div style={{ height: '200px', overflow:'hidden',backgroundColor: '#eee' }} key={index}>
			<Imagekey={index}src={`https://source.unsplash.com/random/300x300?${item}`} style={{ width: '100%' }}/>
	 </div>
))}
</div>
);
export default Myimage;

```


## Authors and Acknowledgment
[Mayank Pandav](https://github.com/mayankpandav)



  

