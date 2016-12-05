# AngularJS - Deep Routing Example

See demo at http://bennadel.github.io/AngularJS-Routing

For Nested routing like : 

1. www.example.com/level-1
2. www.example.com/level-1/level-2
3. www.example.com/level-1/level-2/level-3

Use

.when( '/:slug', {
})
.when( '/:slug/:child_slug', {
})
.when( '/:slug/:child_slug/:child_child_slug', {
})
