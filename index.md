---
layout: default
title: Home
nav_order: 1
description: "Qlassroom.ai delivers personalized education at scale. This documentation site is hosted on GitHub Pages."
permalink: /
---

# Personalised Learning at Scale
{: .fs-9 }

Resources for Qlassroom.ai 
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

Qlassroom is built for [Qlassroom.ai](https://Qlassroom.ai), an education website. 

### Dependencies

Qlassroom.ai is built on the PERN stack. 

- Postgres
- Express
- React
- NodeJS

### Local installation: 

Run `npm install` on /frontend and /backend directory \

In the /backend directory, you can run:

`npm start`

Runs the app in the development mode.\
Open [http://localhost:4000](http://localhost:4000) to view it in the browser.


---

## About the project

Qlassroom is &copy; 2021-{{ "now" | date: "%Y" }} by [Qlassroom](http://Qlassroom.ai).

### License



### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor at: ?

#### Thank you to the contributors of Qlassroom!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Qlassroom is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/cotldus/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
