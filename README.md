# js-iContextMenu

The ContextMenu plugin offers numerous options:

##actions: a collection of actions (functions) to be executed when a corresponding menu item is clicked
##menu: the ID of the element that represents the menu XHTML
##stopEvent: do you want the element's default action to be stopped when the menu is triggered to display? (defaults to true)
##targets: element(s) that should show the menu when triggered (defaults to the document body)
##trigger: event that triggers the menu to display (defaults to "contextmenu", or right-click)
##offsets: an {x,y} object with corresponding x and y offsets (x and y both default to 0)
##onShow: a function to execute when the menu is shown
##onHide: a function to execute when the menu is hidden
##onClick: a function to execute when a menu item is clicked

Beyond these initial options, the ContextMenu class also provide some useful methods:

##disable: disables the context menu
##enable: enables the context menu
##disableItem: disables a given menu item
##enableItem: enables a given menu item

