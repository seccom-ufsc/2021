<template>
  <v-container id="start-page">
    <v-col class="d-flex align-center flex-column" style="min-height: 90vh">
      <v-row class="d-flex align-center mobile-flex-column">
        <div class="text-h1 roboto-mono" v-text="'SECCOM'"></div>
        <div class="text-h1 blue-text-must-click roboto-mono" v-text="2021"></div>
      </v-row>
      <v-col class="d-flex flex-column justify-center">
        <v-row class="flex-grow-0 text-h5 roboto-mono">Semana Acadêmica da Computação e Sistemas</v-row>
        <v-row class="flex-grow-0 text-h5 roboto-mono">De 6 a 10 de dezembro</v-row>

        <v-row class="flex-grow-0 roboto-mono my-8">A SECCOM é um evento acadêmico que visa incrementar a experiência universitária das graduações em Ciência da Computação e Sistemas de Informação, trazendo palestras e oficinas de conteúdos além dos vistos durante a graduação. Esta edição será online e ocorrerá nos dias 6 a 10 de dezembro, com seus eventos ocorrendo majoritariamente no período da tarde. Você pode assistir as transmissões ao vivo no <a href="https://www.youtube.com/channel/UCva2-CmrvppJlf8jSAK61vw">canal no Youtube da SECCOM</a></v-row>
      </v-col>
    </v-col>
  </v-container>
</template>

<script>
export default {
  name: 'StartPage',

  data: () => ({
  })
}
</script>

<style lang="scss">
  .blue-text-must-click {
    color: #474793;
  }

  div.row .roboto-mono, div.col .roboto-mono{
    font-family: 'Roboto Mono', monospace !important;
  }

  @media (max-aspect-ratio: 1/1) {
    .mobile-flex-column {
      flex-direction: column;
    }

    .mobile-hide {
      display: none;
    }
  }
</style>
