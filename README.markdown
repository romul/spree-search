# Search

This is an extension that adds sort and search support for products inside Spree.
This extension works only with Spree 0.9.x.

## Install
      script/extension install git://github.com/romul/spree-search.git

## Actual state
Production ready. Updated to work with the latest i18n code.

## Functionality
It includes basic name search that is suggested to be putted in the main layout. It can be used through the main page or inside a taxon.
It can be tested using the following route:
/search/test


It includes extended search based on some criteria like name, price and classification it is directly in or below it.
It can be tested using the following route:

/searches/new

It has basic sort support for products, by default the only view that has it working is the result of the extended search, but it can be included in all the rest of the application including the main view and the view by current taxon.

or test the following route:

/price/filter/0

for only price filtering.


## gems needed
activerecord-tableless
searchlogic >= 2.3.3

## Screenshots

Samples to show what you can do with it, (layout customization is not included).

Simple search
<br/><br/>
<img src="http://i498.photobucket.com/albums/rr350/edmundo_vn/spree-search_simple.png" style="border: 1px solid #CCC;" />

Sort support
<br/><br/>
<img src="http://i498.photobucket.com/albums/rr350/edmundo_vn/spree-search_sort.png" style="border: 1px solid #CCC;" />

Advanced search
<br/><br/>
<img src="http://i498.photobucket.com/albums/rr350/edmundo_vn/spree-search_advanced.png" style="border: 1px solid #CCC;" />

