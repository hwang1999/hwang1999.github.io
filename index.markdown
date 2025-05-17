---
layout: default
title: Home
---

<style>
  html, body {
    height: 100%;
    margin: 0;
    background: black;
    color: white;
  }

  /* 중앙 정렬 영역 */
  .center-wrapper {
    min-height: calc(100vh - 60px);
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .center-wrapper h1 {
    text-align: center;
    font-size: 3rem;
  }

  /* 스킵 링크 숨김 */
  .skip-links {
    display: none;
  }

  /* 상단 메뉴 및 제목 레이아웃 복원 */
  .masthead__inner-wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .site-title,
  .site-nav__link {
    color: white !important;
    text-decoration: none;
  }

  .site-nav__list {
    list-style: none;
    display: flex;
    gap: 1rem;
    margin: 0;
    padding: 0;
  }

  .greedy-nav__toggle {
    display: none; /* 토글 메뉴 버튼 숨김 */
  }
</style>

<div class="center-wrapper">
  <h1>Let's Study Together</h1>
</div>