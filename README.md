# Basic Explications 
![react-toolbox](https://img.shields.io/badge/react_toolbox-v.0.7.2-brightgreen.svg)
![react-toolkit](https://img.shields.io/badge/ui_toolkit-v.0.1.6-yellow.svg)

## What is this ?

One short sentence to know if I am looking for the ting I am looking for. Seems useless ? Of course not ! 
Maybe we can use tags.

## When/Why do I uses this thing

* A guy
* B guy

# How to use it ?

* [A thing](#link-to-A)
* [B thing](#link-to-B)
  * [Sub A thing](#link-to-A-1)
* [C thing](#link-to-C)

## Usage 1 template

What to start with ? 
Exemple : Start by defining the endpoints of your API.

```js
import { thing } from 'src/url/to/component';

const apiEndpoints = {
  doThings: { 
	  option1: 'value', 
	  option2: 'value' 
  },
};
```

Next step. 
Exemple : You can then perform API requests like this:

```js
thing.method()
.then((result) => {
	//Things
})
.catch((error) => {
	//Other things
});
```

## Attributes

### Arguments / attributes list

`dirty : boolean`\
<details>
<summary>Returns `true` if values are not something from initial values, `false` otherwise.</summary>
<br>
Est sequi tegenda excusatione ire modo curae sequi est est consensio consensio ut aliquando amicitiae est vel bellum sit futurum futura sequi futurum est vel.
</details>

`options : object`\

<details>
<summary>Returns `{}` if values are something from initial values, `null` otherwise.</summary>
<br>
De te esse Epicuri video ita instructior probo quas aut De artibus vellem De deterruisset doctrinis tenent cetero cetero probo vellem inquam est deterruisset qui.
</details>

### Examples

```js
thing.doThing({ id: 12 })
// To do this : this works this way.

thing.doThing({ id: 12, include: 'comments' })
// To do this : this works this way.

thing.doThing({ options: { option1: 'opt', option2: { ... }}})
// To do this : this works this way.

thing.doThing({ id: 12 }, { options: { option1: 'opt', option2: { ... }}})
// To do this : this works this way.
```

### General information

Block about general things or with other important information.
Exemple : By default, this is following headers :

```
Content-Type: application/awesome-developer
Accept: application/you-in-fact
```

If you need to pass additional blabla, you can use the `configureBlabla` option:

```js
import something from './Something';

const config = {
  configureBlabla(value) {
    return {
	    // I Hope something
    };
  },
};
```

### Something Else

Informations.

```js
code();
```
More informations and details.
