<template lang="pug">
  v-layout
    v-flex.text-center
      img.mb-5(src="/v.png"  alt="Vuetify.js")
      blockquote.blockquote &#8220;{{$t("#inspire.text")}}&#8221;
        footer
          small
            em &mdash;John Johnson
</template>
