
# OttawaJS Site revamp 2015
Starting point for new Site is from [Start Bootstrap Agency](http://startbootstrap.com/template-overviews/agency/)

The upstream repo has a master branch which is not in sync with the gh-pages branch. So not sure what to do to regenerate css (from less)

## TODO 
* Realign sponsor layout
* Refine header-bg.jpg 
    * source: [page](http://ottawadailyphotos.blogspot.ca/2014/05/a-view-for-malak-karsh.html) 
    * source:[image](http://2.bp.blogspot.com/-JYzGRpIQJlI/U3q2rzEPMtI/AAAAAAAAfFY/Phr_2ENQf8U/s1600/karsh.jpg)
    * Permission
    * Gimp asset
* Add email:info to Contact
* Sponsor images/text/modals
* Rename Contact to:  About Us, or Next Step, Reach Out, Join Us
* Swap Team and About sections
* Better texts: Name frameworks, If you read this far, twee this page, Organizers and you!
* Social links for sponsors and organizers
* Footer links

## DONE
* Change sections (document mapping)
  * Services -> Contact
  * Portfolio -> Sponsors
  * About ant Team are unchanged
* Remove contact section
* Remove unused js (contact form support)
* Colors: swap yellow (for OttawaJS logo yellow)
    * #fed136 -> #f7df1e in css/agency.css, and less/variable.less
    * #fec503 ->

## Regenerate css from less
    
    npm i less
    ./node_modules/.bin/lessc less/agency.less css/agency.css

-----
Original Readme:

# [Start Bootstrap](http://startbootstrap.com/) - [Agency](http://startbootstrap.com/template-overviews/agency/)

[Agency](http://startbootstrap.com/template-overviews/agency/) is a one page agency portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features several content sections, a responsive portfolio grid with hover effects, full page portfolio item modals, a responsive timeline, and a working PHP contact form.

## Getting Started

To use this theme, choose one of the following options to get started:
* Download the latest release on Start Bootstrap
* Fork this repository on GitHub

## Bugs and Issues

Have a bug or an issue with this theme? [Open a new issue](https://github.com/IronSummitMedia/startbootstrap-agency/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/agency/).

## Creator

Start Bootstrap was created by and is maintained by **David Miller**, Managing Partner at [Iron Summit Media Strategies](http://www.ironsummitmedia.com/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2015 Iron Summit Media Strategies, LLC. Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-agency/blob/gh-pages/LICENSE) license.
