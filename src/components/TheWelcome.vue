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
    <template #heading>Projects</template>
    You can see 
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Projects</a>
     at the company
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Service</template>
    You can order
    <a href="https://hpu-mining.com/services/" target="_blank" rel="noopener">Service</a> at the company
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Careers</template>
    take a look at the
    <a href="https://hpu-mining.com/careers/" target="_blank" rel="noopener">Careers</a> of the company
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Living at HPU</template>

    You can see
    <a href="https://hpu-mining.com/living-with-our-people/" target="_blank" rel="noopener">Living with our people</a> and
    <a href="https://hpu-mining.com/living-with-our-community/" target="_blank" rel="noopener">Living with our community</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact us</template>

    do you have any questions? You can
    <a href="https://hpu-mining.com/contact-us/" target="_blank" rel="noopener">Contact us</a> to find the answer
  </WelcomeItem>
</template>
