---
title: Links for Kids
---

# Reading

[British Library - Discovering Children's Books](https://www.bl.uk/childrens-books)

[Bexley Libraries](https://arena.yourlondonlibrary.net/web/bexley/home)

[Summer Reading Challenge 2020](https://summerreadingchallenge.org.uk/)

[The World of David Walliams - Elevenses with The World of David Walliams](https://www.worldofdavidwalliams.com/elevenses/)

# Videos

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "Videos" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

# Game

[Planet zoo](https://www.planetzoogame.com/)

[Minecraft Wiki](https://minecraft.gamepedia.com)

# History

[English Heritage - The Kids Rule! Guide to the Victorians](https://www.english-heritage.org.uk/members-area/kids/guide-to-victorians/)

[English Heritage - The Kids Rule! Guide to Kings and Queens of England](https://www.english-heritage.org.uk/members-area/kids/kids-rule-guide-to-kings-and-queens/)

[English Heritage - 29 May 2020](https://english-heritage-news.org.uk/1CY6-6VW14-2DWPHQ2X77/cr.aspx): Game On!

[English Heritage - Get inspired with things to do for history lovers](https://www.english-heritage.org.uk/visit/inspire-me)

[English Heritage - 24 May 2020](https://english-heritage-news.org.uk/1CY6-6VJVY-2DWPHQ2X77/cr.aspx): Animations on neolithic and Roman Britain, colouring a medieval monastery

# Home Learning

[Britannica Library](http://library.eb.co.uk/storelibrarycard?id=bexley)

[Math Antics](https://mathantics.com/)

[Bishop Ridley Church of England Primary School - Class Pages](https://www.bishopridleyschool.org.uk/class-pages/)

[Wide Open School](https://wideopenschool.org/programs/family/PreK-5/)

[TED Ed - Earth School](https://ed.ted.com/earth-school)

[Twinkl - Home Learning Hub](https://www.twinkl.co.uk/home-learning-hub)

[White Rose Maths](https://whiterosemaths.com/homelearning/)

# News
[Twinkl - Key Stage 2 - Current Affairs](https://www.twinkl.co.uk/resources/keystage2-ks2/ks2-topics/ks2-current-affairs)

# Geography
[National Geographic - The Compass - Spain](https://email.nationalgeographic.com/H/2/v40000017266053dd29e613ff4bbe5bf30/5e4c1fff-3044-43e3-8a0d-5d2e17046752/HTML)

# Science
[National Geographic Kids - SAM'S ZOOKEEPER CHALLENGE](https://kids.nationalgeographic.com/videos/sams-zookeeper-challenge/?cmpid=org=ngp::mc=crm-email::src=ngp::cmp=editorial::add=FFG_Special_20200531&rid=A71AB196D61531F5C43E8C412346633A)

[National Geographic Kids - 26 May 2020](https://email.nationalgeographic.com/H/2/v40000017253366c6b999ad16e966f4650/484d25b9-06df-49c6-a5da-b1e7ff70145a/HTML): Tigers are terrific, Egypt, making a telescope

# Environment
[National Geographic Kids - Kids vs. Plastic](https://kids.nationalgeographic.com/explore/nature/kids-vs-plastic/)

# Miscellaneous
[Thinkuknow - Band Runner](https://www.thinkuknow.co.uk/8_10/)

[Thinkuknow - Jessie & Friends](https://www.thinkuknow.co.uk/parents/jessie-and-friends-videos/)

# Coding
[Tynker](https://www.tynker.com/#/sign-in-student/)

# Art
[Art Club - Symmetrical Art](https://artclubioanna.wixsite.com/artclub/copy-of-1-op-art-1)

[Tate - Street Art](https://www.tate.org.uk/kids/games-quizzes/street-art): Make your own street art


{% for cat in site.categories %}
  <h1>{{ cat[0] }}</h1>
  <ul>
    {% for post in cat[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
