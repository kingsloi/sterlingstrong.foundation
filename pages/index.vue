<template>
  <div class="site">
    <main class="sterly-girly">
      <div class="container">
        <div class="row mb-5">
          <div class="col-12 small">
            <p class="d-block text-uppercase mb-0 small">
              upcoming events
            </p>
          </div>

          <div class="col-sm-6 ">
            <div class="card small">
              <img class="card-img-top" src="/i/sterling-strong-foundation-billboard.jpeg" alt="Card image cap">
              <div class="card-body py-2 px-3">
                <div class="card-text mb-0">
                  <div class="event-item">
                    <div class="event-schedule">
                      <span class="event-day">30</span>
                      <div class="event-month-time">
                        <span>August</span>
                        <span>1PM-7PM</span>
                      </div>
                    </div>

                    <a href="#2022-blood-drive" class="event-title">
                      Annual Blood Drive
                    </a>

                    <p class="event-content small">
                      <a target="_blank" href="https://www.redcrossblood.org/give.html/drive-results?order=DATE&range=10&zipSponsor=sterlingstrong">Book now</a> and secure your spot!
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="col-sm-6 mt-3 mt-sm-0 align-items-center align-self-end">
            <div class="card small">
              <div class="card-body py-2 px-3">
                <div class="card-text mb-0">
                  <div class="event-item">
                    <div class="event-schedule">
                      <span class="event-day">30</span>
                      <div class="event-month-time">
                        <span>September</span>
                        <span>6PM-9PM</span>
                      </div>
                    </div>

                    <a href="#2022-annual-fundraiser" class="event-title">
                      Annual Fundraiser
                    </a>

                    <p class="event-content small">
                      Save time & <a href="https://sterlingstrongfundraiser.rsvpify.com" target="_blank">buy tickets</a> in advance!
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <hr class="mb-5">

        <header>
          <img src="/i/sterling-strong.png" class="mw-100 d-block mb-5 mx-auto" style="width: 350px;">
        </header>

        <nav class="page-nav">
          <ul class="list-inline list-unstyled mb-5 text-center pl-0">
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#foundation'}">
                Foundation
              </nuxt-link>
            </li>
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#donate'}">
                Donate
              </nuxt-link>
            </li>
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#sterling-raspe'}">
                Sterling
              </nuxt-link>
            </li>
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#events'}">
                Events
              </nuxt-link>
            </li>
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#poptabs'}">
                Pop Tabs
              </nuxt-link>
            </li>
            <!-- <li class="list-inline-item"><nuxt-link :to="{ path: '/', hash:'#swag'}">Swag</nuxt-link></li> -->
            <li class="list-inline-item">
              <nuxt-link :to="{ path: '/', hash:'#music'}">
                Music
              </nuxt-link>
            </li>
          </ul>
        </nav>

        <h1 id="foundation" class="display-4" name="foundation">
          Sterling Strong Foundation &#10084;&#xFE0E;
        </h1>
        <p class="lead">
          Introducing the <span class="font-weight-bold">Sterling Strong Foundation, Inc.</span>, a recognised <span class="non-profit">501(c)(3)</span> non-profit, in honour of <span class="font-weight-bold">Sterling Raspe</span>.
        </p>
        <p class="lead">
          The Foundation's goals will be to help families in a similar situation to Sterling's: rare/chronic illnesses, long/multiple ICU stays, multi-system affecting conditions, treatment outside of home state, etc. with a few things which we <small>(her mom & dad)</small> personally took comfort from during Sterling's 207 days in the ICU, <span class="mission-ampersand">&amp;</span> help bring awareness to, and be an advocates of, congenital heart disease (CHD), Kabuki syndrome, Isomerism/Heterotaxy, and other rare diseases.
        </p>

        <p>Things such as:</p>

        <ul class="fancy-list">
          <li>
            <p class="mb-0 text-uppercase">
              Paying a bill or two
            </p>
            <p class="small">
              It was difficult to make sure all our I's were dotted and our T's were crossed in the ICU, not to mention adding an entire life outside of the hospital into the mix. Our monthly mortgage payment was paid twice by the generosity of others. It was a tremendous help for us. Maybe paying the water bill, a car payment, home insurance, etc., the smallest of thing can really make the biggest of difference.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              comfort items
            </p>
            <p class="small">
              We purchased a mini projector and setup a little cinema in Sterling's ICU room. You wouldn't think you could have a 70" private cinema in an ICU room, would you? <small>(we binge-watched Jersey Shore, et al)</small>. Things to help make parents/patients feel more comfortable/more at home, given the chaos.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              self care items
            </p>
            <p class="small">
              We realised taking care of yourself is just as important as taking care of your child. Your child feeds off of your energy, and it's amazing what getting a pedicure/manicure, hair cut, new products to try, etc. does to the mood. Every mother, father, carer, etc. needs some self-care here and there.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              items for baby's development
            </p>
            <p class="small">
              Nurses do a fantastic job, but they can't be everywhere and do everything (they're superheroes, but not that type of superhero). We purchased a sound recorder and recorded ourselves reading books to Sterling, we recorded albums, messages from family members around the world, prayers, <abbr title="including: Half Manne, Half Cocaine and The Alchemist take on the UNDEAD in this INSTANT CLASSIC First issue --- As the Undead try to move into the Casino game, a turf war ensues and our Anti-Hereoes Freddie “Half Manne, Half Cocaine” Gibbs and The Alchemist travel to the City of Sin to settle their debts.">you name it</abbr>, and asked the nurses to play it whenever we weren't around. We were told it was a huge hit with Sterling, and it helped ease our minds that she was taking comfort from our voices when we weren't around. Staring at the ceiling all day isn't good for a baby's development. A night light that illuminated the room in stars and moons had Sterling obsessed. Oh, and don't get us started on her favourite <a href="https://www.fisher-price.com/en-ca/product/pizza-teether-gmc38" target="_blank">pizza slice</a>.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              gift/meal cards
            </p>
            <p class="small">
              Everyone knows hospital food sucks. We learnt that Chick-fil-A and Frank's RedHot makes anything delicious, but sometimes a meal outdoors, take-out, or a delivered meal does wonders.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              arts &amp; crafts
            </p>
            <p class="small">
              We coloured. We painted. We made memes. We decorated the ICU room(s). Staying mindless helps block out the beeps and dings.
            </p>
          </li>
          <li>
            <p class="mb-0 text-uppercase">
              air quality awareness
            </p>
            <p class="small">
              Accumulating evidence indicates that air pollutants contribute to serious, sometimes fatal damage to the cardiovascular system, even for previously heart-healthy individuals, and further acerbates symptoms for already-at-risk individuals, like Sterling. You can't treat air pollution with diet, exercise, or medication, so we're all better off by advocating for better air quality. To raise awareness, we're bringing world-class air quality monitoring, to Gary, Indiana!
            </p>
            <p class="small">
              Visit <a target="_blank" href="https://millerbeach.community">millerbeach.community</a> for more information.
            </p>
          </li>
          <li>
            <p class="mb-0 font-italic">
              and many other helpful deeds...
            </p>
          </li>
        </ul>

        <horizontal-line />

        <h2 id="donate">
          Interested in helping?
        </h2>
        <p class="lead">
          If you'd like to join us in helping these special families/warriors, please consider making a donation using the form below.
        </p>

        <script src="https://donorbox.org/widget.js" paypalExpress="false" /><iframe
          src="https://donorbox.org/embed/sterling-strong"
          name="donorbox"
          allowpaymentrequest="allowpaymentrequest"
          seamless="seamless"
          frameborder="0"
          scrolling="no"
          height="900px"
          width="100%"
          style="max-width: 420px; min-width: 250px; max-height:none!important; margin: 0 auto; display: block; margin-top: 2rem;"
        />

        <p class="p-3 mt-5 mb-0 text-center position-relative lead" style="z-index: 1000;">
          Your Donation Is Tax-exempt
        </p>

        <p class="lead mt-6 text-center">
          Any philanthropists interested in helping are encouraged to email <abbr title="you have to manually type me into your email field!"><span class="d-inline-block mark e-mail" data-user="olleh" data-website="noitadnuof.gnortsgnilrets" /></abbr>
        </p>

        <horizontal-line />

        <h2 id="sterling-raspe" class="display-4" name="sterling-raspe">
          Sterling <br class="d-xs-block d-sm-block d-md-none"> Raspe
        </h2>

        <p class="lead">
          Sterling's eight months on earth were quite unique, but her story didn't start there. Her story began when her mom and dad met in 2015. Sterling's life was the missing piece to their parent's love story. As if sharing the other half of Banky's "Balloon Girl" tattoo to remember the loss of their parents wasn't fate enough, Sterling was the little girl with the heart-shaped balloon tying Kingsley and Maddie together for life.
        </p>

        <p>At her 21-week anatomy scan, Sterling was diagnosed with hypoplastic left heart syndrome variant (HLHS), a rare type of congenital heart disease (CHD). At three months old, she was diagnosed with Kabuki Syndrome, a rare multi-system-affecting genetic condition that can affect the entire body. Sterling, the HLHS Warrior, was also Sterling the Kabuki Queen. Despite being 1 in 700,000,000+, 207 days in the PCICU, 9 surgeries, there was not a second that went by that Sterling was not smothered in love, prayer, or celebration. Although Sterling's life was short, her fight and strength touched the hearts of strangers from all four corners of the world.</p>

        <p>Sterling Nova Lynn Raspe's legacy will live on through the many lives she touched. She was the embodiment of strength, fight, love, hope, peace, and joy. Against all the odds, she taught us to smile through the hard times, laugh at the inappropriate times, love without limits, and see the beauty and worth in all things big and small. She helped raise awareness and shined a light on HLHS, CHD, Kabuki Syndrome, and other rare diseases. Sterling taught us all something.</p>

        <!--
        <figure class="figure mt-7 mb-5 d-block">
          <client-only>
            <model-stl
              class="mb-0"
              src="/files/sterling-raspe-hand-mold.stl"
              background-color="#f7f3f0"
              :gl-options="{ 'Material': { 'Color': 'rgb(255, 0, 0)' } }"
              :lights="lights"
              :controls-options="controlsOptions"
              :position="{ x: 0, y: 0, z: 0 }"
              :rotation="{ x: 0, y: 0.75, z: 1 }"
            />
          </client-only>
          <figcaption class="figure-caption text-center" style="font-size: 65%;">
            A 3D scan of Sterling's hand
          </figcaption>
        </figure>
