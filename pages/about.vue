<template>
  <div>
    <h1>{{ title }}</h1>
    <nuxt-link to="/">Home</nuxt-link>
    <n-link to="/">Another Way</n-link>
    <NuxtLink to="/">Another Way</NuxtLink>
    <NLink to="/">Another Way</NLink>
  </div>
</template>

<script>
export default {
  //middleware: 'test',
  asyncData() {
    return { title: 'About' }
  },
  head() {
    return {
      title: 'About',
      meta: [
        { hid: 'description', name: 'description', content: 'Hello World' },
      ],
      script: [
        {
          src: '/about.js',
        },
      ],
    }
  },
}
</script>
