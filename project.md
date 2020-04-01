---
layout: default
title: Project
---

<meta property="og:description" content="KOK 개발 블로그 : 프로젝트 페이지">

<div class="project" id="project">
  <h1 class="pageTitle">Project</h1>
  <ul class="posts noList">
      <li>
        <a href="/blog/helloseoul-post/">
          <span class="date">Aug 01 ~ Sep 30, 2019</span>
          <img class="project-img" src="/assets/img/helloseoul.png">
          <h3><a class="post-link nanum" href="/blog/helloseoul-post/">설로</a></h3>
          <p class="project-sub nanum">우리는 서울로 갑니다, 설로</p>
          <p class="project-summary nanum">Open API를 이용한 서울시 관광 어플</p>
        </a>
      </li>
  </ul>
  <!-- Pagination links -->
  <div class="pagination">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path | prepend: site.baseurl }}" class="previous button__outline">Newer Posts</a> 
    {% endif %}
    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path | prepend: site.baseurl }}" class="next button__outline">Older Posts</a>
    {% endif %}
  </div>
</div>
