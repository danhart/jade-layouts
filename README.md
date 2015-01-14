# jade-layouts
A template engine that wraps a jade template in a layout. 

Supports the interface provided by layout-fetchter out of the box.

````JS
// Override jade template engine handler
app.engine('jade', require('jade-layouts').renderFile);
````
