<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Steve"
      subtitle="Engineering the Fun in Fundamental"
      image="/uploads/IMG_Ice_Rink_20181209_215934_processed.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>I'm just a problem solver for fun.</h3>
          <!--<p>
            <strong>
              Edit this page in<code>/pages/about.vue</code>to fit your needs.
            </strong>
          </p>-->
          <p>
            I love solving problems. Even the unsolvable. 
          </p>
          <p>
            The truth is, we never know what we cannot solve. It's only clear what we can solve, when we solve it. 
          </p>

          <h3>A Jack of all trades and a master of some.</h3>
          <p>
            I've always sought after knowing as much about everything I could. My brain takes a view from above. A look at the BIG picture. 
          </p>
          <p>
            Then, I give it my best shot. 
          </p>
          <p>
            It's not really something to brag about, honestly. Everyone thinks they have the best answers. There's really on solace in the fact that you can be a part of a growing community of those who genuinely thrive to test if they have the best answers. 
          </p>
          <!--<quote-card />-->
          <h3>What to expect in this blog</h3>
          <p>
            My future plans for this blog are to share my thoughts and ideas as well as to listen to your comments about them. The world needs all of us to solve all of the world's problems. You can expect: 
            <ul style="list-style-type:disc;">
              <li>Meta posts about how best to format these blog posts.</li>
              <li>Project posts of serious ideas that I want to implement.</li>
              <li>Philosophical posts about the answers to the BIG questions.</li>
              <li>Rant posts, hopefully twisted into the form of civil community efforts.</li>
              <li>Entertainment posts to include: <ul style="list-style-type:disc;"><li>music</li><li>voice acting</li><li>amateur drawing</li><li>story writing</li></li>
            </ul>   
          </p>
        </div>

        <!--<div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Cool Stuff We Do
              </p>
              <p class="subtitle">
                Sooo Cool
              </p>
              <figure class="image is-1by1">
                <opti-image width="500" height="500" />
              </figure>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Other Cool Things
              </p>
              <p class="subtitle">
                Just as cool
              </p>
              <figure class="image is-1by1">
                <opti-image width="500" height="500" />
              </figure>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                All the cool
              </p>
              <p class="subtitle">
                that is all
              </p>
              <figure class="image is-1by1">
                <opti-image width="500" height="500" />
              </figure>
            </article>
          </div>
        </div>-->
      </template>

      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
// import QuoteCard from '~/components/cards/QuoteCard'
//export default {
//  head() {
//    return {
//      title: `About | ${this.$siteConfig.siteName}`
//    }
//  },
//  components: { QuoteCard }
//}
</script>
