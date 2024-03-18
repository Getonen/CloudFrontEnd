<script setup>
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
    <template #heading>Sentiment Analysis</template>

    <p>Text Input:</p> 
    <textarea id="textToAnalyst" name="text" rows="10" cols="30"></textarea>
    <br />
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
  </WelcomeItem>

 
</template>
