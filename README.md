# [OpenIframe](https://github.com/ChechaValerii/openiframe#readme) 1.0.0 
Build ```<iframe>``` and ignore X-Frame-Options, Content-Security-Policy, X-Content-Type-Options, X-Xss-Protection etc. Normally such headers prevent embedding a web page in an ```<iframe>```

* [Documentation](https://doxdox.org/ChechaValerii/openiframe#openiframe.es6.js)


### openiframe.es6.js

### Install
```
 <script src="https://cdn.jsdelivr.net/gh/ChechaValerii/openiframe/openiframe.es6.js"></script>
```
#### OpenIframe(options) 

Creates an instance of OpenIframe.




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| options | `Object`  |  | &nbsp; |
| options.container | `DOM` `string`  | - css selector or DOM element | &nbsp; |
| options.width | `Number`  | - iframe width | &nbsp; |
| options.height | `Number`  | - iframe height | &nbsp; |
| options.append | `Boolean`  | - append iframe to container, prepend by default | &nbsp; |
| options.src | `String`  | - iframe src | &nbsp; |




##### Examples

```javascript
new OpenIframe({
   container: '#header',
   height: 600,
   width: 800
   src: 'https://example.com',
   append: true
});
```


##### Returns


-  iframe Element
  
