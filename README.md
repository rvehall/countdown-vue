# countdown-vue
A simple countdown timer component for VueJS 2.

![screenshot](https://raw.githubusercontent.com/getanwar/vuejs-countdown/master/scr.png "Vue JS Countdown")

## Installation
#### npm

`npm i countdown-vue --save`


## Usage

```html
<template>
  <div>
    <Countdown end="August 22, 2022" showDays showHours showMinutes showSeconds endFunc="func"></Countdown>
    or 
    <Countdown end="2018-03-16T00:42:24.000Z" showDays showHours showMinutes showSeconds endFunc="func"></Countdown>
  </div>
</template>
```

```javascript
<script>
import Countdown from 'countdown-vue'

export default {
  components: { Countdown }
}
</script>
```

The only prop that is required is ```end```.

## Other Config

You can stop the countdown timer anytime by passing back `stop` props.


### Based on [gentanwar's](https://github.com/getanwar/vuejs-countdown) plugin
