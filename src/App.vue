<template>
  <div id="app">
    <tool-menu-bar></tool-menu-bar>
    <workspace-canvas></workspace-canvas>
    <file-menu-bar></file-menu-bar>
  </div>
</template>

<script>
import ToolMenuBar from '@/components/ToolMenuBar.vue'
import WorkspaceCanvas from '@/components/Workspace.vue'
import FileMenuBar from '@/components/FileMenuBar.vue'

export default {
  name: 'App',
  components: {
    'tool-menu-bar': ToolMenuBar,
    'workspace-canvas': WorkspaceCanvas,
    'file-menu-bar': FileMenuBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
