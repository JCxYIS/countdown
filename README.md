# countdown
> 爆炸倒數：很無聊很簡單的純 html 小專案，但很好玩。

![](https://i.imgur.com/e8g7ppv.jpg)

## Usage
https://jcxyis.github.io/countdown

You can combine the url with the parameters below to setup your own countdown, for example, 

https://jcxyis.github.io/countdown?time=2023-04-06T00:00&title=期中考爆炸倒數&titlePassed=期中考已爆炸&bg=linear-gradient(135deg,rgb(57,197,187),rgba(222,233,57))&bgPassed=url(https://i.imgur.com/ZYhVmDs.png)50%%2050%/cover&color=white&colorPassed=gray



## Parameters

### `time`
- 目標時間
- default: `2024-01-01T00:00:00`

### `title`
- 倒數時的說明文字
- default: `距離 2024 還有`

### `titlePassed`
- 倒數完的說明文字
- default: `歡迎來到 2024`

### `color`
- 倒數時的字體顏色
- default: `#ff1111` or `%23ff1111` in URL (red color)

### `colorPassed`
- 倒數完的字體顏色
- default: (same as `color`)

### `bg`
- 背景格式
- 對應 css [background](https://developer.mozilla.org/en-US/docs/Web/CSS/background)
- e.g.
    - `url(https://i.imgur.com/RKamJ5G.jpg) 50% 50% / cover`
    - `linear-gradient(135deg,rgb(57,197,187),rgba(222,233,57))`
- default: `black`

### `bgPassed`
- 時間到了以後的背景格式
- default: (same as `bg`)

### `overflow`
- 時間到了以後是否要改為正計時，否則維持 00:00:00
- default: `true`


## Embed
```html
<iframe 
    width="600"
    height="160" 
    style="border: 0;" 
    src="https://jcxyis.github.io/countdown?">
</iframe>
```

e.g. embed in hackmd

![embed in hackmd](https://i.imgur.com/PWQpsmd.png)
Demo: https://hackmd.io/-gNpgxaWTMWteZox8USIEw?both
