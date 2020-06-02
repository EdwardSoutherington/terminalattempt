<<<<<<< HEAD
---
title: Home
---

#Edward Southerington

## Portfolio and CV

the text on the home page


<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
=======
---
title: Home
---

#Edward Southerington

## Portfolio and CV

the text on the home page


<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
>>>>>>> 5b5374c86a77218d21090cc962d751e9880918f2
