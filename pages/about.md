---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: skin03
# set background-position for featured image, "center", "top", "bottom"
position: bottom
# major heading to display over featured image
heading: About this Collection
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 4em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
#^^ yaml frontmatter, metadata about this page
---

## What are skin scents?

Like much of the terminology used to describe fragrance, there is no formal definition of what constitutes 'skin scent'. Also described as "your-skin-but-better" or "perfumes for people who don't want to smell like they're wearing perfume," skin scents are typically characterized by a closer sillage (the distance from which you can smell the fragrance, also called projection), a lack of strongly discernible notes, and fragrance profiles that are generally regarded as being comforting, clean, and light.

American perfume house [snif](https://snif.co/en-ca/blogs/news/skin-scents) describes skin scents as "fragrances designed specifically to mimic the smell of clean, warm skin — like that smell you get when you’re fresh out of a hot shower, before you put on any body oil or lotion," however the 

Given their almost ambiguous nature, collection was built to explore the olfactory information about skin scents that has been consolidated on the fragrance databases Fragrantica and Parfumo


{% include feature/image.html objectid="skin09;skin03;skin04;skin19;skin17" width="75" %} 

## What data was used?

The data in this collection was manually compiled from the fragrance house's website (and occasionally social media), Parfumo/Basenotes, and Fragrantica. 

#### About Accords

The [Accords](https://shidafuonline.github.io/skinscents/accords.html) page shows accords from both Parfumo/Basenotes and Fragrantia. All Parfumo/Basenotes accords were included, however only the top five Fragrantica accords were included as their database can include 10+ accords per fragrance. As these have not been standardized (unlike the notes), there may be duplicates or similar notes when these databases use variations of the same word (such as Parfumo using the accord "animal" and Fragrantica using the accord "animalic"). 

#### About Notes

Certain notes used by the perfumer (especially adjective - note) have been tagged twice to improve fragrance searchability. The name used by the fragrance house on their website was prioritized when discrepancies between names on the fragrance house's website and the databases emerged, with some liberties being taken for clarity. Images are borrowed from the fragrance house's website whenever possible, with alternatives from Parfumo or Fragrantica being used when no stable image link was available. When multiple release years were noted without the fragrance house offering this information directly, the later year was noted.

### About CollectionBuilder CSV

This demo collection features items from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital/), and is build using [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv).

CollectionBuilder-CSV is a "Stand Alone" template for creating digital collection and exhibit websites using Jekyll, given:

- a CSV of collection metadata
- a folder of images, PDFs, audio, or video files

Driven by your collection metadata, the template generates engaging visualizations to browse and explore your objects.
The resulting static site can be hosted on any basic web server.

[CollectionBuilder](https://github.com/CollectionBuilder/) is an set of open source tools for creating digital collection and exhibit websites that are driven by metadata and powered by modern static web technology.
See [CB Docs](https://collectionbuilder.github.io/cb-docs/) for detailed information.

{% include feature/image.html objectid="demo_001" width="75" %} 

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
