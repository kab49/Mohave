---
layout: post-new
title:  "Cooper's Hawk"
scientific-name: "Acccipiter-cooperii"
intro: "ttt"
date:   2016-05-05 12:34:56 -0600
featured-image: pic11.jpg
author: "Kurt Buzard"

features:
- icon: fa-tree
  title: Habitat
  excerpt: Cooper’s Hawks are forest and woodland birds. These hawks are a regular sight in parks, quiet neighborhoods, over fields, at backyard feeders, and even along busy streets if there are trees around. They are also adaptable in all seasons to forested mountainous regions, especially foothills.
- icon: fa-mouse
  title: Food
  excerpt: Often smallish or medium-sized birds are the preferred food, but also many small mammals and, in more arid vicinities, lizards are regularly taken. Infrequently, frogs may be eaten, as will (rarely) insects and fish in nearly dry watercourse.[2][177] Birds in general form about 50–85% of diet
- icon: solid fa-rocket
  title: Nesting
  excerpt: Cooper's hawk is a solitary bird apart from breeding and rare aggregations during migration. Usually a bulky platform nest is built each year although pairs may reuse a nest for 2-3 years. Egg laying peaks in late April although it can occur as early as febuary. Often about 3–5 eggs are laid every other day, though there can be up to 2 days between the 4th and 5th eggs. Jeveniles depart the nest at about 1 month.
- icon: solid fa-signal
  title: Migration
  excerpt: Cooper's hawks are year-round residents around Las Vegas and in most of the Mohave. Like a majority of diurnal birds of prey in the Northern Hemisphere, Cooper's hawk is a partial migrant. They tend to be most migratory in the north and largely to partially sedentary elsewhere.
my_posts_array:
- image: /images/kestral4.jpg
  title: Mohave Birds
  excerpt: The Mohave desert is on the Pacific flyway and we see many migratory birds in addition to the native desert and riperian birds.
  url: "/mohave-birds.html"
- image: /images/bvp.jpg
  title: Mohave Birding Hotspots
  excerpt: Although the Mohave is mostly desert, and there are desert birds, the majority of the birds are to be found around water, either in a river, spring or lake. Also, since I live in Las Vegas, many are in proximity to my home town.
  url: "#"
- image: /images/mohave-plants.jpg
  title: Mohave Plants
  excerpt: Although many will picture the desert as a wasteland, it is surprisingly full of life, even in the most trying times of the year.
  url: "#"
- image: /images/mohave-flowers.jpg
  title: Mohave Flowers
  excerpt: Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.
  url: "#"
- image: /images/mohave-animals.jpg
  title: Mohave Animals
  excerpt: Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.
  url: "#"
- image: /images/mohave-insects.jpg
  title: Mohave Insects
  excerpt: Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.
  url: "#"
---


<!-- Section -->
	<section>
		<header class="major">
			<h2>Components</h2>
		</header>
		{% include components/features.html features=post-new.features %}
	</section>

<!-- Section -->
	<section>
		<header class="major">
			<h2>Categories</h2>
		</header>
		{% include components/posts.html posts=post-new.my-posts-array %}
	</section>