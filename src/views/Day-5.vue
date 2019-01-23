<template>
  <div>
    <h1 class="header_page_title">{{ pageTitle }}</h1>
    <section v-if="live">
      <div class="loading" v-if="loading">LOADING</div>
      <div class="content" v-else>

        <form>
          <p>Reminder: James’ 2019 Prediction Summit is on Thursday, January 24, at 1 p.m. EST</p>
          <p>We’re broadcasting it live — miss it, and you could miss your opportunity to ride three of James’ tidal-wave predictions to seven-figure wealth.</p>
          <h1 class="cal_link_header">Add This Event to Your Calendar:</h1>
          <div class="cal_link">
            <a href="http://www.google.com/calendar/event?action=TEMPLATE&dates=20190124T180000Z%2F20190124T190000Z&text=James%20Altucher%27s%202019%20Prediction%20Summit%20&location=Online%20From%20the%20Comfort%20of%20Your%20Own%20Home&details=A%20live%20broadcast%20with%20millionaire%20trend%20investor%2C%20James%20Altucher" target="_blank">Google Calendar</a>
            <a href="https://d8yoo85ikfg26.cloudfront.net/wp-content/uploads/2019/01/James_Altuchers_2019_Prediction_Summit.ics" target="_blank">iCal Calendar</a>
          </div>
        </form>

        <form class="optInForm" id="LeadGen">
          <h1 class="cal_link_header">Get Up-To-The-Minute Updates About The Event... And Two Special Never-To-Be-Seen-Again Bonuses ($79 Value!):</h1>
          <iframe src="https://slicktext.com/widget/v2/f7386e59301818e98a8275c463a8a3bc" width="514" height="299" frameborder="0" /></iframe>
        </form>

        <br>

        <div v-if="showPart2">
          <hr>
          <br>

          <div class="cal_link parts">

            <div class="part_1">
              <a @click.prevent="choosePart1" href="#!" target="_blank">Part 1</a>
              <span class="part_title_1">What would you do with a crystal ball and $100,000?</span>
            </div>
            <div class="part_2">
              <a @click.prevent="choosePart2" href="#!" target="_blank">Part 2</a>
              <span class="part_title_2">Financial Friday on a Wednesday</span>
            </div>
          </div>

          <hr>
          <br>

        </div>

        <br>
        <div v-show="showPart1">

          <h1 ref="part1">Part 1: “What would you do with a crystal ball and $100,000?”</h1>

            <br>

            <div class="left_img_container">
              <img src="https://d13p2xj50zkyqm.cloudfront.net/promos_10/LF/production//pubs/general/common/img/monica_circle-pic-autho-bio.png" alt="monica mcarthy">
              <p><strong>Hey, it’s Monica</strong>… James is hard at work prepping for the event… You’ll hear from him later this afternoon.</p>
            </div>

            <p>In the meantime, I have some incredible, heartwarming, inspirational stories to show from your fellow readers today. (And one that’s a little controversial!)</p>

            <p>First thing’s first, James went to scout the location down on Times Square. He recorded this video for you about “mastering” 2019:</p>

            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_n9p1eqithc videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <p>Remember, on that website, on <strong>January 24th at 1pm EST</strong>, we’ll be broadcasting James’ 2019 Predictions Summit. </p>

            <div class="pre">
              <p><strong>He’ll show you his 3 top trends for making money this year… and he’ll reveal a fascinating market anomaly you could piggyback for 1,000% returns in before the end of 2019.</strong></p>
            </div>

            <p>Ok, here’s what I wanted to show you today…</p>

            <p>Ever since you signed up for James’ Prediction Summit — which goes live on Thursday at 1pm! -- we’ve been asking for you to share what you’d do if you made 10x your money using James’ incredible predictive powers. </p>

            <p>For simplicity, we asked you to imagine turning a starting $10,000 stake into an extra $100,000. </p>

            <p>What would you do with 100 grand? </p>

            <p>The answers have been inspiring.</p>

            <p>It’s clear that many of you would do some incredible things with $100k… </p>

            <p>There are people who would give more to their favorite charities…  People looking to start a business or reinvest… Folks looking to travel the world and retire. People who just want to have some fun… </p>

            <p>We went through THOUSANDS of testimonials. </p>

            <p>Your feedback has made us laugh… cry… filled us with hope and joy…</p>

            <p>But mostly it’s gotten James and I pumped up to reveal all the details about James’ 2019 predictions tomorrow!</p>

            <p><strong>Here’s what your fellow readers said they would do with $100,000 by the end of 2019</strong>:</p>

            <!-- quotes -->
            <div class="pre"><strong>Hi James, the short and sweet answer here would be to take a vacation with my son. Not had one of those for ten years. I would re-invest most of it and try to make it a MILLION + why not hey. Simple!!!</strong>
            <br><br><span class="text_light">-- Paul</span></div>

            <div class="pre"><strong>With $100k, I would pay off all debt and use the remainder to bolster my retirement savings.</strong>
            <br><br><span class="text_light">-- Jeannette</span></div>

            <div class="pre"><strong>Allocate the additional $100,000 to specific charities within my existing trust.</strong>
            <br><br><span class="text_light">-- Wayne</span></div>

            <div class="pre"><strong>I'd pay off Credit Card debts and invest the difference!!</strong>
            <br><br><span class="text_light">-- David</span></div>

            <div class="pre"><strong>Proof Is In The Pudding! Reinvest in James ' Teachings!</strong>
            <br><br><span class="text_light">-- James</span></div>

            <div class="pre"><strong>I am dreaming to have a small health center to educate Americans to address their psychological, physical health issue by teaching Yoga, cooking healthy food and considering [environmental issues].</strong>
            <br><br><span class="text_light">-- Kathy</span></div>

            <div class="pre"><strong>Pay off some back bills and reinvest the other $90,000 to make more money.</strong>
            <br><br><span class="text_light">-- Stephen</span></div>
            <div class="pre"><strong>I just want the American dream that everyone else has if I can just have a half a percent of a million dollars I'll be content</strong>
            <br><br><span class="text_light">-- Julio</span></div>
            <div class="pre"><strong>I would use the money to supplement my income, pay off debts and medical bills. I just recently became a widow with the unexpected lost of my husband. Not looking to get filthy rich but would like to ease the stress of my financial situation.</strong>
            <br><br><span class="text_light">-- Darlene</span></div>
            <div class="pre"><strong>Pursue other life passions and create lasting wealth. Get rid of student loans so I don't feel obligated to stay strictly in my field.</strong>
            <br><br><span class="text_light">-- Daphne</span></div>
            <div class="pre"><strong>WE NEED A HOUSE BADLY, THAT MONEY WOULD BE USED FOR A DOWN PAYMENT!</strong>
            <br><br><span class="text_light">-- Reader from New York</span></div>
            <div class="pre"><strong>I would pay of my visa cards pay off my sister and invest in the stocks you recommend to me</strong>
            <br><br><span class="text_light">-- Chris</span></div>
            <div class="pre"><strong>I would reinvest all of the 100,000.00 dollars!</strong>
            <br><br><span class="text_light">-- Allen</span></div>
            <div class="pre"><strong>Spend it on debt and landscaping/interior refreshing.</strong>
            <br><br><span class="text_light">-- Will</span></div>
            <div class="pre"><strong>I would retire, since I am still working now at the age of 68.</strong>
            <br><br><span class="text_light">-- Billy</span></div>
            <div class="pre"><strong>I would use it to up-grade our condominium at Orange Beach, Alabama</strong>
            <br><br><span class="text_light">-- Frank</span></div>
            <div class="pre"><strong>I would spend $25,000 to buy my dream corvette which is a custom built Mako Shark. Then I would buy my dream home for $45,000 cash in North Carolina. With the balance I would reinvest in the markets under your guidance, with a little going into the Marijuana stock market. When making more money I would then share the information with my family and friends.</strong>
            <br><br><span class="text_light">-- Chris</span></div>
            <div class="pre"><strong>Give 10% to my church , then reinvest the rest for retirement life</strong>
            <br><br><span class="text_light">-- Dan</span></div>
            <div class="pre"><strong>I would teach my daughters how to invest it to make a living from home and give half of it to each as seed money. My daughters have serious health problems and to does my grandson. I would ask them to share the information with their friends and relatives who are interested in doing the same.</strong>
            <br><br><span class="text_light">-- Gerry</span></div>
            <div class="pre"><strong>I would donate it to the Anne Arundel Medical Center for cancer research and treatment. </strong>
            <br><br><span class="text_light">-- Jeff</span></div>
            <div class="pre"><strong>I would pay all my bills and my kids bills. Buy a house, take my kids and grand kids to Disney World and some other Theme Parks in Orlando. I would build some homeless shelters for families all over the United States. I would donate money to our Vets every month I would donate to the research hospitals for our Children. I would also donate to the animal shelters each month</strong>
            <br><br><span class="text_light">-- Christine</span></div>
            <div class="pre"><strong>I would revisit all the countries in which I lived and worked during my international employment</strong>
            <br><br><span class="text_light">-- Tony</span></div>
            <div class="pre"><strong>I WOULD TAKE THAT 100,000 and invest it and make it 1, 000,000</strong>
            <br><br><span class="text_light">-- Jerry</span></div>
            <div class="pre"><strong>Tithe. Give. Secure my children's education. Buy a condo. Travel.</strong>
            <br><br><span class="text_light">-- Elaine</span></div>
            <div class="pre"><strong>TAKE A VACATION INVEST IN A HOME STARTING A SMALL BUSINESS</strong>
            <br><br><span class="text_light">-- Kim</span></div>
            <div class="pre"><strong>I would share it out amongst my family. I would share with the how I managed to make that kind of money, so they too can learn and be educated in making these kinds of returns. I would share the love - because helping them out, shows them how much they mean to me.</strong>
            <br><br><span class="text_light">-- David</span></div>

            <p>Here’s a video from Sarah:</p>
            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_hn4d9r2lgo videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <div class="pre"><p>“I would give money to my friend Dity, who is raising four kids on her own in Israel, some to my parents, and..maybe go on a vacation to Bali.”</p></div>

            <hr>
            <br>

            <p>Ismael, a martial arts instructor, had this to say: </p>
            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_wdier7zekx videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <div class="pre"><p>“I would open up a center for battered women… It’s not about the money, it’s about helping other people.”</p></div>

            <hr>
            <br>

            <p>Julia wants some breathing room to open up a healing center:</p>

            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_wt9qvmp26s videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <div class="pre"><p>“Free myself from ongoing debt...open a healing centre...love to help people”</p></div>

            <hr>
            <br>

            <p>And here’s Stephen, who would take that $100,000, play lots of guitar, and travel to all those “bucket list” places:</p>

            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_frag1889un videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <div class="pre"><p>“Travel & explore the world, play music, paint watercolors”</p></div>

            <hr>
            <br>
            <br>

            <h3>Some Praise for James!</h3>

            <p>Some folks have taken the opportunity to say some other nice things about James…</p>

            <div class="pre"><strong>I saw James in 2011 predict Dow 20k and everybody laughed at him. Not me. But I missed the boat. I’m not gonna miss it this time. </strong>
            <br><br><span class="text_light">-- Jeff</span></div>
            <div class="pre"><strong>James has taught me what it means to have 100% ownership for my own life .... Thank You so much James.</strong>
            <br><br><span class="text_light">-- Darren</span></div>
            <div class="pre"><strong>[He’s] given me a lot of information on different ways to invest without losing your money and just opening my eyes to things that I never knew were possible and for that I'm very grateful. Thanks again.</strong>
            <br><br><span class="text_light">-- George</span></div>

            <p>And here’s a delightful video from Michael:</p>


            <div class="wistia_responsive_wrapper">
              <div class="wistia_embed wistia_async_td5gl9qa98 videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
            </div>

            <div class="pre"><p>James, I read your book, "Choose Yourself" from cover to cover. I laughed. I cried. I BEGAN TO LOVE MYSELF ENOUGH TO BE MYSELF! I NOW HAVE BEGUN TO CREATE A LIFE THAT I LOVE, THANKS TO YOU.</p></div>

            <hr>
            <br>

            <p>Some great stuff, right?</p>

            <p>We had to leave out a lot of dream scenarios and praise… </p>

            <p>But time is running short…</p>

            <p>And the 2019 Prediction Summit is right around the corner. </p>

            <h3>We Go Live Tomorrow, January 24, 1pm Eastern! </h3>

            <p>Mark your calendar, cancel your appointments, and stay tuned!</p>

            <p>You don’t want to miss this.</p>

            <p>Your host,</p>
            <p>Monica McCarthy</p>

            <p>PS Later this afternoon, James will reveal a little bit more about the event… I hear he has a special gift for you, too. Keep an eye out for that!</p>

            <p>And if you haven’t done so already, sign up for our premiere reminder service.</p>

            <hr>

            <br>

        </div>

        <div v-if="showPart2">

          <h1 ref="part2">Part 2: Keep an Eye On Your Inbox!</h1>

          <br>

          <div class="left_img_container">
            <img src="https://d13p2xj50zkyqm.cloudfront.net/promos_10/LF/production//pubs/general/common/img/altucher_circle-pic-autho-bio.png" alt="james altucher">
            <p>Predictions give me indigestion. </p>
            <p>Market forecasters exist to make weathermen look good, as economist John Kenneth Galbraith once noted. Making predictions is just a way to get attention.</p>
          </div>

          <p>On Wall Street, if you get it right just once (and you’re very loud about it), you get paid enormous sums for your (most likely dead wrong) follow-up predictions. </p>

          <p>And yet… Here I am, holding a Prediction Summit tomorrow, January 24th, at 1pm. </p>

          <p>Worse… I’m making some hefty market forecasts about the top trends I see hitting this year (and how they’re on a collision course).</p>

          <p>Worst yet… <strong>I’m backing it all up with an attention-grabbing guarantee that I’ll show you how to make 1,000% on your money by the end of 2019</strong>.</p>

          <p>So is this just a bold promise?</p>

          <p>Or am I the real deal? </p>

          <p>After all, 1,000% gains don’t come often. </p>

          <p>Here’s where I think I stand head-and-shoulders above pundits and other investment gurus…</p>

          <p>I put skin in the game. I actively invest in the ideas I believe in with my own money. But I always save my best ideas for my readers--so that I’m not “hogging” the investment with my dollars. I don’t pretend to be the smartest person in every room. And my track record is an open book (including the two times I went broke!).</p>

          <p>I also don’t know anyone else with my track record. </p>

          <p>I’ve made millions many times over by landing dozens of triple-digit and 1,000%+ gains off my predictions... </p>

          <p>All by using a single system.</p>

          <p>This system is the ace up my sleeve. The rabbit in my hat. </p>

          <p>It helped me make 6,000% and 3,600% with private investments.</p>

          <p>It earned me 7,100% in cryptos.</p>

          <p>It helped me find 13 stocks that went up over 1,000% and 77 others that went up between 100% and 999% over the last decade.</p>


          <p>And I’m going to show you how the magic trick works. </p>

          <div class="img_container">
            <img class="w100" src="https://d13p2xj50zkyqm.cloudfront.net/promos_2/LF/production/pubs/top/common/img/top_hotlist_012019/TOP_2019PREDICTIONSEVENT_CHART01_012019.png" alt="Big gains">
          </div>

          <br><br>

          <h3>HOW TO TURN TRENDS INTO DOLLARS</h3>

          <p>Unless you play these stocks the right way, you can’t expect to get 1,000% returns from big companies like Walmart or IBM. </p>

          <p>These gains don’t come from companies that don’t innovate. </p>

          <p>They come from the biggest and best new ideas. The most powerful market-shifting trends. </p>

          <p>They come from getting into the right plays at the right time alongside the right people. </p>

          <p>As I revealed to you a couple days ago, the “secret sauce” behind my predictions is identifying and investing in big trends. </p>

          <p>I said: “<strong>When you’re aware of what a trend can do for you — and you bring in a bit of investing knowledge — it gets real easy to see the future… and how wealthy the future-you can be</strong>.”</p>

          <p>The “knowledge” I mention above is what I call “investing through the back door.”</p>

          <p>A backdoor investment could be an ultra-small, low-share-price stock in the startup phase that’s going to dominate a growing trend. </p>

          <p>It could be a stock option on a big, publicly traded company that capitalizes on a “big idea” or trend sweeping the world. </p>

          <p>It could be a company that does business with another company surfing on a trend.</p>

          <p>(For example, why invest in Tesla when you can find the tiny company supplying batteries for the Tesla cars and invest in that? That tiny company won’t be tiny for long. So… you access it by going through the back door.) </p>

          <p>Almost always, there is a way to:</p>

          <ul>
            <li>Play a trend directly in the stock market</li>
            <li>Buy a stock whose business will directly benefit from a growing trend</li>
          </ul>

          <p>No matter what, when I hunt for stocks I’m always batting for 1,000% gains. But I’m never disappointed if I end up with a double or triple or more.</p>

          <p>This is exactly what happened with a stock I recommended back in 2010, called Inhibitex. I knew that under-the-radar stock was capitalizing on biotech trends. </p>

          <p>It shot up 787%. Enough to turn a $1,000 into $7,870. Or $10,000 into $78,700.</p>

          <p>I did the same thing with Petro River back in 2013, when I saw it surfing along huge energy trends in America. SF Gate even mocked me for recommending a stock this small.</p>

          <p>It shot up 715%.</p>

          <p>And then there was NVIDIA. They made chips for virtual reality headsets. So I saw the company as a backdoor way into the virtual reality trend.</p>

          <p>That popped up 568%. </p>

          <p>The great thing about this is it allows middle class investors and retirees to profit from huge trends without having to be a rich venture capitalist or accredited investor. </p>

          <p>In fact, you don’t need much money at all. You can make these backdoor investments from your kitchen table, if you like. </p>

          <p>And by doing that, you profit from the same market forces the mega-investors are taking advantage of.</p>

          <p>But I will warn you: These “backdoor” investments are extremely rare.</p>

          <p>Yet if you get access to these investment opportunities early enough, the potential is huge. </p>

          <p>Like when I recommended Tucows in <em>The Forever Portfolio</em>. That stock went up 6,025% over the course of a decade. Enough to turn every $1,000 into $60,250.</p>

          <p>Tomorrow, when the Predictions Summit goes live, I’ll be sharing with you the biggest trends I’m seeing in 2019… and the backdoor plays you can use to make money from them.</p>

          <h3>But What You’ll See On Thursday Isn’t Meant For Everyone</h3>

          <p>That’s because I’ll only look for the biggest and newest investment ideas… which some folks might find a bit too risky or “over the top.”</p>

          <p>I only recommend the best of what crosses my desk.</p>

          <p>I refuse to recommend any investment unless I know someone in the hedge fund world who’s bought in and I’ve analyzed it myself, for the best possible shot at returns of 100% to 1,000% or higher.</p>

          <p>These are the types of opportunities I’ve been profiting from for the past 2 decades.</p>

          <p>It’s the approach I use with my personal money. </p>

          <p>And on Thursday, I’ll show you exactly how to play each opportunity… every single month… with the same secret I’ve used at multimillion-dollar hedge funds.</p>

          <p>For example, I might recommend a 3-D printer that prints houses… a biotech firm that grows new organs… a super-robot company… you name it…</p>

          <p>But here’s the thing…</p>

          <p>What I’ve discovered after meeting thousands of investors over the years is that many folks can’t stomach these kinds of “innovations.”</p>

          <p>And if it’s one thing 2019 is going to have in spades, it’s innovation.</p>

          <p>And what I’ve learned is that when it comes to putting your money into the kind of trends reshaping society, most people simply aren’t cut out for it.</p>

          <p>They’d rather play it safe and buy blue chips or utilities or government bonds.</p>

          <p>There’s nothing wrong with that. But if that sounds like you, then some of my predictions and the strategies I’ll be using to make money off them might not be the best fit for you.</p>

          <p>We look for “backdoors” into truly big ideas BEFORE the masses ever hear about them… which potentially take off by 500% or even 1,000%.</p>
          <p>It’s happened to me dozens of times and I’ll continue to find these ideas year after year.</p>

          <p>But let me be clear, here. I’m not rolling dice here. </p>

          <p>You SHOULD NOT simply go out and buy every tiny company trying to profit from a trend. </p>

          <p>That’s a good way to blow up your wallet. </p>

          <p>You need to filter only the best ideas.</p>

          <h3>Your 4 Step Trend Stock Screener</h3>

          <p>As I mentioned, my network is my most valuable asset… and has allowed me to create and refine this investment secret that anyone can use to make tens of thousands of dollars, no matter what their background is. </p>

          <p>But my connections are just one step in deciding what to buy…</p>

          <p>You also have to identify a trend that affects millions of consumers…</p>

          <p>And you have to find all of the possible companies involved in the trend. </p>

          <p>Only then can you scour your network to find out which companies the “big guys” are most interested in.</p>

          <p>Once you have a short list of companies, then you have to decide which “backdoor” investment to make.</p>

          <p>I’m going to go much deeper into this tomorrow, and I’ll reveal exactly what I do at every stage of this system. </p>

          <p>But because backdoor investments can take many forms, I’ve put together this FREE report to help you set up the right brokerage account, so you can make these investments easily and on your own: “<a href="https://d8yoo85ikfg26.cloudfront.net/wp-content/uploads/2019/01/TOP_The1000Backdoor.pdf" target="_blank">The 1000% Backdoor Skeleton Key</a>.”</p>

          <p>I’ll reveal everything on tomorrow’s webinar at 1pm. </p>

          <p>I’m also going to reveal why 2019 is the best year in 40 years to start investing this way, due to a rare combination of market forces. </p>

          <p>So don’t hesitate—use your <a href="https://d8yoo85ikfg26.cloudfront.net/wp-content/uploads/2019/01/TOP_The1000Backdoor.pdf" target="_blank">free report</a> to set yourself up right.</p>

          <hr>
          <br>

          <p>Oh, and by the way, I went scouting in Times Square near the set location yesterday. </p>

          <p>I filmed a video for you, because I want you to know that 2019 is about more than making money. It’s about choosing yourself so you can have the best life you can possibly lead. </p>

          <p>Click here to see it:</p>

          <div class="wistia_responsive_wrapper">
            <div class="wistia_embed wistia_async_n9p1eqithc videoFoam=true playbar=true fullscreenButton=true  playButton=true autoPlay=false">&nbsp;</div>
          </div>

          <br><br>

          <div v-if="showPart2">
            <hr>
            <br>
            <div class="cal_link parts">
              <div class="part_1">
                <a @click.prevent="choosePart1" href="#!" target="_blank">Part 1</a>
                <span class="part_title_1">What would you do with a crystal ball and $100,000?</span>
              </div>
              <div class="part_2">
                <a @click.prevent="choosePart2" href="#!" target="_blank">Part 2</a>
                <span class="part_title_2">Financial Friday on a Wednesday</span>
              </div>
            </div>

            <hr>
            <br>

          </div>
        </div>

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
    name: 'Day5',
    data () {
      return {
        loading: true,
        live: true,
        pageTitle: "Day 5",
        showPart1: true,
        showPart2: false,
        currentDate: '',
        currentTime: '',
        part2StartDate: '01-23-2019',
        // part2StartTime: '16:00:00',
        part2StartTime: '16:00:00',
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
          this.live = true;
          this.loading = false
        } else {
          this.live = false;
        }
      });

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
      const explodeStartDate = this.part2StartDate.split('-');
      const explodeStartTime = this.part2StartTime.split(':');

      const expired = isPast( new Date(explodeStartDate[2], explodeStartDate[0]-1, explodeStartDate[1], parseInt(explodeStartTime[0]), parseInt(explodeStartTime[1]), parseInt(explodeStartTime[2])) );

      if(expired) {
        this.showPart2 = true;

        if(this.$route.params.id != 2) {
          this.showPart1 = true;
        }
      }

      if(this.$route.params.id == 2) {
        this.showPart1 = false;
        this.showPart2 = true;
      }
    },
    methods: {
      choosePart1 () {
        this.showPart1 = true;
        this.$nextTick(() => {
          window.scrollTo({
            top: (this.$refs.part1.offsetTop - 20),
            behavior: 'smooth'
          });
        });
      },
      choosePart2 () {
        this.showPart2 = true;
        this.$nextTick(() => {
          window.scrollTo({
            top: (this.$refs.part2.offsetTop - 20),
            behavior: 'smooth'
          });
        });
      }
    }
  }
</script>

<style >
.cal_link.parts {
  align-items: flex-start;
  width: 100%;
}
.cal_link.parts a {
  width: 95%;
  align-self: flex-start;
}
.cal_link.parts [class^="part_"]:last-of-type a {
  align-self: flex-end;
}
[class^="part_"] {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
  font-weight: bold;
  width: 100%;
  text-align: center;
}
[class^="part_title_"] {
  margin-top: 10px
}
</style>