---
pageClass: about-page
description: "The biography and information about me."
avatar: /ghost.jpg
head: "Ghostt"
info: "1-4-1"
interests: "Hunt Down Makarov"
socials:
  - title: github
    link: https://github.com/joyboyid
  - title: email
    link: "mailto:joyboy[at]unram.co.id"
  - title: wazap
    link: https://wa.me/085339357795
# actions:
#   - text: Projects
#     link: /projects/
#   - text: Blog
#     link: https://github.com/mtobeiyf
#   - text: CV
#     link: /article/
footer: Made with ♥ by Fing. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

"el único que puede matar Ghost es Ghost "

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>