-->

        <p>The word Sterling comes from the word "steorra", meaning star. The word "nova" means new. Sterling Nova. A little star made new and whole in heaven. A nova is when a star's gas builds up and triggers an explosion making it shine up to a million times brighter than normal.</p>

        <p>May we all remember her life and be <span class="font-weight-bold">"Sterling Strong"</span> because her life and impact on this earth and our hearts was a supernova. Created perfectly imperfect, may she forever Rest In Peace.</p>

        <figure class="figure mt-5 mb-10">
          <img src="/i/banksys-balloon-girl.gif" class="mw-100">
        </figure>

        <horizontal-line />
      </div>

      <figure class="figure my-10 w-100 sterling-strong-life">
        <h3 class="figure-caption text-center w-lg-50 mx-auto pb-5">
          Follow Sterling's journey through her <a href="https://beadsofcourage.org/" target="_blank">Beads of Courage</a>.<br>One bead for every procedure, poke, surgery, day in the ICU<br> etc, etc, etc.
        </h3>

        <a href="https://sterlingstrong.life/" target="_blank" class="d-block"><img src="/i/sterling-beads-of-courage.png" class="w-100"></a>

        <figcaption class="figure-caption text-center w-50 mx-auto pt-5">
          visit <a href="https://sterlingstrong.life/" target="_blank">sterlingstrong.life</a>
        </figcaption>
      </figure>

      <div class="container">
        <horizontal-line />

        <h2 id="events" class="display-4" name="events">
          Sterling Strong Events
        </h2>
        <section class="timeline my-6 mx-md-n5 mx-lg-n10">
          <div class="d-flex flex-column">
            <div class="timeline-item text-muted">
              <div class="timeline-img" />
              <div class="timeline-content" style="opacity: 0.5;">
                <h2 class="h4">
                  Sterling Strong Day
                </h2>
                <div class="date">
                  April 17th 2021
                </div>
                <p>Ava Micheal Beautique put on the original "Sterling Strong" day, it included a braid bar, up-do's, music (and more), and the money raised went to Sterling's medical bills. Thank you, Ava Micheal Beautique!</p>
                <address class="small mb-0">
                  <strong class="d-block brand-4">Ava Micheal Beautique</strong>
                  120 S Main St<br> Crown Point<br> IN 46307
                  <a href="https://www.avamichaelbeautique.com/" target="_blank" class="d-block">avamichaelbeautique.com</a>
                </address>
              </div>
            </div>

            <div class="timeline-item text-muted">
              <div class="timeline-img" />
              <div class="timeline-content" style="opacity: 0.5;">
                <h2 class="h4">
                  Sterling Strong Day
                </h2>
                <div class="date">
                  June 12th 2021
                </div>
                <p>Moda were kind enough to put on a "Sterling Strong" day, they put on a braid bar, did up-do's, face painting, music, raffles, (and more) and the money raised was donated to Sterling's Foundation! Thank you, Moda!</p>
                <address class="small mb-0">
                  <strong class="d-block brand-4">Moda Beauty Bar</strong>
                  10921 Miami St<br> Winfield<br> IN 46307
                  <a href="https://www.modabeautybar.com/" target="_blank" class="d-block">modabeautybar.com</a>
                </address>
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content" style="opacity: 0.5;">
                <h2 class="h4">
                  Annual Blood Drive
                </h2>
                <div class="date">
                  August 31st 2021
                </div>
                <p>Sterling had 9 surgeries, and needed many blood transfusions, she was also immunocompromised and needed weekly IVIG infusions made from plasma of blood donations.</p>
                <p class="text-muted ml-3">
                  To make an average yearly dose of IVIG for patients who need it, it takes 250 liters of blood plasma. To make 1 liter of plasma, four whole blood donations are needed. <a href="https://www.ribc.org/news/articles/the-blood-of-1000-donors/" target="_blank" class="small">[source]</a>
                </p>
                <p>Your blood donation is more than just blood for many people.</p>
                <p>Help us keep the blood banks full!</p>
                <address class="small mb-0">
                  <strong class="brand-4">CrossPoint Church</strong><br>
                  214 S Court St<br> Crown Point<br> IN 46307
                </address>
                <p class="mt-3">
                  Please <a target="_blank" href="https://www.redcrossblood.org/give.html/drive-results?order=DATE&range=10&zipSponsor=sterlingstrong">book an appointment</a> to secure your spot!
                </p>
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content position-relative overflow-hidden pt-0">
                <div class="balloon-container" />

                <h2 class="h4 position-relative pt-5" style="opacity: 0.5; z-index: 1000;">
                  Celebration of Life & Foundation Launch
                </h2>
                <time class="d-block date position-relative" datetime="2021-09-12 13:00" style="opacity: 0.5; z-index: 1000;">September 12th 2021 1-5PM</time>
                <p style="opacity: 0.5; z-index: 1000;">
                  Join us for Sterling's 1st birthday, a celebration of her life, and for the launch of her foundation! Live music, caricature drawings, silent auction, and more!
                </p>

                <address class="small position-relative" style="opacity: 0.5; z-index: 1000;">
                  <strong class="brand-4">Gary Aquatorium</strong><br>
                  6918 Oak Ave<br> Gary<br> IN 46403
                </address>

                <p class="mark p-3 mb-0 text-center position-relative mark-opacity-75 text-white" style="z-index: 1000;">
                  What an incredible day! We raised over $4,000 - thank you to everyone who helped show their support and/or who has contributed in some way! We appreciate you!
                </p>
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content position-relative overflow-hidden pt-0" style="opacity: 0.5">
                <h2 class="h4 position-relative pt-5">
                  Delivered Christmas Care Packages to the PCICU 🎅
                </h2>
                <time class="d-block date position-relative" datetime="2021-12-19 13:00">December 19th 2021</time>
                <p>
                  Maddie and Kingsley delivered 20 home-made boxes full of festive goodies to the PCICU for babies and their families, and their ICU room.
                </p>
                <figure class="figure">
                  <img src="/i/2021-holiday-boxes.jpg" alt="2021 holiday boxes delivered to the PCICU" class="d-block mw-100">
                  <figcaption class="figure-caption text-center mt-0 mb-0 small">
                    <small>Santa came early!</small>
                  </figcaption>
                </figure>
                <p>
                  Full of decorations, twinkle lights, coffee mug, candy, socks, stockings, cookies, books, gift cards, a felt board and more, the boxes were sponsored by families and businesses in Northwest Indiana, and their animals.
                </p>
                <p>
                  We also delivered 20 voice recorders preloaded with wonderful songs, poems, stories, and more, to the PCICU directly, made by Anna Bucci and other fantastic artists.
                </p>
                <p class="mb-0">
                  Doctors, nurses, therapists, and families can use the voice recorders to soothe the babies, playing recordings of their parents voices reading stories, playing music, etc.
                </p>
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content position-relative overflow-hidden pt-0">
                <div class="balloon-container" />

                <h2 class="h4 position-relative pt-5" style="opacity: 0.5; z-index: 1000;">
                  IRS Approves Tax-Exempt Status
                </h2>
                <time class="d-block date position-relative" datetime="2022-01-06 12:00" style="opacity: 0.5; z-index: 1000;">January 6th 2022</time>
                <p class="mb-0" style="opacity: 0.5;">
                  Sterling Strong Foundation was recognised as a tax-exempt <span class="non-profit">501(c)(3)</span> nonprofit organisation on both a national and state level with EIN 87-2210499.
                </p>
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content px-0 pb-0 ">
                <h2 class="h4 px-5">
                  Sterling's Blood Drive Appears on ABC 7 Chicago
                </h2>
                <time class="px-5 d-block date position-relative" datetime="2022-01-07 17:00" style="opacity: 0.5; z-index: 1000;">January 7th 2022</time>
                <iframe
                  width="100%"
                  height="243"
                  class="mb-n3"
                  src="https://www.youtube-nocookie.com/embed/x1mfPVt9u_A?controls=0"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                />
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content px-0 pb-0 ">
                <h2 class="h4 px-5">
                  Rainbow Babies Meet
                </h2>
                <time class="px-5 d-block date position-relative" datetime="2022-05-18 10:00" style="opacity: 0.5; z-index: 1000;">May 18th 2022</time>
                <iframe
                  width="100%"
                  height="243"
                  class="mb-n3"
                  src="https://www.youtube-nocookie.com/embed/9NJSoocz1mU?controls=0&showinfo=0"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                />
              </div>
            </div>

            <div class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content position-relative overflow-hidden pt-0">
                <div class="balloon-container" />
                <h2 class="h4 position-relative pt-5" style="opacity: 0.5; z-index: 1000;">
                  We Collected 1 Million Pop Tabs!
                </h2>
                <time class="px-0 d-block date position-relative" datetime="2022-05-30 10:00" style="opacity: 0.5; z-index: 1000;">May 30th 2022</time>
                <p class="mb-0" style="opacity: 0.5;">
                  A big <mark>thank you</mark> to everyone who helped us reach our goal of collecting 1 million pop tabs!
                </p>
              </div>
            </div>

            <div id="2022-blood-drive" class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content">
                <h2 class="h4">
                  Annual Blood Drive
                </h2>
                <div class="date">
                  August 30th 2022 - 1-7PM
                </div>
                <p>Last year's blood drive was so successful, we're hosting another!</p>
                <p>Your blood donation is more than just blood for many people.</p>
                <p>Help us keep the blood banks full!</p>
                <address class="small mb-0">
                  <strong class="brand-4">CrossPoint Church</strong><br>
                  214 S Court St<br> Crown Point<br> IN 46307
                </address>
                <p class="mt-3">
                  Please <a target="_blank" href="https://www.redcrossblood.org/give.html/drive-results?order=DATE&range=10&zipSponsor=sterlingstrong">book an appointment</a> to secure your spot!
                </p>

                <p class="mb-0">
                  <strong class="brand-4 d-block">Can't make it?</strong>
                  You can still donate in Sterling's memory at a location/time that's more convenient, visit our <a target="_blank" href="https://sleevesup.redcrossblood.org/campaign/sterling-strong-foundation/">SleevesUp</a> campaign, and pledge to give blood near you!
                </p>
              </div>
            </div>

            <div id="2022-annual-fundraiser" class="timeline-item">
              <div class="timeline-img" />
              <div class="timeline-content position-relative overflow-hidden pt-0">
                <h2 class="h4 position-relative pt-5" style="z-index: 1000;">
                  2<sup>nd</sup> Annual Fundraiser
                </h2>
                <time class="d-block date position-relative" datetime="2021-09-12 13:00" style="z-index: 1000;">September 30th 2022 - 6-9PM</time>
                <p style="z-index: 1000;">
                  Join us for Sterling's 2nd birthday, and a celebration of her life! Live reggae music, photo booth, games, food &amp; drink, caricature drawings, silent auction, and more!
                </p>

                <address class="small position-relative" style="z-index: 1000;">
                  <strong class="brand-4">Gary Aquatorium</strong><br>
                  6918 Oak Ave<br> Gary<br> IN 46403
                </address>

                <p class="mt-3 mb-0">
                  Save time &amp; <a href="https://sterlingstrongfundraiser.rsvpify.com" target="_blank" class="font-weight-bold ">buy tickets</a> online today!
                </p>
              </div>
            </div>
          </div>
        </section>

        <horizontal-line />

        <h2 id="poptabs" class="display-4 text-center" name="poptabs">
          Pop Tabs Collection
        </h2>
        <figure class="figure mt-4 mb-4">
          <img src="/i/collecting-poptab.png" class="mw-100 p-6 w-50 mx-auto d-block">
          <figcaption class="figure-caption text-center mt-0 w-75 mx-auto">
            <strike class="d-inline-block">
              Collecting 1 million pop tabs!
            </strike> Done!
          </figcaption>
        </figure>

        <p>We collected <span class="font-weight-bold brand-4">1 million pop tabs</span> to help give back* to the <span class="font-weight-bold brand-4">Ronald McDonald House</span>. The Ronald McDonald House helped our family by providing a <em>"home away from home"</em> for us. By raising 1 million pop tabs (or <em>789 lbs</em>), the Ronald McDonald House in Oak Lawn will add Sterling's name to their <a href="https://rmhccni.org/get-involved/pop-tabs/">Thanks A Million</a> tree.</p>

        <blockquote class="small mb-5 mt-4">
          <p class="small text-right text-muted pull-right">
            * "[...] United Scrap Metal, buys the pop tabs [...] at market rate and makes an additional charitable contribution. While the price of aluminum changes regularly, we receive an average of 40 to 55 cents per pound." <a href="https://rmhccni.org/get-involved/pop-tabs/">[source]</a>
          </p>
        </blockquote>

        <div class="row mb-6">
          <div class="col-12 col-xl-8 align-self-center">
            <div class="progress" style="height: 3rem;">
              <div
                class="progress-bar bg-success progress-bar-striped progress-bar-animated"
                role="progressbar"
                :aria-valuenow="(789/789)*100"
                aria-valuemin="0"
                aria-valuemax="100"
                :style="`width: ${ ((789/789)*100).toFixed(0) }%`"
              >
                <span class="lead font-weight-bold">{{ ((789/789)*100).toFixed(0) }} %</span>
              </div>
            </div>
          </div>
          <div class="col-12 mt-3 mt-xl-0 col-xl-4 align-self-center text-right ">
            <span class="lead font-weight-bold text-muted">789/789 lbs</span>
          </div>
        </div>

        <!-- Removed clothes
          <horizontal-line />

          <h2 class="display-4 text-center" id="swag" name="swag">
            Sterling Strong Swag
          </h2>
          <p class="lead">
            Help share Sterling's story by wearing some Sterling Strong Swag 💁‍♀️
          </p>
          <figure class="figure mt-4 mb-4">
            <a href="https://www.bonfire.com/store/sterling-strong/" target="_blank">
              <img src="/i/sterling-strong-swag.png" class="mw-100 p-6">
            </a>
            <figcaption class="figure-caption text-center mt-0 w-75 mx-auto">
              Check out the <a href="https://www.bonfire.com/store/sterling-strong/" target="_blank">Sterling Strong</a> swag. Purchases will go towards Sterling's Foundation.
            </figcaption>
          </figure>
      -->
        <horizontal-line />

        <h2 id="music" class="display-4" name="music">
          "The Sterling Sessions"
        </h2>
        <p class="lead">
          Music was a huge part of Sterling's life even before she was born.
        </p>
        <p>We knew her birth and the first few weeks were going to be chaos. We had both read about babyies exposed to music in-utero were soothed by the same music as newborns. It was worth a shot! Lacksley Castell's "Speak Softly" was Sterling's record of choice (she was probably bored of hearing it by the time she was born). We played it whenever she would have any procedure. We think it helped calm her, and us.</p>

        <div class="text-center my-5">
          <iframe
            align="middle"
            class="mx-auto"
            src="https://open.spotify.com/embed/track/7iyqxcCTBIdHm7vJZoX40D"
            width="300"
            height="80"
            frameborder="0"
            allowtransparency="true"
            allow="encrypted-media"
          />
        </div>

        <p>A lovely music therapist at the hospital offered to customise "Speak Softly" into "Speak Softly Sterling" and asked us to write our own lyrics specifically for Sterling. It was a hit! It's since grown and we produced 3 songs together. We recorded Sterling's heartbeat thanks to a special stephescope, and the music therapist was able to use heartbeat recording in the songs!</p>

        <div class="d-block">
          <a
            class="d-block display-4 mt-6 text-center"
            target="_blank"
            href="https://kingsley.sh/posts/2021/the-sterling-sessions"
          >
            <small class="d-block" style="font-size: 40%;">Listen to</small>
            "The Sterling Sessions"
          </a>
        </div>

        <horizontal-line />

        <p class="lead text-center">
          Here's a playlist of some of the music Sterling got to enjoy. Beautiful songs about love, happiness, and sorrow, wrapped up in an upbeat tempo, and enjoyed forever.
        </p>
        <p class="lead text-center">
          May they bring you smiles/wiggles like they brought us.
        </p>
        <div class="text-center my-5">
          <iframe
            src="https://open.spotify.com/embed/playlist/1qp5AfSmmKLwefGyaJfLxP"
            width="300"
            height="380"
            frameborder="0"
            allowtransparency="true"
            allow="encrypted-media"
          />
        </div>

        <p class="text-center display-4 h1 mt-7">
          Let's keep Sterling's <br>legacy a jammin'
        </p>
        <horizontal-line type="heart" />
      </div>
    </main>

    <footer id="footer" class="footer">
      <!--<div class="container-fluid px-5 px-lg-7 px-xl-10 footer__content">
        <div class="row">
          <div class="col-md-6">
            <h2 class="text-uppercase">
              Donate
            </h2>

          </div>
          <div class="col-md-6 pl-xl-10">
            <h2 class="text-uppercase">
              Thank You
            </h2>
            <ul class="pl-0">
              <li>adasd asdasd &mdash; dfdfgdfg dfgdg</li>
              <li>asdasd asdasd &mdash; werw werwer</li>
              <li>asdasd asdasd &mdash; sfsdfsdf sdfsdf</li>
              <li>asdasdas asdasd &mdash; fghfh fghfgh</li>
            </ul>
          </div>
        </div>
      </div>-->

      <div class="container-fluid px-5 px-lg-7 px-xl-10 footer__socket">
        <ul class="text-center text-muted mb-5" style="font-size: 1.1rem;">
          <li class="pb-3">
            👏
          </li>
          <li>t-shirts, logos, banner designs &mdash; Becca Smith</li>
          <li>
            Sterling's photos &mdash; <a href="https://wendyswansonphotography.zenfolio.com/" target="_blank">Wendy Swanson Photography</a>
          </li>
          <li>
            Beads of Courage photos &mdash;
            <a href="https://www.carihughesphotography.com" target="_blank">Cari Hughs Photography</a>
          </li>
        </ul>

        <p class="text-center mb-0">
          Sterling Strong Foundation, Inc. is a recognised <span class="non-profit">501(c)(3)</span> organisation <small />
          <strong class="d-none text-muted">Your donation is tax deductible.</strong>
          <small class="d-block">Tax ID/EIN: 87-2210499 | Business ID: 202108271518733</small>
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
import { ModelStl } from 'vue-3d-model' // eslint-disable-line vue/no-unused-components

