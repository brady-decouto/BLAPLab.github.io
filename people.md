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

<!-- Arfa Mubeen -->
<div class="person grad">
  <img src="{{ '/assets/img/Mubeen.png' | relative_url }}" alt="Arfa Mubeen">
  <div class="person-text">
    <h2 class="person-name">Arfa Mubeen, M.Phil.</h2>
    <p>
      Arfa is currently a first-year PhD student in Sport Psychology under the supervision 
      of Dr. DeCouto, with a background in Psychology. Her research interests include motor 
      learning, with a particular focus on the effectiveness of different types of assistance 
      in the acquisition of motor skills. Her M.Phil. research focused on elite athletes, and
      in her PhD, she plans to work with novice athletes. She is interested in applying her 
      research to optimize skill learning and performance in sport and physical activity contexts. 
    </p>
  </div>
</div>

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

<!-- Elita Odartei -->
<div class="person ra">
  <img src="{{ '/assets/img/Odartei.png' | relative_url }}" alt="Elita Odartei">
  <div class="person-text">
    <h2 class="person-name">Elita Odartei, B.S.</h2>
    <p>
      Elita Odartei is a second-year master’s student in the Florida State University
      Sport Psychology program. With a background in neuroscience, her current research
      interests include the utilization of neurofeedback technology to elevate performance outcomes, 
      the intersection of art and performance psychology, and traumatic brain injury prevention
      and rehabilitation among marginalized athletic populations. Elita is committed to advancing
      empirically grounded, holistic approaches to mental health, performance, and wellness across
      youth, collegiate, and professional sport settings to promote comprehensive care for all. 
    </p>
  </div>
</div>


{% assign ra_students = 
   "Allison Cox,Anjali Kapadia,Cooper Garrard,Edgar Mora,Elita Odartei,Jakob Tweedel,Janos Bjoernvig,Kara Cousino,Keanu Parsa,Michael Avola,Taylor Yanchuk" 
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
