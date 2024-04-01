C: Tipos de datos
=====================

```
var a = { prop: 'a' };
var i = 0;
var b = { prop: [] };

while ( i++ < 10000 ) {
  test( Math.random() > 0.5 ? a : b );
}
```

.