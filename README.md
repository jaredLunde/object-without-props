`yarn add object-without-props` or `npm add object-without-props`


## Usage
```js
import objectWithoutProps, {objectWithProps} from 'object-without-props'


const objectA = {foo: 'bar', bar: 'baz', baz: 'boz'}
const objectB = {foo: null}
const objectC = ['bar']

objectWithoutProps(objectA, objectB, objectC)
// {baz: 'boz'}

objectWithProps(objectA, objectB, objectC)
// {foo: 'bar', bar: 'baz'}
```
