# jfa-posts-accordion
A wordpress plugin to show posts in an accordion for a category. Intended for the Objections category, but usable on any category. (see glf master outline)

* Creates a shortcode [posts-accordion category="Category Name"].

* Uses ajax via Wordpress Rest API to retrieve content when node is clicked.

* Cache nodes that have been opened (with wp transient api?)

* Uses collapse-o-matic plugin for show/hide functionality.

* Bypasses the normal url, in this case /section/"category name", because permalink settings have a category base of section.

