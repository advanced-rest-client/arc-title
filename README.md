[![Build Status](https://travis-ci.org/advanced-rest-client/arc-title.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/arc-title)  

# arc-title

`<arc-title>` An element that controls ARC's main title element depending on route params

### Example

```
<header>
  <h1>[[title]]</h1>
</header>
<app-location route="{{route}}" use-hash-as-path></app-location>
<app-route route="{{route}}" pattern="/:base" data="{{routeData}}"></app-route>
<arc-title base="[[routeData.base]]" page-title="{{title}}"></arc-title>
```

