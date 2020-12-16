---
title: UCSB CS190J
---

<h1>UCSB CMPSC 190J: Teaching Computer Science </h1>

* [Tutor Program FAQ](/topics/tutor_faq/)
* [Kronos Tips](/topics/kronos_tips/)

<div id="about" data-role="collapsible" data-collapsed="true" markdown="1">
<h2>About this course</h2>

Teaching Computer Science is designed to support the [Computer Science department's Undergraduate Tutor Program](http://cs.ucsb.edu/education/undergrad/undergraduate-tutor-program).
The course is offered to outstanding students who are interning as tutors in CS courses for the very first time. Students enrolled into the course are selected through an application process that typically involves an in person interview. Lecture/discussion surveys current research and best practices in CS pedagogy including student development theories, different pedagogical techniques, and methods for assessing learning. Students gain experience working one-on-one with students, fostering positive learning environments, and providing feedback on student work.

Students who successfully complete this course will earn 4 units towards their major field electives by serving as a tutors. They will also be eligible to apply for paid tutoring positions in lower division undergraduate courses in the following quarters.

</div><!-- about -->



<div id="topics" data-role="collapsible" data-collapsed="false">
  <h2>Other Topics</h2>
  <ul>
   {% for topic in site.topics %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>



<div id="resources" data-role="collapsible" data-collapsed="false">
  <h2>Resources</h2>
  <ul>
   {% for topic in site.resources %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>

