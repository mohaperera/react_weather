# react_weather
small react weather component 

![Alt text](https://raw.githubusercontent.com/mohaperera/react_weather/master/react.PNG?raw=true "React Weather")

# React Weather
[![npm](https://img.shields.io/npm/v/npm.svg)](https://www.npmjs.com/package/react-weather)
![license](https://img.shields.io/badge/license-MIT%20License-green.svg)
 


## Features

 
- Supports Yahoo API
 



### Installing
Install via npm:
```
npm install react_weather --save
```


### Quick Example
This example shows how to use the GenericWeather component.
The component display static data via props.
``` javascript
import React, { Component } from 'react';
 
import Tempnow from 'react_weather';
const style = {
  height: 180,
  width: 220,
  margin: 20,
  textAlign: 'center',
  display: 'inline-block',
 
   backgroundColor: '#FBE9E7',
};
   <Tempnow location="Chicago"  style={style}  /> 
```

 

 
```

props:
  - location - The city name ,zip...etc
  - style 
 
### License
MIT

