<template>
  <div>
    <header>
      <TrunityHeader />
      <TrunitySubHeader />
    </header>
    <main>
      <Nuxt />
    </main>
    <footer></footer>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout'
}
</script>
