


# aframe-open-page-iframe.js

Component add ability to open page url in iframe, 
with switching view context, without page reload.

## Properties
| Property  | Default | Required | Description |
| --------- | ------- | -------- | ----------- |
| `event ` | `click`  | **true** |event on entity, when process functional (can be filled with all js events on element)
| `url`  | ` `  | **true** |page url to open in iframe

## Example

[Demo Website](https://demo.inplayo.com/aframe/switch-vr-and-page/)

```html
<a-entity open-page-iframe="url:https://inplayo.com/;event:click;"></a-entity>
```

### Demo video

[![Demo Video](https://img.youtube.com/vi/GwYH4lUYU_8/0.jpg)](https://www.youtube.com/watch?v=GwYH4lUYU_8 "Demo Video")


### Demo using
* A-Frame 1.3.0
* Oculus Quest 2
* Google Chrome Version 102.0.5005.61 (Mobile + Desktop)
## Badges

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=0077b6">](https://github.com/SamKirkland/FTP-Deploy-Action)
