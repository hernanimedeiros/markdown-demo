#Github relative links explanation
For example, you have a repo like the following:

```
project/
    text.md
    subpro/
       subtext.md
       subsubpro/
           subsubtext.md
       subsubpro2/
           subsubtext2.md
```

The relative link to subtext.md in text.md might look like this:
```
[this subtext](subpro/subtext.md)
```

The relative link to subsubtext.md in text.md might look like this:
```
[this subsubtext](subpro/subsubpro/subsubtext.md)
```

 The relative link to subtext.md in subsubtext.md might look like this:
```
[this subtext](../subtext.md)
```

The relative link to subsubtext2.md in subsubtext.md might look like this:
```
[this subsubtext2](../subsubpro2/subsubtext2.md)
```

The relative link to text.md in subsubtext.md might look like this:
```
[this text](../../text.md)
```
