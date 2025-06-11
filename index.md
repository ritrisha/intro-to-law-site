---
layout: none
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
  document.getElementById("ch1").addEventListener("click", function() {
    window.location.href = "chapter1.html";
  });
</script>
</head>

<body>
<header class="bg-dark text-white p-4 text-center">
  <h1>📘 Meaning of Law</h1>
  <p class="lead">A 3-sub-chapter digital guide built with Jekyll + Bootstrap</p>
</header>

<main class="container my-5">
  <section>
    <h2>What is this site?</h2>
    <p>This website is a static CMS-style project where a multi-page legal document has been converted into accessible, responsive web pages.</p>
  </section>

  <section>
    <h2>Meaning of Law</h2>
    <p>Have you ever felt the necessity of ‘Law’ in your day to day life? Have you seen any one being booked by the Traffic Police for Violating traffic rules? Do you feel the necessity of a birth certificate when a child is born? After death, do you know the importance of a death certificate? In fact, Law affects all aspects of our life. It rules us from cradle to grave. It protects us right from the mother’s womb to our education, service, marriage and other important events of life. Law plays an important role in our daily life, right from buying a newspaper or a bottle of milk or any other big or small item necessary for our life. Law is so important for our life that it becomes necessary to understand various aspects of law viz. What are the sources of Law, what are the kinds of Law and finally its application for the best use of our society.</p>
    <h3>Objectives</h3>
    <p>
      After studying this lesson, you will be able to:
      <ul>
        <li>understand and define the term ‘Law’;</li>
        <li>make a broad classification of ‘Law’;</li>
        <li>identify the various sources of ‘Law’; and</li>
        <li>appreciate the role of Indian Legal System, Judiciary, legal professionals and
Civil Society in the enforcement of Law and administration of Justice.</li>
      </ul>
    </p>
  </section>

  <section id="ch1" class="mt-10 text-center">
    <button class="btn btn-lg btn-success">Start Reading</button>
  </section>

  <section class="mt-5 text-center">
    <button id="lawBtn" class="btn btn-warning">Quote Me Some Law</button>
  </section>
</main>

<footer class="bg-light text-center py-3 mt-5">
  <p>&copy; 2025 | Built with <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>, <a href="https://getbootstrap.com/" target="_blank">Bootstrap</a> & 💻</p>
</footer>
</body>

