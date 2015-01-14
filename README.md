# jade-layouts
A template engine that wraps a jade template in a layout. 

Supports the interface provided by `layout-fetcher` out of the box.

Expects the layout to include a `{{{content}}}` tag to indicate where the view should be rendered.

````JS
// Override jade template engine handler
app.engine('jade', require('jade-layouts').renderFile);
````
