---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: header-2
    logo: "/uploads/2018/06/21/portfolio_lg.JPG"
    navigation:
      - link: "/"
        link_text: Intro
      - link: "#profile"
        link_text: Profile
      - link: "#project"
        link_text: Project
      - link: "#fork"
        link_text: Fork
      - link: "#interest"
        link_text: Interest
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
      url: https://wldud01.github.io/myblog/#profile
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
     <strong>Project</strong><br>
          <span class="light">&nbsp;&nbsp;&nbsp;" My Team project "</span></span>
    content:
      <p><br>
          <ol>
            <li>Book page - 가장 저렴한 가격의 책을 찾아주는 사이트</li>
            <ul><small><li>Position  기획 & UX/UI & front-end <br> React를 이용한 첫 프로젝트 / 긴 로딩시간이 조금 아쉬움<br>
          <a href="https://github.com/wldud01/OpensourceClass/tree/main/prev_book_page">here</a></li></small></ul>
            <li>AI - 진행중 ( Deeplearning )</li>
            <li>Dash board web - 진행중( Spring boot )</li>
            <li>Meta bus - 진행중 ( Unity ) </li>
          </ol>

        </p>
    media:
      image: "/uploads/2018/06/21/Project.png"
      alt_text: Project
  - template: 1-column-text
    block: one-column-1
    slug: Fork
    headline: <h3 id ="fork_title"> < Fork - I'm interested in > </h3>
    content: 

      <p id ="fork_text" >
          AI - 프로젝트를 위해 공부 해야하는 분야&nbsp;&nbsp;&nbsp;<a href="https://github.com/wldud01/pymldg-rev">Machine learning guide</a><br>
          Spring boot - 현재 공부 중인 분야&nbsp;&nbsp;&nbsp;<a href="https://github.com/wldud01/spring-boot">Spring boot guide</a>
        </p>
  - template: full-width-media-element
    block: media-1
    image: "/uploads/2018/06/21/bodyprofile.png"

    caption: 
     <figure><img/></figure>
    slug: Interest
    
  - template: detail-content
    block: text-1
    headline:  <h2>Interest</h2><br>
        <p id ="interest_title">" Challenge Something New "</p>
    content:
     <p id = "interest_text"><strong>Exercise</strong> - 아침 저녁으로 4시간 & 1시간까지는 걷기<br>
          <strong>Baking</strong> - 빵을 너무 좋아해서 제과 제빵 자격증 취득 <br>
          <strong>Flower</strong> - 꽃을 만들고, 배우면서 일하는 중 <br>
          <strong>Video content</strong> - 예전에 너무 잘 먹음 -> 유튜브 contents -> over 22k view </p>
  - template: simple-footer
    block: footer-1
    content: <figcaption>Contact<br>yunjiyeong0106@gmail.com</figcaption>
---
