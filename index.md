# Welcome to the University of Ottawa Physics Demonstration wiki page!

### Browsing demonstrations
Lecture physics demonstrations available at the university of Ottawa can be found on this site.  They are sorted following the [http://physicslearning.colorado.edu/bib/bibMain.asp PIRA Demonstration Classification Scheme] (see the list of topics on the left side of the page).  You can also use our search engine located at the top of this page.

### Borrowing a demonstration for a lecture
If you need to borrow a demonstration for your class, please contact the 1st year laboratory staff in person at STM 377, by phone at x6766, or [mailto:phylab@uottawa.ca by email] at least 48 hours before your lecture.

{% for demo in site.demos %}
  - [{{ demo.title }}]({{ site.url }}{{ demo.url }})
{% endfor %}
