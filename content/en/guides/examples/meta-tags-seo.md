---
title: Meta Tags and SEO
description: In this example we use asyncData and fetch to show you the differences between both methods.
position: 35
category: examples
csb_link: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/03_features/06_meta_tags_seo?
---

`nuxt.config.js` uses the `head` property to show a `title`, `titleTemplate`, `charset` and `description` as well as adding an external stylesheet.

`pages/index.vue` uses the head property as an object.

`pages/fun.vue` uses the head property as a function with dynamic data.

<base-alert type="next">

Learn more in the Features book in the [Meta Tags and SEO](/guides/features/meta-tags-seo) chapter.

</base-alert>

<code-sandbox :src="csb_link"></code-sandbox>