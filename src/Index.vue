<template>
  <App theme="dark"/>
</template>

<script>
import App from './components/App.vue'

import '@arc-web/components/dist/themes/index.css';
import '@arc-web/components/dist/themes/light.css';
import '@arc-web/components/dist/themes/dark.css';

// This setBasePath method is required to load static assets such as icons
import { setBasePath } from '@arc-web/components/dist/utilities/base-path.js';
setBasePath('/');

export default {
  name: 'Index',
  components: {
    App
  }
}
</script>