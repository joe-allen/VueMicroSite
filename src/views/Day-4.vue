<template>
  <div>
    <h1 class="header_page_title">{{ pageTitle }}</h1>
    <section v-if="live">
      <div class="loading" v-if="loading">LOADING</div>
      <div v-else>
        <h1>Placeholder content for Day 4</h1>
      </div>
    </section>
    <section v-else>
      <h1>This content is locked</h1>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'Day4',
    data () {
      return {
        loading: true,
        live: true,
        pageTitle: "Day 4"
      }
    },
    mounted () {
      let component = this;

      // send user to page top
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });

      this.$nextTick(() => {
        if(this.$parent.$data.daysRemainingTillEvent <= '2') {
          this.live = true;
          this.loading = false
        } else {
          this.live = false;
        }
      });
    },
  }
</script>