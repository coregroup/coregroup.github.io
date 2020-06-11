---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find all my papers on [my Google Scholar](https://scholar.google.com.br/citations?user=iVYE88IAAAAJ) or in my [CV (Lattes) in Portuguese](http://lattes.cnpq.br/9474452617185092).

# Recent Publications (selected and in English only)

## 2019

SILVA, P., COSTA, E., AND DE ARAÚJO, J. R. An Adaptive Approach to Provide Feedback for Students in Programming Problem Solving. In Intelligent Tutoring Systems (Cham, 2019), A. Coy, Y. Hayashi, and M. Chang, Eds., Springer International Publishing, pp. 14 – 23. [paper here](https://doi.org/10.1007/978-3-030-22244-4_3)

## 2014

SILVA, P., PINHEIRO, R., AND COSTA, E. A Predictive Model for Video Lectures Classification. In Proceedings of the 7th International Conference on Educational Data Mining, EDM 2014, London, UK, July 4-7, 2014 (2014), J. C. Stamper, Z. A. Pardos, M. Mavrikis, and B. M. McLaren, Eds., International Educational Data Mining Society (IEDMS), pp. 325 – 326. [paper here](https://educationaldatamining.org/EDM2014/uploads/procs2014/posters/1_EDM-2014-Poster.pdf)

DE BARROS COSTA, E., SILVA, E. T., SANTOS, A., AZEVEDO, A. C. S., SILVA, P., SILVA, M. T., ROCHA, H., AND LIMA, C. An agent-based tutoring system for learning propositional logic using multiple linked representations. In 2014 IEEE Frontiers in Education Conference (FIE) Proceedings (2014), pp. 1 – 7. [paper here](https://doi.org/10.1109/FIE.2014.7044342)

## 2012 

COSTA, E., SILVA, P., SILVA, M., SILVA, E., AND SANTOS, A. A Multiagent-Based ITS Using Multiple Viewpoints for Propositional Logic. In Intelligent Tutoring Systems (Berlin, Heidelberg, 2012), S. A. Cerri, W. J. Clancey, G. Papadourakis, and K. Panourgia, Eds., Springer Berlin Heidelberg, pp. 640 – 641. [paper here](https://doi.org/10.1007/978-3-642-30950-2_100)

DE BARROS COSTA, E., SILVA, P., MAGALHÃES, J., AND SILVA, M. An open and inspectable learner modeling with a negotiation mechanism to solve cognitive conflicts in an intelligent tutoring system. In Workshop and Poster Proceedings of the 20th Conference on User Modeling, Adaptation, and Personalization, Montreal, Canada, July 16-20, 2012 (2012), E. Herder, K. Yacef, L. Chen, and S. Weibelzahl, Eds., vol. 872 of CEUR Workshop Proceedings, CEUR-WS.org. [paper here](http://ceur-ws.org/Vol-872/pale2012_paper_8.pdf)

MAGALHÃES, J., DE SOUZA, C. C., SILVA, P., COSTA, E., AND FECHINE, J. M. Improving a recommender system through integration of user profiles: a semantic approach. In Workshop and Poster Proceedings of the 20th Conference on User Modeling, Adaptation, and Personalization, Montreal, Canada, July 16-20, 2012 (2012), E. Herder, K. Yacef, L. Chen, and S. Weibelzahl, Eds., vol. 872 of CEUR Workshop Proceedings, CEUR-WS.org. [paper here](http://ceur-ws.org/Vol-872/srs2012_paper_5.pdf)

ROCHA, R. H. S., COSTA, E. B., BRITO, P. H. S., SILVA, M., SILVA, P, AND PAES, R. B. Improving Construction and Maintenance of Agent-based Applications through an Integration of Shell and Software Framework Approaches. In Proceedings of the 9th National Meeting on Artificial and Computational Intelligence, ENIAC 2012, Curitiba, BR.




{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
