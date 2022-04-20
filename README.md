# mapbox-gl-draw-rectangle-mode-cdn

![mapbox-gl-draw-rectangle-mode](https://img.shields.io/badge/mapbox--gl--draw--rectangle--cdn-v1.0.4-%23C50008?logo=npm)
![mapbox-gl-draw-rectangle-mode-cdn](https://img.shields.io/badge/mapbox--gl--draw--rectangle--mode--cdn-v1.0.0-%23C50008?logo=npm)
[![blog](https://img.shields.io/badge/blog-yesifang.com-orange?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABjFBMVEUAAAAIAQUiBhQVBA05CyK0I2z4MJTgKoV8GEoKAgZyFkT8MZfTKX4dBRFWEDP9MZfMJ3kGAQQHAQTlK4htFUEAHRMATDAAbUQAf1EAh1QAgFAAbUUATDAAHhNMDy7KJngAeUsAKBp9GEr4MJMDAQIAmWEAWzkABAOGGlD9MZYAcUgABQNoFD7mLIoAZUCdHl4ANiKiH2EpCBgAh1UAAgERAwrVKH9nFD0ALBwSAwuqIWXmK4pTEDIAWTgrCBp2F0eVHVmKG1NWETMAdEgAgVAAAQIAJTcATXIAZJQAbqUAap0AVoEAfE4AAQEAN1EAgMAAaEIACQ4Aap4ARiwACQ0AebMAmV8AEwwAAAAAZ5oAZT8AMkkAkFoAEQsAebMAl14AGCQAkl0ALx4AOlYAeEsAGRAATHAAbkUAll0All4AbkYAMB4ATXMABwQAIxYANiIAPicANyIAJBYAQF4AIjIAis0AAgMAhsYAZJYARWYAk9oAHy4ABQcAfbkAO1gAis3/MZgAmmEAld3///8EabibAAAAgHRSTlMACCIVObX54XwKcv3UHVb+zQYH5m0xfrTU4NW1fzJMy8hDffkD/pcHh/69CGjnqJ5ZoynfBBHWZ0kSqudTlCt2lotWwNUCQIOrvrWVzwFe3a4QtnQPz/0gAbKnVe4c0Psp9E9jximBtvj4t0+FCzpaZlo7bTruA+Wtdfs1CNdm7ZpKyEIAAAABYktHRIP8tM/SAAAAB3RJTUUH5QoVBh0NInrzjgAAATtJREFUOMt902VbwzAUBeDLcAYMhru7uzPcXYcP1+EyPMkvZ03TNk0TztfzNnL7BECeCFck/JOo6BiEYuPiVX2CG9EkJsn7ZA9iSUmV9d40ZCYdICMzKzsnNy+/wASFVo+KALCR4hIGSjlQVm4BXFFZRUE1B2q8HMC4tk4D9RxoABvAjRpwuS3QJADcrIkW6witImhrD4OOTtZ7ukAEuFtboqeXjqqvH5xgQL/qoG9oeET/FQIYdQxWAGNmMT4xOTU9MyuCOVbPLywSGhEs6f3yCiFysEr7tXWiABubWu/fIiqwTRfYISqwu0fBvgoc0DlCgCjA4ZF+hWMFODllMzizgfML2l5eXfuNGd7YAARv7+4fHoPc9J/swJlnrn+Rgdc3C4SkT+vd7D8+peDr2+h/FK838Ev3D4W//wNiKCWwWalJAwAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMS0xMC0yMVQwNjoyOToxMyswMDowMP1Zb/cAAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjEtMTAtMjFUMDY6Mjk6MTMrMDA6MDCMBNdLAAAAAElFTkSuQmCC)](//yesifang.com)

> 这是一个mapbox-gl-draw-rectangle-mode的cdn支持版本。
>
> This is a cdn-supported version of mapbox-gl-draw-rectangle-mode.
<div align="center">
  <a href="https://nodei.co/npm/mapbox-gl-draw-rectangle-mode-/"><img src="https://nodei.co/npm/mapbox-gl-draw-rectangle-mode.png?downloads=true&downloadRank=true&stars=true"></a>
</div>
<div align="center">
  <a href="https://nodei.co/npm/mapbox-gl-draw-rectangle-mode-cdn/"><img src="https://nodei.co/npm/mapbox-gl-draw-rectangle-mode-cdn.png?downloads=true&downloadRank=true&stars=true"></a>
</div>

## Run Simple Demo

```shell
$ git clone https://github.com/SuperYesifang/mapbox-gl-draw-rectangle-mode-cdn.git
$ cd mapbox-gl-draw-rectangle-mode-cdn
$ npm run serve
```



## Usage

### 1. Use CDN

```html
<script src="https://raw.githubusercontent.com/SuperYesifang/mapbox-gl-draw-rectangle-mode-cdn/master/dist/DrawRectangleMode.cdn.js"></script>
<script>
	console.log(DrawRectangleMode);
</script>
```

### 2. Use ESM

```js
import MapboxDraw from "@mapbox/mapbox-gl-draw";
import DrawRectangleMode from "mapbox-gl-draw-rectangle-mode-cdn";
const draw = new MapboxDraw({
	modes: {
		...MapboxDraw.modes,
		draw_rectangle: DrawRectangleMode
	}
});
map.addControl(draw);
```