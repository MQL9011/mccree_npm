<template>
  <div id="gaoMap" />
</template>

<script lang="ts">
// import { Vue, Component } from 'vue-property-decorator';
// import { ICON_BUS_RED, ICON_KEYUNZHAN } from '@/common/images/index';
// import { ready } from '@/common/script/jsapi';
// import { namespace } from 'vuex-class';
// const Map = namespace('map');

// @Component
// export default class GaoMap extends Vue {
// @Map.State('map') private map;
// @Map.Action('createMap') private createMap;

// async mounted() {
//   let ua = navigator.userAgent;
//   if (ua === 'test') {
//     await this.createMap({ domId: 'map', geolocation: true }); // 初始化地图
//     return;
//   }
//   ready(async () => {
//     await this.createMap({ domId: 'map', geolocation: true }); // 初始化地图
//   });
// }
// markerClicked(e) {
//   console.log(e);
// }

// }
</script>

<style lang="less" scoped>
#gaoMap {
  width: 100%;
  height: 100%;
}
</style>
