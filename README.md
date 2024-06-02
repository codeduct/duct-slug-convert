## using duct-slug-convert

Text to Url Slug conversion tool

# Demo 
https://codeduct.com/duct-slug-convert

## duct-slug-convert setup

#### npm
```
npm i duct-slug-convert
```

Add the duct-slug-convert package in the component you want to use after installation.

```Javascript
import slug from 'duct-slug-convert'
```
ready to use

Example 1
```Javascript
const convert = slug('String');
```
Example 2
```Javascript
{{ slug('String') }}
```
The value sent to the slug function is converted to a url and returned as a value.