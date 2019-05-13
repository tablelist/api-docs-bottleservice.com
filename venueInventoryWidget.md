## Venue Inventory Widget

Use our inventory widget to display inventory for a particular venue:

### Installation

First you'll need to include the following script on your page:
```js
<script src="https://widgets.tablelist.com/widgets/embedded/tablelist-widgets-core.min.js"></script>
```

Next you'll need to add a `<div>` tag where you want the widget to load:

```html
<div id="inventory-list-widget"></div>
```

Lastly, you'll need to instantiate the widget:

```js
window.TablelistWidgets.onReady(function() {
  var inventoryListWidget = new window.TablelistWidgets.widgets.InventoryListWidget('#inventory-list-widget');

  inventoryListWidget.init({
    venueId: '{{ venueId }}',
    theme: 'theme-dark', //use 'theme-light' for light background pages
    trackingID: '{{ trackingID }}' //Tablelist Affiliate Tracking ID
  });
});
```
