<template>
  <body>
    <img class="background-image" src="public\background image.jpg" alt="" />
    <img class="Stall-image-green" src="public\Stall image green.png" alt="" />
    <img src="public\廠商 logo.jpg" class="-logo" />
    <img src="public\廠商首頁圖上傳圖.jpg" class="homepage" />
    <img src="public\上一頁按鈕.png" class="prevPageBtn" />
    <img src="public\廠商展品輪播圖.jpg" class="smallPic" />

    <div class="acrContainer">
      <img src="public\Acr image.png" class="Acr-image" />
      <img src="public\web.png" class="web" />
      <img src="public\email.png" class="email" />
      <img src="public\tel.png" class="tel" />
      <img src="public\fax.png" class="fax" />
      <img src="public\add.png" class="add" />
    </div>

    <div class="titleContainer">
      <span class="Text-Style"> 流亞科技股份有限公司 </span>
      <span class="subTitle"> Logic Art Automation Co., Ltd </span>
    </div>
  </body>
</template>

<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
}
body {
  width: 1920px;
  height: 1080px;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}
img.Stall-image-green {
  width: 1428px;
  height: 966.2px;
  margin: 0.2px 0 1px;
  padding: 57.6px 48.2px 39.8px 51.3px;
  object-fit: contain;
  position: absolute;
}
img.-logo {
  width: 124.9px;
  height: 81.9px;
  margin: 0 13.2px 253.3px 178.3px;
  object-fit: contain;
  position: absolute;
  top: 125.7px;
  left: 469.4px;
}
.Text-Style {
  width: 561.3px;
  height: 51px;
  margin: 9.3px 20.8px 15.5px 32.8px;
  font-family: MicrosoftYaHeiBold-GBpc-EUC-H;
  font-size: 41.7px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.33;
  letter-spacing: 8.35px;
  text-align: center;
  color: #333;
}
.subTitle {
  width: 563.3px;
  height: 34px;
  margin: 15.5px 18.8px 225.3px 32.8px;
  font-family: MicrosoftYaHeiGBpc-EUC-H;
  font-size: 30.1px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.81;
  letter-spacing: normal;
  text-align: center;
  color: #333;
  top: -17px;
  position: relative;
}
.homepage {
  width: 713.7px;
  height: 399.6px;
  margin: 225.3px 67.9px 46.5px 103.5px;
  object-fit: contain;
  position: absolute;
  top: 233px;
  left: 469px;
}
.prevPageBtn {
  width: 66.7px;
  height: 66.7px;
  margin: 0 737.7px 845.8px 32.4px;
  object-fit: contain;
  position: absolute;
  top: 67.9px;
  left: 277px;
}
.titleContainer {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  top: 120px;
  left: 802px;
}
.smallPic {
  width: 170.2px;
  height: 170.2px;
  margin: 251.4px 103.5px 249.7px 0;
  object-fit: contain;
  position: absolute;
  left: 299.8px;
  top: 248px;
}
.acrContainer {
  position: absolute;
  right: 259px;
  top: 400px;
  width: 273.1px;
  height: 353.8px;
  padding: 57.6px 32.9px;
  flex-direction: column;
  justify-content: center;
}
img.Acr-image {
  width: 273.1px;
  height: 353.8px;
  object-fit: contain;
  position: absolute;
  z-index: 1;
}
img.web {
  width: 52.6px;
  height: 52.6px;
  margin: 0 0 8.9px 104.2px;
  object-fit: contain;
  position: absolute;
  z-index: 5;
  right: 80px;
}
img.email {
  width: 57.4px;
  height: 21.1px;
  margin: 8.9px 104.2px 31.4px 0;
  object-fit: contain;
  position: relative;
  z-index: 5;
}
img.tel {
  width: 57.4px;
  height: 21.1px;
  margin: 31.4px 104.2px 29.8px 0;
  object-fit: contain;
  position: relative;
  z-index: 5;
}
img.fax {
  width: 57.4px;
  height: 21.4px;
  margin: 29.8px 104.2px 28.3px 0;
  object-fit: contain;
  z-index: 5;
  position: relative;
  z-index: 5;
}
img.add {
  width: 57.4px;
  height: 21.4px;
  margin: 28.3px 104.2px 0 0;
  object-fit: contain;
  position: relative;
  z-index: 5;
}
</style>
