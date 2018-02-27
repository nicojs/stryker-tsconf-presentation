### Code coverage problem

```ts
// Production code
class User{
    constructor(private age: number) { }
    isMature(){
        return this.age >= 18;
    }
}
```

```ts
// Test
var user = new User(24);
assert.equal(user.isMature(), true);
```

Code coverage 100%

<!-- .element class="fragment" -->
