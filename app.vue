<script setup>

useHead ({
  script: [{'src': 'https://kit.fontawesome.com/126e477cae.js'}]
})

</script>

<template>
  <!-- 
    <NuxtRouteAnnouncer />
    <NuxtWelcome /> 
  -->
  <div>
    <AppPreHeader />
    <NewHeader />
    <AppClaim />
    <AppContent />
    <AppArguments />
    <AppFooter />
  </div>
</template>
