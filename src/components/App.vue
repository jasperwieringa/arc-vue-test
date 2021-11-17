<template>
  <arc-container :theme="theme">
    <arc-navbar slot="nav">
      <arc-button type="tab">Tab One</arc-button>
    </arc-navbar>
    <arc-sidebar slot="side">
      <div>Sidebar content</div>
    </arc-sidebar>
    Default content
  </arc-container>
</template>

<script>
import '@arc-web/components/dist/components/container/arc-container.js';
import '@arc-web/components/dist/components/navbar/arc-navbar.js';
import '@arc-web/components/dist/components/sidebar/arc-sidebar.js';
import '@arc-web/components/dist/components/button/arc-button.js';

export default {
  name: 'Arc',
  props: {
    theme: String
  }
}
</script>