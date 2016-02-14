# ag23-lazy-ts
Lazy initialization for TypeScript and JavaScript.

## Usage

```ts
const lazyHelloWorld = new ag23.Lazy<string>(() => "Hello, World!");
console.log(lazyHelloWorld.toString());
const helloWorld = lazyHelloWorld.value;
console.log(lazyHelloWorld.toString());
```

Console output:  
```
Value is not created.  
Hello, World!
```
