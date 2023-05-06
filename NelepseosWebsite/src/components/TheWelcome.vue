<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <div>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Github</template>

    My
    <a href="https://github.com/Nelepseo" target="_blank" rel="noopener">Github</a>
    for a view of my sparse portfolio of unfinished projects.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Linkedin</template>

    My
    <a href="https://www.linkedin.com/in/andrew-thompson18/" target="_blank" rel="noopener">Linkedin</a>
    for professional information.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Youtube</template>

    My
    <a href="https://www.youtube.com/@Nelepseo" target="_blank" rel="noopener">Youtube</a>
    for a look at my younger self trying to create content. <span style="color: red">WARNING</span> Cringe worthy material.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Twitter</template>

    My
    <a href="https://twitter.com/Nelepseo" target="_blank" rel="noopener">Twitter</a>
    for a look at my younger self trying to create content. <span style="color: red">WARNING</span> Not used very often.
  </WelcomeItem>
</div>
</template>