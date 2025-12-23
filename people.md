---
layout: page
title: People
permalink: /people/
---

## Principal Investigator

<div class="person pi">
  <img src="{{ '/assets/img/DeCouto.png' | relative_url }}" alt="Dr. Brady DeCouto">
  <div class="person-text">
    <h2 class="person-name">Brady DeCouto, PhD</h2>
    <h3 class="person-title">Principal Investigator</h3>
    <p>
      Brady is broadly fascinated in all things neuroscience, with a current emphasis on the interaction between technologies and human cognition. Brady has applied his research background concerning the science of expertise (e.g., attention in high-level athletes, skill learning, talent identification) to technological domains, including AI, exoskeletons, health wearables, and brain-computer interfaces (BCIs), to uncover how to best measure and optimize complex cognitive and emotional processes at play during learning and performance. Brady is also highly interested in using neuroscience to study attention during movement and movement planning.
    </p>

    <div class="person-actions">
      <a class="btn" 
         href="https://scholar.google.com/citations?user=GR4n1yEAAAAJ&hl=en&oi=ao" 
         target="_blank" rel="noopener">Scholar</a>

      <a class="btn" href="{{ '/assets/docs/Decouto_CV.pdf' | relative_url }}" download>CV</a>
    </div>

  </div>
</div>

---

## PhD & Thesis Students

<!-- Johanna Glaaser -->
<div class="person grad">
  <img src="{{ '/assets/img/Glaaser.png' | relative_url }}" alt="Johanna Glaaser">
  <div class="person-text">
    <h2 class="person-name">Johanna Glaaser, M.S.</h2>
    <p>
      Johanna is a doctoral candidate whose research investigates the convergence
      of sport psychology and technology, specifically studying how coaches
      implement neurofeedback training to enhance athlete performance. She
      prioritizes an interdisciplinary approach in her work and is pursuing
      graduate certificates in Measurement & Statistics and Athletic Coaching.
      Her aim is to translate data and empirical research into actionable coaching
      tools for supporting athlete development and cultivating high-performance
      environments.
    </p>
  </div>
</div>

<!-- Trey Wood -->
<div class="person grad">
  <img src="{{ '/assets/img/Wood.png' | relative_url }}" alt="Trey Wood">
  <div class="person-text">
    <h2 class="person-name">Trey Wood, B.A.</h2>
    <p>
      Trey is a second-year master’s student in the Sport Psychology program. His
      current thesis investigates the relationship between personality, self-talk,
      and quiet eye duration in target performance. By integrating eye tracking
      technology into his research, Trey adopts a more holistic approach to
      understanding attention and motor learning. He intends to provide empirical
      evidence supporting mental skills that enhance and elevate athletic performance.
    </p>
  </div>
</div>

<!-- Eli Zemach -->
<div class="person grad">
  <img src="{{ '/assets/img/Zemach.png' | relative_url }}" alt="Eli Zemach">
  <div class="person-text">
    <h2 class="person-name">Eli Zemach, B.S.</h2>
    <p>
      Eli is a second-year master’s student in the Sport Psychology program at FSU
      on the thesis track. His research and career interests are at the intersection
      of performer well-being and clinical disorders, as well as the development of
      interventions to enhance the student-athlete experience. He enjoys playing
      golf and soccer in his free time and is pursuing his doctorate beginning fall 2026.
    </p>
  </div>
</div>

<!-- Arfa Mubeen -->
<div class="person grad">
  <img src="{{ '/assets/img/placeholder.png' | relative_url }}" alt="Arfa Mubeen">
  <div class="person-text">
    <h2 class="person-name">Arfa Mubeen, M.S.</h2>
    <p></p>
  </div>
</div>


<!-- Alec Treacy -->
<div class="person grad">
  <img src="{{ '/assets/img/placeholder.png' | relative_url }}" alt="Alec Treacy">
  <div class="person-text">
    <h2 class="person-name">Alec Treacy</h2>
    <p></p>
  </div>
</div>

---

## Research Assistants

{% assign ra_students = 
   "Allison Cox,Anjali Kapadia,Cooper Garrard,Edgar Mora,Elita Odartei,Eli Zemach,Jakob Tweedel,Janos Bjoernvig,Kara Cousino,Keanu Parsa,Michael Avola,Taylor Yanchuk" 
   | split: "," | sort %}
{% for ra in ra_students %}
<div class="person ra">
  <img src="{{ '/assets/img/placeholder.png' | relative_url }}" alt="{{ ra }}">
  <div class="person-text">
    <h2 class="person-name">{{ ra }}</h2>
    <p></p>
  </div>
</div>
{% endfor %}
