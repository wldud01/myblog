---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: header-2
    logo: "/uploads/2018/06/21/portfolio_lg.jpg"
    navigation:
      - link: "/"
        link_text: Intro
      - link: "#swap"
        link_text: Profile
      - link: "#customize"
        link_text: Project
      - link: "#responsive"
        link_text: Interest
      - link: "#blocks"
        link_text: Fork
    cta:
      url: https://github.com/wldud01
      button_text: My Git
  - template: hero-banner-w-image
    block: hero-2
    slug: Intro
    headline: Hello! <br><strong><small>I am</small><br>" Creator "</strong>
    content:
      Creator is a someone who creates new contents.<br>
      I want to complete my own contents in my field.
    cta:
      enabled: true
      url: https://github.com/wldud01
      button_text: "Start "
    image:
      image: "/uploads/2018/06/21/Intro_p2.png"
      alt_text: Product Shot
    background_image: "/uploads/2018/06/21/background.png"
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: Profile
    headline:
     <strong>My Profile<span class="light">&nbsp;</span></strong><br>
            <span class="light">&nbsp;&nbsp;&nbsp;&nbsp; " Who am I? "</span>
    content:
         <p>
            <ul>
              <li> Name - 윤지영 </li>
              <li> Major - 컴퓨터공학전공</li>
              <li> Grade - 3</li>
            </ul><br>
          </p><hr>
          <p><br>
            <h2><span class="light"><strong>Language Experienced<span class="light">&nbsp;                    </span></strong><br></h2>
            <ul><br>
              <li>Html</li><div class="progress-bar"><div class="Hprogress"></div></div>
              <li>CSS</li><div class="progress-bar"><div class="Cprogress"></div></div>
              <li>Javascript</li><div class="progress-bar"><div class="Sprogress"></div></div>
              <li>Java</li><div class="progress-bar"><div class="Jprogress"></div></div>
              <li>React</li><div class="progress-bar"><div class="Rprogress"></div></div>
            </ul><br>
          </p>
    media:
      image: "/uploads/2018/06/21/profile_me.jpg"
      alt_text: uBuild Blocks Mock-Up
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: Project
    headline:
      <strong>Customize Blocks</strong><span class="light">&nbsp;to make quick
      edits throughout your new site</span>
    content:
      Each block comes with custom Front Matter that can be edited in
      Forestry CMS.
    media:
      image: "/uploads/2018/06/21/edit.gif"
      alt_text: Customize Blocks
  - template: 1-column-text
    block: one-column-1
    slug: Interest
    headline: 16 Fully Responsive Design Blocks
    content: |
      The Design Blocks can be used without Forestry but to harness the power
      of Blocks we recommend using <a href="https://forestry.io">Forestry</a>. Once the site is imported you can immediately
      create new sites and make them fully customizable.
  - template: full-width-media-element
    block: media-1
    image: "/uploads/2018/06/21/theme.png"
    caption: All Available Blocks
    slug: Fork
  - template: detail-content
    block: text-1
    headline: Steps to Build a Site!
    content:
      <p>uBuild is an open-source Jekyll based demo that doubles as a builder tool inside the Forestry content manager.</p><ol><li><p><a href="https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll">Import this demo in Forestry</a>.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
      article</a> and create your own Blocks.</p></li><li><p>Add and customize the available Blocks and preview them as you go along.</p></li></ol>
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎ in Canada
---