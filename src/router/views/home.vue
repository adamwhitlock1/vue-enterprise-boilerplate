<script>
import appConfig from '@src/app.config'
import Layout from '@layouts/main'

export default {
  page: {
    title: 'Home',
    meta: [{ name: 'description', content: appConfig.description }],
  },
  components: { Layout },
}
</script>

<template>
  <Layout>
    <h1 class="text-4xl text-green-800 font-bold uppercase">Home Page</h1>
    <img src="@assets/images/logo.png" alt="Logo" />
  </Layout>
</template>
