# impress-step-timer

## Description
Adds a countdown timer to [impress.js](https://github.com/impress/impress.js) `.step` slides. When the slide becomes active the timer starts. When the slide becomes inactive the timer resets. 

## Installation with bower
```bash
$ bower install triglian/impress-step-timer
```

## Usage
Usage: 
Add a `data-timer` attribute to the steps that you want to have a timer. The value of the attribute should be the number of seconds to count down. 

Example:
```html
<!-- Count down 5 minutes -->
<div id="myslide" class="step" data-timer="300">
    <!-- slide contents go here -->
</div>
```

## License 
MIT

