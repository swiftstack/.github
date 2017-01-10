# SwiftStack Universe

### Current progress
You can track the state of things [here](https://github.com/swift-stack/universe/projects/1).

### Requirements

Everything should work with our [docker image](https://github.com/swift-stack/docker).

## What do we have

### Concurrency

[Fiber](https://github.com/swift-stack/fiber) - cooperative multitasting with non-blocking asynchronous io written in Swift.<br>
We can't wait for Swift's async/await, but when it comes the API won't change much.

### Frontend

> "Standards aren't add-ons to the web. They are the web" - Apple

It's time to use [Web Components](http://webcomponents.org).
Please take a look at [Stencil](https://stenciljs.com) and [Polymer](https://www.polymer-project.org).

### Backend

* Nginx - load balancing, tls proxy and static files ([example](https://github.com/swift-stack/examples/tree/master/nginx-spa))<br>
* [HTTP](https://github.com/swift-stack/http) - high performance asynchronous api ([example](https://github.com/swift-stack/examples/tree/master/http))

A pure Swift solution will be available after TLS module is ready.<br/>

### Database

* [Tarantool](https://github.com/swift-stack/tarantool) with [swift stored procedures](https://github.com/swift-stack/tarantool#tarantool-module) support ([example](https://github.com/swift-stack/examples/tree/master/tarantool))<br>

### Contribute

Any contributions are very welcome. If you have any question feel free to open an issue.<br/>
