---
layout: page
<!-- sidebar: left -->
title:  "GF DF Challah 1.0"
teaser: "lol what was I thinking..."
date:   2016-09-03 
categories: recipes
tags: gf, df, bread, challah, gf_df_challah, gf_df_challah_1_, gf_df_challah_1_0
breadcrumb: true
---
[TL;DR Recipe][TLDR-Recipe]

![final](recipe_images/final.jpg)

I was really missing pika (my co-op) at MIT.  Every night, we share a delightful homemade dinner by one of the rotations of big and little cooks.  Because the meal is made to be shared, it has to cater to everyone's dietary restrictions: omnivore, pescatarian, vegetarian, vegan, gluten-free, low fodmap etc.  In the pika spirit, I embarked to make a gluten-free, dairy-free challah.  I would have gone the whole 9 and done vegan, but I really can't imagine doing challah without an egg wash.  

The Specs1
====================
* `Pikan_ish`: gluten-free and dairy-free
* `Bready`: solid outside, soft inside
* `Asian_ish`: including some special Korean flavor

The Specs2
====================
{% highlight ruby %}
@Pikan_ish gluten-free and dairy-free
@Bready solid outside, soft inside
@Asian_ish including some special Korean 

@return challah

{% endhighlight %}

The Specs3
====================
{% highlight ruby %}
@param Pikan_ish gluten-free and dairy-free
@param Bready solid outside, soft inside
@param Asian_ish including some special Korean 

@throws PanicDance If gluten-free flour sabotages all hopes and dreams 
@return challah

private bread gf_df_challah_1_0(Stuff ingredients) {
{% endhighlight %}

Bare Recipe
====================

1. 2T `Yeast` + 2t `Sugar` + 1.5C `Warm Water`: let **froth** for ~5min
2. 2T `Sugar` + 1.5t `Salt` + 0.5C `Coconut Oil` + 6 `Eggs`: **mix** at medium speed until combined
3. Combine *Yeast Mixture*+*Other Wet Ingredients*
4. /+6C *Gluten-Free Flour Mix* (4C `Rice Flour`+ 1.33C `Potato Flour` + 0.66C `Almond Flour`): **slowly** add to *All the Wet Ingredients*
5. Attempt to **knead** for about 8min == **FAIL**
6. **Squirt** into muffin tins, while sandwiching a squirt of `팥` (maybe 2C total?)
7. **Proof** for 45min; **pray** for mercy
8. /+1 `Egg`: **eggwash**
9. **Bake** for 40min at 375F(135Celsius)
10. **Cool** for 10min; **Sample**; **Dump**

Recipe with Pictures
====================
![yeast](recipe_images/2yeast.jpg)
1. 2T `Yeast` + 2t `Sugar` + 1.5C `Warm Water`: let **froth** for ~5min
![wet](recipe_images/3wet.jpg)
2. 2T `Sugar` + 1.5t `Salt` + 0.5C `Coconut Oil` + 6 `Eggs`: **mix** at medium speed until combined
3. Combine *Yeast Mixture*+*Other Wet Ingredients*
{% include image.html url="recipe_images/1gf_flour.jpg" description="I trusted you, internet..." %}
{% include image.html url="recipe_images/4mix.jpg" description="added flavor" %}
4. /+6C *Gluten-Free Flour Mix* (4C `Rice Flour`+ 1.33C `Potato Flour` + 0.66C `Almond Flour`): **slowly** add to *All the Wet Ingredients*

{% include image.html url="recipe_images/5squirt.jpg" 
description="The batter was way too wet, so I had to think quickly.  The only thing that made sense to me was to control the slop by putting it into baggies" %}
5. Attempt to **knead** for about 8min == **FAIL**

{% include image.html url="recipe_images/6pat.jpg" description="lol. looks like dooky" %}
6. **Squirt** into muffin tins, while sandwiching a squirt of `팥` (maybe 2C total?)
![proof](recipe_images/7proof.jpg)
7. **Proof** for 45min; **pray** for mercy

![proof](recipe_images/8eggwash.jpg)
8. /+1 `Egg`: **eggwash**
![bake](recipe_images/9bake.jpg)
9. **Bake** for 40min at 375F(135Celsius)
{% include image.html url="recipe_images/final.jpg" description="I hope I never have to taste this ever again" %}
10. **Cool** for 10min; **Sample**; **Dump**


Code Review
====================
* `Pikan-ish`: I didn't cave into adding any gluten or dairy. [
![checkmark]({{ site.baseurl }}/assets/img/check.jpg)
]
<!-- ![checkmark]({{ site.url }}/assets/check.jpg) -->
* `Still bready`: It was super dense and not very tastey at all. [ X ]
* `Asian-sh`: I added some 팥 (Korean red bean), so I guess it had that going for it [
![checkmark]({{ site.baseurl }}/assets/img/check.jpg)
]

TODO
====================
* Do something else

<!-- [jekyll-docs]: http://jekyllrb.com/docs/home -->
<!-- [TLDR-Recipe]: /about/ -->
[TLDR-Recipe]: /recipes/gf-df-challah-1_0/tldr.html
