---
title: Who We Are
feature_text: |
  A demo of Markdown and HTML includes
feature_image: "https://github.com/Coding-for-Social-Service/coding-for-social-service.github.io/blob/master/assets/images/Group-photo2.jpg?raw=true"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---

### Cougars Care has provided:

* Over $50,000 in grants of food, class fees, sports fees, school supplies, as well as numerous other tangible requests
* Grants and services to over 2000 students and staff
* Allowed over 100’s of students to continue to take classes by helping to pay for their class fees
<br>
### More About Cougars Care:
Cougars Care is a non-profit organization that was created at Coronado High School in order to help meet the tangible needs of students that present themselves every day.  In 2005 and 2006, conversations began among the administration about how Coronado would be able to assist with the needs of students as the staff at Coronado was continually being inundated with requests for help with sports fees, class fees, school supplies, requests for food, graduation expense requests, as well as countless others.  By law, we couldn’t simply transfer money from our student government accounts for example into other accounts even though compassion abounded and staff and students felt the desire to respond to the numerous needs brought forth.  Meanwhile, our free and reduced lunch population had grown from single digits to approaching fifty percent. 

Conversations begun by the administration spurred by an idea borrowed from a fellow high school in Longmont was the genesis of Cougars Care.  Susan Humphrey, the principal at Coronado High School, approached me and asked me to do some research on how to begin an in house foundation that could respond to the needs of our students.  After a few months of research and processing how to respond well to our community, I was given the charge to begin Cougars Care. 

Cougars Care began with humble beginnings and a few hundred dollars to respond to needs.  Our immediate task was to educate the staff and students about Cougars Care.  It has never been designed to be an organization that worked behind the scenes.  Our goal is for every staff member and student to be aware of Cougars Care and have an idea of how to access its services. 

A student committee was formed in order to engage in the process of assisting its community.  The Cougars Care committee is always open to any staff or student.  Its goal is to, by consensus, determine the most prudent and compassionate way to respond to our fellow students and staff in need. 

The process of requesting a grant from Cougars Care is always confidential and safe for those requesting help.  If a student finds himself or herself in need and is unable to pay a class fee for example, he/she approaches any staff member and requests assistance.  An application is filled out in conjunction with that staff member while the staff member verifies the need.  Then, the request is submitted to Cougars Care Committee confidentially.  The only people to be aware of the actual name of the student requesting the grant are myself, the staff member who has signed the application, and our business office personnel that transfer the money into a particular account.  Though the student committee has the responsibility to decide to fund the grant or not, they do so knowing the details of the request but not the name of the individual. 

When the Cougars Care Committee considers a grant request, we hold two values dear.  First, we consider that no grant request has greater value than another.  We consider all requests to have value.  Therefore, a request for track shoes is not less or more important than a request for assistance with a class fee.  Second, we want every participant on every level to be involved and have ownership on every level.  Therefore, we never grant 100% of a request.  We always ask the person requesting to take ownership in their request.  Typically we will pay 50% of a request and ask the participant to pay 50% or we will pay 100% and ask the individual to volunteer between 2 to 6 hours in the class or area that he/she is asking for help with.  For example, if Cougars Care is granting a request for an art fee, and 100% of the grant is paid, we ask the individual to volunteer a few hours in the art room.  Further, as another step of continued ownership, Cougars Care doesn’t transfer money to the appropriate account until the individual has paid their portion or volunteered their hours. 

However, there is one exception to the deliberative process that takes place.  If a student finds themselves in need of food, clothing or school supplies, those requests are met immediately by any staff member on campus. 

With on campus and community fundraising as well as tremendous support from the Coronado staff, Cougars Care has been fortunate enough to have a significant impact within our community.  Since its beginning, Cougars Care has granted in excess of $50,000 of fees, supplies, and food to its students and staff.  Further, it has helped 100’s of students and staff at Coronado.  Educationally, Cougars Care has helped more than 500 students pay for class fees and stay in classes, which they would have previously been forced to drop.  Moreover, Cougars Care as achieved its goal of becoming a known entity on our campus as an avenue for assistance for anyone in need. 

While Cougars Care has tried its best to impact the Coronado community, its vision is to duplicate itself throughout the district and be a model for other schools.  To this end, we will continue to serve our community and spread the vision.
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
