---
pageClass: home-page
# some data for the components
description: "The biography and information about me."
avatar: /profile.jpg
head: "Kraken"
# info: "Im the Administrator "
# socials:
#   - title: github
#     link: https://github.com/joyboyid
#   - title: email
#     link: "mailto:joyboy[at]unram.ac.id"
# actions:
#   - text: Projects
#     link: /projects/
#   - text: Blog
#     link: https://github.com/joyboyid
footer: i'm a pirates !
---

<AboutCard :frontmatter="$page.frontmatter">

Ini adalah Website Pemantauan Peminjaman Perlengkapan dan Perizinan peminjaman Ruangan di
**Fakultas Kedokteran Universitas Mataram**

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>
