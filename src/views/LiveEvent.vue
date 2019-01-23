<template>
  <div>
    <h1 class="header_page_title">LIVE EVENT</h1>
    <section v-if="live">
      <div class="loading" v-if="loading">LOADING</div>
      <div v-else>
        <h1>You will be redirect shortly.</h1>
      </div>
    </section>
    <section v-else>
      <h1>We go LIVE on <strong>January 24, 1 p.m. EST</strong>. Check back then!</h1>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'Day1',
    data () {
      return {
        loading: false,
        live: true,
        fields: {
          pageTitle: null,
          pageContent: null
        }
      }
    },
    mounted () {
      this.$nextTick(() => {
        if(!this.$parent.$data.isExpired) {
          this.live = false;
        }
      });
    }
  }
</script>