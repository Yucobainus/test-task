<template>
  <v-header></v-header>
  <v-banner></v-banner>
  <post-list></post-list>
  <v-footer></v-footer>
</template>

<script>
import VHeader from "@/components/VHeader";
import VFooter from "@/components/VFooter";
import VBanner from "@/components/VBanner";
import PostList from "@/components/PostList";
export default {
  components: {
    VHeader, VFooter, VBanner, PostList
  }
}
</script>

<style></style>
