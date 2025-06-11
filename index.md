---
layout: default
title: Introduction to Law
---

<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script defer src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

<style>
  body {
    font-family: "Segoe UI", sans-serif;
  }
  section {
    margin-top: 2rem;
  }
</style>

<script defer>
  document.addEventListener('DOMContentLoaded', function () {
    const btn = document.getElementById('lawBtn');
    if (btn) {
      btn.addEventListener('click', () => {
        alert('Law is reason free from passion — Aristotle');
      });
    }
  });
</script>
</head>
<body>
<header class="bg-primary text-white p-4 text-center">
  <h1>📘 Meaning of Law</h1>
  <p class="lead">A 3-sub-chapter digital guide built with Jekyll + Bootstrap</p>
</header>

<main class="container my-5">
  <section>
    <h2>What is this site?</h2>
    <p>This website is a static CMS-style project where a multi-page legal document has been converted into accessible, responsive web pages.</p>
  </section>

  <section>
    <h2>Browse Chapters</h2>
    <ul class="list-group list-group-flush">
      <li class="list-group-item"><a href="chapter1.html">Chapter 1.1: Meaning and Definition of Law</a></li>
      <li class="list-group-item"><a href="chapter2.html">Chapter 1.2: Classification of Law</a></li>
      <li class="list-group-item"><a href="chapter3.html">Chapter 1.3: Sources of Law</a></li>\
    </ul>
  </section>

  <section class="mt-5 text-center">
    <button id="lawBtn" class="btn btn-success">Quote Me Some Law</button>
  </section>
</main>

<footer class="bg-light text-center py-3 mt-5">
  <p>&copy; 2025 | Built with <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>, <a href="https://getbootstrap.com/" target="_blank">Bootstrap</a> & 💻</p>
</footer>
</body>

