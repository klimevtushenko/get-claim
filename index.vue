<script setup>
useHead({
  title: 'Claim Pro | Professional Claim Management',
  meta: [
    {
      name: 'description',
      content:
        'Claim Pro provides expert claim management services, connecting professionals with clients to resolve claims quickly and efficiently.',
    },
    { name: 'robots', content: 'index, follow' },
    { property: 'og:type', content: 'website' },
    { property: 'og:site_name', content: 'Claim Pro' },
    {
      property: 'og:title',
      content: 'Claim Pro | Professional Claim Management',
    },
    {
      property: 'og:description',
      content:
        'Claim Pro provides expert claim management services, connecting professionals with clients to resolve claims quickly and efficiently.',
    },
    { property: 'og:image', content: 'claims-hero-bg.jpg' },
    { property: 'og:url', content: 'https://www.getclaimpro.com/' },
    { name: 'twitter:card', content: 'summary_large_image' },
    {
      name: 'twitter:title',
      content: 'Claim Pro | Professional Claim Management',
    },
    {
      name: 'twitter:description',
      content:
        'Claim Pro provides expert claim management services, connecting professionals with clients to resolve claims quickly and efficiently.',
    },
    { name: 'twitter:image', content: 'claims-hero-bg.jpg' },
  ],
  link: [{ rel: 'canonical', href: 'https://www.getclaimpro.com/' }],
})
</script>
<template>
  <main class="overflow-hidden">
    <HomeHero />
    <HomeWhatWeDo />
    <HomeAboutClaim />
    <HomeJoinTeam />
    <HomeProtectInterests />
  </main>
</template>
<style scoped lang="scss"></style>

