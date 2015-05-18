# rowlow.type.text-transform

A little util to take control over text transforms via CSS selectors

## Install

```
    bower install --save rowlow.type.text-transform
```

## Variables

```
    $rowlow-text-transform-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-text-transform-namespace: "namespace-";

    @import "bower_components/rowlow.type.text-transform/main.scss"
```


### HTML
```
    <h1 class="uppercase"></h1>
    <h1 class="lowercase"></h1>
    <h1 class="nocase"></h1>
```

