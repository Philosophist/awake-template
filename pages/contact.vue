<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="Contact Me"
      subtitle="Prioritize in this order: Honesty > Clarity > Civility"
      image="/uploads/IMG_Donuts_20190323_163913_processed.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Hello!
              </p>
              <p class="subtitle">
                What can I do for you?
              </p>
              <figure class="image is-1by1 ">
                <opti-image
                  :src="require('~/assets/uploads/IMG_20170608_223545_processed.jpg').src"
                  :srcset="
                    require('~/assets/uploads/IMG_20170608_223545_processed.jpg').srcSet
                  "
                />
              </figure>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent is-8">
            <article class="tile is-child box">
              <contact-form />
            </article>
          </div>
        </div>
      </template>
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <!-- Latest Posts -->
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
import ContactForm from '~/components/ContactForm'
export default {
  head() {
    return {
      title: `Contact | ${this.$siteConfig.siteName}`
    }
  },
  components: { ContactForm }
}
</script>
