<p align="center">
  <img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/060.png" width="100" title="hover text" alt="accessibility text">
</p> 

# POLYWAG :chart_with_upwards_trend:	
A data visualization library built on top of Plotly.js 
Current version : 0.0.1

This library provides fast and pre-built components to represent different kind of data in a clear and communicative way.

## API

See documentation at http://www.dvisionlab.com/polywag

## Installation

`yarn add polywag`

## Example

    let data = {
        value: [1,2,3,4,5],
        timestamps: [1598368228264, 1598368240796, 1598368248441, 1598368256295, 1598368263938]
    }

    let hm = new TimeseriesComponent("chart-container", { title: "A chart", color: "Viridis" };

    hm.update(data);
    
## Build docs

Create `template` folder into project root  
Clone docdash repo (http://clenemt.github.io/docdash/) into /template folder  
`yarn run generate-docs`

## Contributors

Mattia Ronzoni (https://github.com/ronzim)  
Simone Manini (https://github.com/daron1337)

![dvisionlab logo](https://www.dvisionlab.com/images/logo_dv.png)
