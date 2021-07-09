<template>
  <nb-container>
    <text
    :style="{textAlign: 'center'}">Hello World</text>
  </nb-container>
</template>

<script>
import { Dimensions, Platform } from "react-native";

export default {
  props: {
    navigation: {
      type: Object
    }
  },
  data() {
    return {
    };
  },
};
</script>
