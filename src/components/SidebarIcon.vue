<template>
  <div class="sidebar-icon group">
    <!-- v-bind to force transfering, mapping, forwarding prop to child -->
    <RemixIcon class="" v-bind:icon="icon" />
    <span class="sidebar-tooltip group-hover:scale-100" value="">{{ tooltip }}</span>
  </div>
</template>

<script>
import RemixIcon from "./RemixIcon.vue";

export default {
  name: "SidebarIcon",
  components: {
    RemixIcon,
  },
  props: {
    icon: String,
    tooltip: String,
  },
};
</script>
