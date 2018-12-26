All you need to know about pointer
===
1. If and only if we write int *p, we mean ***P is an uninitialized pointer, pointing to nothing so far.***
2. In other cases 

```
int y = 20;
int *p;
p = &y;
```

```
int y = 20;
int *p = &y;
```

```
int y[2] = {1,2};
