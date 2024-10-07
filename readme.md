Web applications are at every corner of modern society.
The largest web applications can serve millions of people.
These applications are expected to be strongly reliable and stable yet capable of evolving to adapt to their users.
At such a scale, these expectations can only be met through huge resources and time.
For this reason, it is critical to further our ability to understand the structure of web applications to ease their maintenance and evolution.

In this thesis, we explore web application structure through a variety of lenses: web testing, data extraction, and web analytics.
Our study shows that many web-related research efforts, regardless of the research domain, suffer greatly from the lack of a generic fully unsupervised web application abstraction inference solution. We attempt to develop such a solution iteratively, leading to three main contributions:

*SFTM*: Similarity-based Tree Matching, an algorithm allowing the matching of two web pages. Compared to traditional, generic Tree Matching algorithms, SFTM produces better matchings for computation times several orders of magnitude smaller.

*ERRATUM*: An approach allowing the repair of locators on web applications. ERRATUM strongly improves the quality of repairs with little to no overhead. We integrated ERRATUM into a widely used open-source testing framework.

*APPSTRACT*: An approach to automatically generate an abstraction of a web application. APPSTRACT combines intra-page abstraction and inter-page abstraction using SFTM to generate robust and semantically-rich application-wide locator identifiers for each element of a webpage.

We believe our work opens up many new possibilities in a variety of research domains. In particular, the computation speed of SFTM enables approaches that were previously impractical with generic tree matching, and the approach we describe in APPSTRACT could pioneer new web analytics or web testing generation solutions based on web application abstraction.