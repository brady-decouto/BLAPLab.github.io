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

{% assign grad_students = "Alec Treacy,Arfa Mubeen,Eli Zemach,Johanna Glaaser,Trey Wood" | split: "," %}
{% for student in grad_students %}
<div class="person grad">
  <img src="{{ '/assets/img/placeholder.png' | relative_url }}" alt="{{ student }}">
  <div class="person-text">
    <h2 class="person-name">{{ student }}</h2>
    <p></p>
  </div>
</div>
{% endfor %}

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