export default {
  components: { ModelStl }, // eslint-disable-line vue/no-unused-components
  data () {
    return {
      lights: [{
        type: 'DirectionalLight',
        position: {
          x: 1,
          y: 1,
          z: 1
        },
        color: 0xFFFFFF,
        intensity: 1
      }, {
        type: 'DirectionalLight',
        position: {
          x: 0,
          y: -1,
          z: -1
        },
        color: 0xFFFFFF,
        intensity: 1
      }],

      controlsOptions: {
        enablePan: true,
        enableZoom: false
      }
    }
  },

  mounted () {
    this.createBalloons(5)
  },

  methods: {
    getRandomStyles () {
      const random = num => Math.floor(Math.random() * num)
      const r = random(255)
      const g = random(255)
      const b = random(255)
      const mt = random(200)
      const ml = random(200)
      const dur = random(5) + 5
      return `
        background-color: rgba(${r},${g},${b},0.7);
        color: rgba(${r},${g},${b},0.7);
        box-shadow: inset -7px -3px 10px rgba(${r - 10},${g - 10},${b - 10},0.7);
        margin: ${mt}px 0 0 ${ml}px;
        animation: float ${dur}s ease-in infinite
      `
    },

    createBalloons (num) {
      const containers = document.querySelectorAll('.balloon-container')

      for (const container of containers) {
        for (let i = num; i > 0; i--) {
          const balloon = document.createElement('div')
          balloon.className = 'balloon'
          balloon.style.cssText = this.getRandomStyles(); container.append(balloon)
        }
      }
    }
  }
}
</script>

<style></style>
