# Perftest

This contains super simple code to demonstrate the baseline performance of rendering a component.

This simple test was run by:

```bash
git clone git@github.com:erkie/ember-component-performance-test.git
cd ember-component-performance-test
npm install && bower install
ember s # open localhost:4200
```

Then open the ember inspector in Chrome Development tools, go to `Render Performance` and reload the page.

Between `0.2 ms and 1.08 ms` to render the component `list-item`.

![](http://i.imgur.com/wmLhLCJ.png)
