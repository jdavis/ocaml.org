<!-- ((! set title OCaml Planet !)) ((! set community !)) -->

#OCaml Planet

The [OCaml Planet](http://planet.ocaml.org) aggregates various blogs
from the OCaml community. If you would like to be added, read the
[Planet subscription HOWTO](http://www.ocamlcore.org/planet/).

<div class="container">
<div class="row">
<section class="span8">

((! cmd script/rss2html http://planet.ocaml.org/rss20.xml !))

</section>
<section class="span4">
<div class="subscribers">

<h3>Subscriptions</h3>

((! cmd script/rss2html --subscribers http://planet.ocaml.org/opml.xml !))

<a href="http://planet.ocaml.org/rss20.xml"
><img src='../img/rss20.png' alt='' /></a>
<a href="http://planet.ocaml.org/opml.xml"
><img src='../img/opml.png' alt='' /></a>

</div>
</section>
</div>
</div>
