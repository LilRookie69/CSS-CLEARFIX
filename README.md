# CSS-CLEARFIX

```
/** CLEAR FIX **/

.cf:before,
.cf:after {
    content: " "; /* 1 */
    display: table; /* 2 */
}

.cf:after {
    clear: both;
}

.cf {
    *zoom: 1;
}
```

SOURCE : http://nicolasgallagher.com/micro-clearfix-hack/
