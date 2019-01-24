---
title: Workshop-2019
feature_text: |
  Agenda
feature_image: "/assets/AIinPharma.jpg"
excerpt: "A demo of Markdown and HTML includes"
aside: false
---

### Agenda

*  9:30 a.m. Breakfast/Refreshment

* 10:00 a.m. Opening remarks
	-Dr.Jiajie Zhang, Dean, School of Biomedical Informatics (SBMI), UTHealth
* 10:15 a.m. CHSP Challeneges 
* 10:25 a.m. Biomedical Challenege: Driver Disease Mutstaions and Drug Combinations
* 10:35 a.m. Data sharing or Model Sharing?
* 10:45 a.m. A Framework for Similarity-based Predictions
* 10:55 a.m. Research Overview: Network-Based & Baseyian Approaches for Biomedical Data Analysis

* 11:05 a.m. Coffee Break

* 11:20 a.m. Depression Monitoring via Dynamic Vocal Biomarkers
* 11:30 a.m. Deep Leanring Reasearch at Information Innvoation Lab
* 11:40 a.m. Data Analysis at Texas A&M (DATA Lab) 
* 11:50 a.m. Title TBD
* 12:00 p.m. NLP Lab Introduction 

* 12:10 p.m. Group Picture

* 12:20 p.m. Lunch Break

*  1:30 p.m. Practical Applications of Homomorphic Encryption
*  1:40 p.m. An Information-Theoretic Approach to Data Clustering
*  1:50 p.m. Literature, Ontology, Gene Network 
*  2:00 p.m. Discovering Underlying Concepts with Tensor Factorization
*  2:10 p.m. Learning COmplex Systems under Data Scarcity 

*  2:20 p.m. Coffee Break

*  2:35 p.m. Linear Optimization and Ranking Algorithms
*  2:45 p.m  Metric Learning Approach for Representation Learning
*  2:55 p.m. Title TBD

*  3:05 p.m. Group Discussions

*  4:00 p.m  Summarization Session

*  5:30 p.m. Dinner at Kata Robata, 3600 Kirby Dr.#H, Houston, TX 77098 

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
