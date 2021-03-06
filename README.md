# react-native-swipeout
iOS-style swipeout buttons that appear from behind a component
![swipeout preview](http://i.imgur.com/oCQLNFC.gif)

## Installation
```
npm install --save react-native-swipeout
```

## Usage example

note: see example/index.ios.js for more detailed example

```
var Swipeout = require('react-native-swipeout')

// Buttons
var swipeoutBtns = [
  {
    text: 'Button'
  }
]

// Swipeout component
<Swipeout right={swipeoutBtns}>
  <View>
    <Text>Swipe me left</Text>
  </View>
</Swipeout>

```

## Props

Prop            | Type   | Optional | Default   | Description
--------------- | ------ | -------- | --------- | -----------
autoClose       | bool   | Yes      | false     | auto close on button press
backgroundColor | string | Yes      | '#dbddde' | 
left            | array  | Yes      | []        | swipeout buttons on left
right           | array  | Yes      | []        | swipeout buttons on right

##### Button props

Prop            | Type   | Optional | Default   | Description
--------------- | ------ | -------- | --------- | -----------
backgroundColor | string | Yes      | '#b6bec0' | background color
color           | string | Yes      | '#ffffff' | text color
component       | string | Yes      | null      | pass custom component to button
onPress         | func   | Yes      | null      | function executed onPress
text            | string | Yes      | 'Click Me'| text
type            | string | Yes      | 'default' | default, primary, secondary

## To Do

[https://github.com/dancormier/react-native-swipeout/issues](https://github.com/dancormier/react-native-swipeout/issues)