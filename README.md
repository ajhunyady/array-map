# array-map

This is the sample implementation of [array-map SmartModule](https://www.fluvio.io/smartmodules/transform/array-map/) offered in binary format. 

ArrayMap flatens an array json object into individual json records:

```
[
    {"a": 1},
    {"b": 2},
    {"c": 3}
]
```

into 

```
{"a": 1}
{"b": 2}
{"c": 3}
```

Note: The smartmodule assumes the input is a `json array`