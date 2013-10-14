Tree
====

## Tree extends Backbone.js with the following view types:
* Tree.BaseView: extends Backbone.View with render, load, and dispose methods. Provides hook methods that define the way templates are fetched, and compiled. 
It also allows to define before, and after render methods.
* Tree.ContainerView: extends Tree.BaseView. Allows the management of other views through the concept of "regions".
* Tree.StackedView: extends Tree.BaseView. Allows the management of other views through the concept of "card deck". 
Useful for creating carousels, tabs, etc. Can be seen as a special case of ContainerView where all the views map
to only one region.
* Tree.ListView: extends Tree.BaseView. Inspired by Marionette.js's CollectionView, 
* Tree.GridView: extends Tree.BaseView. Provides a wrapper on top of dynamic bin-packing layout libraries such as Packery
http://packery.metafizzy.co/

## Roadmap
* Version 0.1: BaseView, ContainerView. Test covergae at least of 85%.
* Version 0.2: ListView, PubSub mixins. Test covergae at least of 85%.
* Version 0.3: StackedView, GridView. Test coverage at least of 85%.
* Version 0.4: Integration with Effeckt.
* Version 0.5 to 1.0: TBD
