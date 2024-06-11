---
{
	"title": "Introduction block with image",
	"language": "fr",
	"altLangPage": "gc-intro-image-fr.html",
	"breadcrumbs": [
		{ "title": "GCWeb home", "link": "https://wet-boew.github.io/GCWeb/index-en.html" }
	],
	"dateModified": "2024-06-11"
}
---

<div class="wb-prettify all-pre"></div>

<div class="bg-center bg-cover" data-bgimg-srcset="https://wet-boew.github.io/vocab/wb/utilities#no-image 991w, img/ip-cover-image-1200x726.jpg 992w">
	<div class="container">
		<div class="row">
			<div class="col-md-7">
				<h1 property="name" id="wb-cont">{% if page.language == "en" %}Introduction block with full-width image{% else %}Bloc d'introduction avec image pleine largeur{% endif %}</h1>
				<p>{% if page.language == "en" %}The introduction block pattern introduces the content of a landing page.{% else %}La configuration de conception du bloc d'introduction introduit le contenu d'une page de destination.{% endif %}</p>
				<p><a class="btn btn-call-to-action" href="#">{% if page.language == "en" %}Supertask button{% else %}Bouton de super-tâche{% endif %}</a></p>
			</div>
		</div>
	</div>
</div>

<div class="container">
	<h2>Code sample</h2>
	{% highlight html %}<div class="bg-center bg-cover" data-bgimg-srcset="https://wet-boew.github.io/vocab/wb/utilities#no-image 991w, img/ip-cover-image-1200x726.jpg 992w">
	<div class="container">
		<div class="row">
			<div class="col-md-7">
				<h1 property="name" id="wb-cont">{% if page.language == "en" %}Introduction block with full-width image{% else %}Bloc d'introduction avec image pleine largeur{% endif %}</h1>
				<p>{% if page.language == "en" %}The introduction block pattern introduces the content of a landing page.{% else %}La configuration de conception du bloc d'introduction introduit le contenu d'une page de destination.{% endif %}</p>
				<p><a class="btn btn-call-to-action" href="#">{% if page.language == "en" %}Supertask button{% else %}Bouton de super-tâche{% endif %}</a></p>
			</div>
		</div>
	</div>
</div>{% endhighlight %}
</div>

<div>
	<div class="container">
		<div class="row">
			<div class="col-md-6">
				<h1 property="name" id="wb-cont">{% if page.language == "en" %}Introduction block with half-width image{% else %}Bloc d'introduction avec image demi largeur{% endif %}</h1>
				<p>{% if page.language == "en" %}The introduction block pattern introduces the content of a landing page.{% else %}La configuration de conception du bloc d'introduction introduit le contenu d'une page de destination.{% endif %}</p>
				<p><a class="btn btn-call-to-action" href="#">{% if page.language == "en" %}Supertask button{% else %}Bouton de super-tâche{% endif %}</a></p>
			</div>
			<div class="col-md-6 mrgn-tp-sm hidden-sm hidden-xs">
					<img src="img/825x200.jpg" alt="" class="gc-intro half-width-image"/>
			</div>
		</div>
	</div>
</div>

<div class="container">
	<h2>Code sample</h2>
	{% highlight html %}<div>
	<div class="container">
		<div class="row">
			<div class="col-md-6">
				<h1 property="name" id="wb-cont">{% if page.language == "en" %}Introduction block with half-width image{% else %}Bloc d'introduction avec image demi largeur{% endif %}</h1>
				<p>{% if page.language == "en" %}The introduction block pattern introduces the content of a landing page.{% else %}La configuration de conception du bloc d'introduction introduit le contenu d'une page de destination.{% endif %}</p>
				<p><a class="btn btn-call-to-action" href="#">{% if page.language == "en" %}Supertask button{% else %}Bouton de super-tâche{% endif %}</a></p>
			</div>
			<div class="col-md-6 mrgn-tp-sm hidden-sm hidden-xs">
					<img src="img/banner-520x200.png" alt="" class="pull-right img-responsive thumbnail"/>
			</div>
		</div>
	</div>
</div>{% endhighlight %}
</div>
