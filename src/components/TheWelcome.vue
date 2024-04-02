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
    <template #heading>About Me</template>
    I am a student at the Islamic University of Riau, located on Kaharuddin Nst Street in Pekanbaru.
    Currently, I am in the 4th semester of the Computer Engineering department at the Islamic
    University of Riau. I come from Rokan Hilir District, Bagan Sinembah Subdistrict, Riau Province.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Education</template>

    SDN 1 BATU HAMPAR 2009-2015<br />
    SMPN 1 BATU HAMPAR 2015-2018<br />
    SMAN 1 BATU HAMPAR 2018-2021<br />
    ISLAMIC UNIVERSITY OF RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skills</template>
    I have skills in programming, especially in JavaScript and the Vue.js framework. Additionally, I
    am also familiar with HTML, CSS, and various other web technologies. I am confident in
    problem-solving and have good communication skills.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Instagram</template>
    <h2>Instagram</h2>
    <p>
      You can view my Instagram
      <a
        href="https://www.instagram.com/zatbezi?igsh=MTB5enBxMzdqYW1heQ=="
        target="_blank"
        rel="noopener"
        >@zatbezi</a
      >, where you can follow me.
    </p>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Me</template>

    <p>
      If you wish to contact me, please send an email to
      <a href="mailto:mhmmdazizi18@gmail.com" target="_blank" rel="noopener"
        >mhmmdazizi18@gmail.com</a
      >.
    </p>
  </WelcomeItem>
</template>
