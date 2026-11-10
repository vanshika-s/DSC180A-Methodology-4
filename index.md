---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>DSC 180A Methodology Assignment 4</title>
  <link rel="stylesheet" href="{{ '/style.css' | relative_url }}">
</head>
<body>

<header class="hero">
  <div class="eyebrow">DSC 180A · METHODOLOGY ASSIGNMENT 4</div>
  <h1>Capstone Reflections</h1>
  <p>Vanshika Somani</p>
  <p><a href="mailto:vsomani@ucsd.edu">vsomani@ucsd.edu</a></p>
  <div class="pill">Section D29 · Mentor: Stuart Geiger</div>
</header>

<main class="container">

  <h2 class="section-title">My Reflections</h2>

  <div class="cards">

    <article class="card">
      <div class="number">01</div>
      <h3><strong>What is the most interesting topic covered in your domain this quarter?</strong></h3>
      <p>
        One of the most interesting topics we've explored is how LLMs can give different responses based on small changes to a prompt. Through our auditing work, I've become more interested in how factors like gender and ethnicity can influence the advice a model provides, even when the rest of the information stays the same. I found this especially interesting in our college admissions audit, where we looked at how demographic information affected the scores given to applicants.
      </p>
    </article>

    <article class="card">
      <div class="number">02</div>
      <h3><strong>Describe a potential investigation you would like to pursue for your Quarter 2 Project.</strong></h3>
      <p>
        For Quarter 2, I'd like to expand on our current college admissions audit by looking at how LLMs recommend and rank universities for different students. Instead of only giving admission chance scores, we could ask models to classify colleges as reach, target, or safety schools and compare how these recommendations change across student profiles. We could also include more factors such as ethnicity, sexual orientation, gender, and age while keeping academic qualifications the same. This would help us understand whether demographic characteristics influence which colleges students are encouraged to apply to.
      </p>
    </article>

    <article class="card">
      <div class="number">03</div>
      <h3><strong>What is a potential change you'd make to the approach taken in your current Quarter 1 Project?</strong></h3>
      <p>
        One change I'd make is to test more models and run each experiment multiple times. In our current project, we focused on GPT-4.1-mini and found differences in college admission scores based on stated gender. Testing other models would help us understand whether these patterns are specific to one model or appear across different models. Repeating the experiments would also help us see how consistent the results are.
      </p>
    </article>

    <article class="card">
      <div class="number">04</div>
      <h3><strong>What other techniques would you be interested in using in your project?</strong></h3>
      <p>
        I'd be interested in exploring more ways to analyze model responses beyond numerical scores. In our current project, we used statistical tests to compare college admission scores across different groups. For future audits, I'd like to explore methods for comparing longer responses, especially when models provide explanations or recommendations instead of just a score. This could help us identify differences that may not be obvious from numerical results alone.
      </p>
    </article>

  </div>

  <div class="github-link">
    <a class="github-button"
       href="https://github.com/vanshika-s/DSC180A-Methodology-4"
       target="_blank"
       rel="noopener noreferrer">
      View on GitHub
    </a>
  </div>

</main>

</body>
</html>
