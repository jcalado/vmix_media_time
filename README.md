# vmix_media_time
Shows a bar with title, elapsed and remaining time for the media playing on a vmix instance.
When less than 5 seconds remain, timer flashes red.

## Screenshot
![image](https://user-images.githubusercontent.com/26873/186619058-7d1698cd-f244-4936-b2e2-41ab38adc27e.png)


## Options
URL params:

### Set the VMix hostname/ip to access its API:
`index.html?server=serverhost:port/api/`

### Set the update interval to 2000ms
`index.html?update=2000`

### Flash the timer red when 10s are left in the current media
`index.html?warn=10`

### Do not show the - indicator on the remaining time
`index.html?showMinusIndicator=false`

## Customization

Lines 14-20 are CSS variables that can be changed:

```css
--progress-height: 20vh;
--timer-font-size: calc(var(--progress-height) - 2vh);
--title-size: 6vh;
--progress-bar-color: #22c45d;
--progress-bar-bg: #41f280;
--title-text-colors: white;
--title-background-color: orange;
```



