# pxt-katakana
---
This library make it possible to show characters of Katakana in half-width.

## Basic Usage
---

Method
```
katakana.showString(string, integer)
```

- string: characters to show
- integer: speed of scrolling

the first argument is the characters to show. The default is blank. And the second argument is the speed of scrolling, the unit is ms. The default is 500ms. The second argument can be omitted.

You can use the half-width characters below and space.
```
 ｱｲｳｴｵｶｷｸｹｺｻｼｽｾｿﾀﾁﾂﾃﾄﾅﾆﾇﾈﾉﾊﾋﾌﾍﾎﾏﾐﾑﾒﾓﾔﾕﾖﾗﾘﾙﾚﾛﾜｦﾝｧｨｩｪｫｬｭｮｯﾞﾟ0123456789-,.､｡!?｢｣[]()<>#$%&'ABCDEFGHIJKLMNOPQRSTUVWXYZ^`_･*+ｰ=\\/:;@
```

You cannot use the half-width characters below and full-width characters.
```
abcdefghijklmnopqrstuvwxyz{|}~¥
```

If you want more information, please go to our web site(http://mbit.fun/).

## Example
---

It works.
```
katakana.showString("ｶﾀｶﾅ")

katakana.showString("ｶﾀｶﾅ",1000)
```


It does not work.
```
katakana.showString("カタカナ")

katakana.showString("カタカナ",1000)
```

## License
MIT

## Supported targets

* for PXT/microbit
