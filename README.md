# formsy-react-components

[![Build Status](https://travis-ci.org/twisty/formsy-react-components.svg?branch=master)](https://travis-ci.org/twisty/formsy-react-components)
[![npm version](https://badge.fury.io/js/formsy-react-components.svg)](https://badge.fury.io/js/formsy-react-components)
[![GitHub release](https://img.shields.io/github/release/twisty/formsy-react-components.svg)](https://github.com/twisty/formsy-react-components/releases)
[![GitHub contributors](https://img.shields.io/github/contributors/twisty/formsy-react-components.svg)](https://github.com/twisty/formsy-react-components/contributors)

**NOTE! the master branch is the development branch, the [`release-0.x`](https://github.com/twisty/formsy-react-components/tree/release-0.x) branch has the source and README for the current `npm` release.**

`formsy-react-components` is a selection of React components that render form elements for use in a [formsy-react](https://github.com/christianalfoni/formsy-react) form.

The components render markup to be quickly included in a [Bootstrap 3 form](http://getbootstrap.com/css/#forms). This includes a `<label>`, [help text](http://getbootstrap.com/css/#forms-help-text), and some [validation styling](http://getbootstrap.com/css/#forms-control-validation) tied to formsy’s validation state and validation messages.

## Install

To install using `npm`:

```
npm install --save formsy-react
npm install --save formsy-react-components
```

## Browser Support

This should run on browsers where both [Bootstrap](http://getbootstrap.com/getting-started/#support) and [React](https://facebook.github.io/react/docs/react-dom.html#browser-support) are supported.

* *Internet Explorer:* polyfills for [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [Array.from](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/from?v=example#Polyfill) are required.

## Usage

```jsx
import { Form, Input } from 'formsy-react-components';

const MyForm = (props) => {
    return (
        <Form onSubmit={(data) => { console.log(data) }}>
            <Input
                name="firstname"
                label="What is your first name?"
            />
        </Form>
    )
}
```

## Examples

* See [examples](./examples/) for a overview on usage.

## Documentation

Documentation is a work in progress!

* For a working code example, visit the [Playground](http://twisty.github.io/formsy-react-components/playground/), then examine the [source](https://github.com/twisty/formsy-react-components/tree/master/examples/playground).
* There is some information in the [Wiki](https://github.com/twisty/formsy-react-components/wiki).
