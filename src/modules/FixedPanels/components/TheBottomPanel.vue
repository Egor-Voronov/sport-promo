<script lang="ts" setup>
import FixedPanel from "../ui/FixedPanel.vue";
import CurrentGood from "./CurrentGoodTxt/TheCurrentGoodTxt.vue";
import Title from "./Title/TheTitle.vue";
</script>

<template>
  <fixed-panel :class="$style.bottomPanel">
    <Title />
    <CurrentGood />
  </fixed-panel>
</template>

<style lang="scss" module>
.bottomPanel {
  bottom: 0;

  @extend %FixedPanelsNormalFont;
}
</style>
