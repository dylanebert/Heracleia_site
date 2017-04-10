# Readme

## General

The page displayed should ALWAYS be index.html.
Every other "page" displayed is actually displayed inside the <div id="body">
of the index.

Internal links are structured as <a class="targetpage" href="#">Link</a>.
The functionality of the link is in the jQuery below. Don't change the href for internal pages.

External links are structured as <a href="example.com" target="_blank">Link</a>.
Remember target=_blank so external links open in a new tab.

## Home

Located in home.html, but you shouldn't have to modify home.html.

The description is loaded from home/description.html.

The carousel captions are in carousel1.html, carousel2.html, and
their images can be modified just by replacing carousel1.png, etc. with the desired image.
To change the number of carousel images, you'll have to modify the code in home.html.

Modify the news in news.html. Keep the formatting consistent and add new news to the top.

## People

All of people is in people.html. The formatting should be clear from what's already there.
If making a person a link, use the formatting used for Fillia's entry, which links to her page.

## Publications

Publications is in publications.html. Use the EXACT formatting for each publication entry.
It will be automatically sorted by date, so it doesn't matter what order you put it in.
The actual date sorting functionality is the UNIX EPOCH DATE. Make sure this is correct. I put
a link to the site I used for this as a comment in the page.

## Internships

This is an external link.