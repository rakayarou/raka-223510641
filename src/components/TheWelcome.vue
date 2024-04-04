<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>History</template>
    Saya adalah lulusan SMKN 1 MANDAU jurusan Teknik Komputer dan Jaringan
    <br>Saya pernah dikeluarin dari perusahaan saat saya magang karena terlalu jago wkwk, gak gak karena ada masalah sikit </br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>
    email : rakasandheo160304@gmail.com 
    <br> instagram : @rakayarou</br>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    1. Main game
    <br> 2. Berbakti kepada org tua 
    <br> 3. Speeding
    <br> 4. spending money
    <br> 5. Dramatis
  </WelcomeItem>
</template>
