<template>
  <aside
    class="space-y-2 fixed flex flex-col items-center h-screen left-0 top-0 w-16 py-6 bg-gray-50 dark:bg-gray-800 z-50"
  >
    <img
      :title="`v${extensionVersion}`"
      src="https://www.fast2.tech/images/favicon.png"
      class="w-10 mb-4 mx-auto"
    />

    <SidebarIcon icon="home" tooltip="Home 💡" />
    <SidebarIcon icon="timer" tooltip="Scheduler 💡" />
    <SidebarIcon icon="dashboard" tooltip="Dashboards 💡" />
    <SidebarIcon icon="settings-3" tooltip="Settings 💡" />
    <div class="flex-grow"></div>
    <SidebarIcon icon="information" tooltip="Information 💡" />
  </aside>
</template>

<script>
import SidebarIcon from "./SidebarIcon.vue";

export default {
  name: "AppSidebar",
  components: {
    SidebarIcon,
  },
};
</script>
