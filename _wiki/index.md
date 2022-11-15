---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
regenerate: true
---

## wiki items

  * [[Vim을 배우다]]
    * [[Vimwiki를 배우다]]
    * [[Vim에서 Typescript 개발하기]]
  * [[언어]]
    * [[Clojure]]
  * [[독서]]
    * [[역행자]] 
  * [[코드]]
    * [[Graphql]]
    * [[tmux]]

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public != false %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

