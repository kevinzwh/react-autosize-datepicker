# react-autosize-datepicker
==========================

react-autosize-datepicker combines the simplicity of react-datepicker &
react-input-autosize in one easy to use component.

## Installation

To start using react-autosize-datepicker, install it from NPM by running the
following command:

```
npm install --save react-autosize-datepicker
```

## Usage

react-autosize-datepicker renders a DatePicker component with an InputAutosize
component as its input field.

Since react-autosize-datepicker is derived from react-datepicker by hackerone,
you can refer to their documentation here for further details on customizing
your datepicker: [react-datepicker
docs](https://hacker0x01.github.io/react-datepicker/)

You can also refer to react-input-autosize by Jed Watson for further details on
the input field itself: [react-input-autosize
docs](https://github.com/JedWatson/react-input-autosize)



```es6
import AutosizeDatePicker from 'react-autosize-datepicker'

<AutosizeDatePicker
  selected={ this.state.startDate }
  onChange={ this.handleChange }
  dateFormat="YYYY/MM/DD"
  placeholder="Select a date"
  placeholderIsMin
/>
```
