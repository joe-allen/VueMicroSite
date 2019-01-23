<template>
  <div>
    <h1 class="header_page_title">{{ pageTitle }}</h1>
    <section v-if="live">
      <div class="loading" v-if="loading">LOADING</div>

      <div class="content" v-else>

        <div class="wistia_responsive_wrapper">
          <div class="wistia_embed wistia_async_sp1n2dagn6 videoFoam=true playbar=true fullscreenButton=true  playButton=false autoPlay=false">&nbsp;</div>
        </div>

        <br><br>

        <form class="optInForm" id="LeadGen">
          <h1 class="cal_link_header">Get Up-To-The-Minute Updates About The Event... And Two Special Never-To-Be-Seen-Again Bonuses ($79 Value!):</h1>
          <iframe src="https://slicktext.com/widget/v2/f7386e59301818e98a8275c463a8a3bc" width="514" height="299" frameborder="0" /></iframe>
        </form>
      </div>
    </section>
    <section v-else>
      <h1>This content is locked</h1>
    </section>
  </div>
</template>

<script>

  import { isPast } from 'date-fns';
  import wistia from 'wistia-js-player-api'

  export default {
    name: 'Day4',
    data () {
      return {
        loading: true,
        live: false,
        pageTitle: "Live Event Preview Part 2",
        currentDate: '',
        currentTime: '',
        part1StartDate: '01-23-2019',
        // part1StartDate: '01-24-2019',
        part1StartTime: '10:00:00',
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
        if(this.$parent.$data.daysRemainingTillEvent < '1') {
          this.loading = false

          // store date and times on arrival to page
          const now = new Date();
          const year = now.getFullYear();
          const month = now.getMonth() + 1;
          const day = now.getDate();
          const hours = now.getHours();
          const minutes = now.getMinutes() + 1;
          const seconds = now.getSeconds();

          this.currentDate = month + '-' + day + '-' + year;
          this.currentTime = hours + ':' + minutes + ':' + seconds;

          const explodeCurrentDate = this.currentDate.split('-');
          const explodeCurrentTime = this.currentTime.split(':');
          const explodeStartDate = this.part1StartDate.split('-');
          const explodeStartTime = this.part1StartTime.split(':');

          const expired = isPast( new Date(explodeStartDate[2], explodeStartDate[0]-1, explodeStartDate[1], parseInt(explodeStartTime[0]), parseInt(explodeStartTime[1]), parseInt(explodeStartTime[2])) );

          if(expired) {
            this.live = true;
          }

        } else {
          this.live = false;
        }
      });
    },
  }
</script>

<style lang="scss" scoped>
.left_img_container {
  width: 100%;
  margin: 0 auto;

  img {
    width: auto;
    margin-right: 15px;
    align-self: center;
    float: left;
  }
}
.right_img_container {
  width: 100%;
  margin: 0 auto;

  img {
    width: 35%;
    margin-left: 15px;
    align-self: center;
    float: right;
  }
}
.img_container {
  width: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: center;

  img {
    width: 60%;
    align-self: center;
  }
  img.w100 {
    width: 100%;
  }
}

@media screen and (max-width: 540px) {
  .right_img_container {
    img {
      width: 100%;
      margin-bottom: 15px;
    }
  }
  .left_img_container {
    img {
      width: auto;
      margin-bottom: 10px;
    }
  }
  .img_container {
    img {
      width: 100%;
    }
  }
}
</style>