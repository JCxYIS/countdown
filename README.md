# countdown
> 爆炸倒數：很無聊很簡單的純 html 小專案，但很好玩。

## Usage
Visit https://jcxyis.github.io/countdown

You can combine the url with the parameters below to setup your own countdown, e.g.

https://jcxyis.github.io/countdown?time=2023-04-06T00:00&title=期中考爆炸倒數&titlePassed=期中考已爆炸&bg=linear-gradient(135deg,rgb(57,197,187),rgba(222,233,57))&bgPassed=url(https://i.imgur.com/ZYhVmDs.png)%200%200%20/cover&color=white&colorPassed=gray



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
- default: `#ff1111`  (red)

### `colorPassed`
- 倒數完的字體顏色
- default: (same as `color`)

### `bg`
- 背景格式
- 對應 css [background](https://developer.mozilla.org/en-US/docs/Web/CSS/background)
- e.g.
    - `url(https://i.imgur.com/RKamJ5G.jpg) 0% 50% / cover`
    - `linear-gradient(135deg,rgb(57,197,187),rgba(222,233,57))`
- default: `black`

### `bgPassed`
- 時間到了以後的背景格式
- default: (same as `bg`)




## Embed

```
<iframe 
    height="160" 
    style="width: 100%; " 
    src="https://jcxyis.github.io/countdown?">
</iframe>
```

<!-- embed in hackmd  -->