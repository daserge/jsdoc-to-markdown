# Input source code
```js
/** @constructor */
function Greeter(name) {
    setName.apply(this, name);
}

/** @this Greeter */
function setName(name) {
    /** a great name */
    this.name = name;
}

```

* * * 

# jsdoc-parse output
```json
[
  {
    "id": "Greeter()",
    "longname": "Greeter",
    "name": "Greeter",
    "kind": "constructor",
    "memberof": "Greeter",
    "params": [],
    "order": 1
  },
  {
    "id": "Greeter",
    "longname": "Greeter",
    "name": "Greeter",
    "scope": "global",
    "kind": "class",
    "order": 0
  },
  {
    "id": "setName",
    "longname": "setName",
    "name": "setName",
    "scope": "global",
    "kind": "function",
    "params": [],
    "thisvalue": "Greeter",
    "order": 2
  },
  {
    "id": "Greeter#name",
    "longname": "Greeter#name",
    "name": "name",
    "scope": "instance",
    "kind": "member",
    "description": "a great name",
    "memberof": "Greeter",
    "order": 3
  }
]
```

* * * 

# dmd output
```markdown
<a name="Greeter"></a>
### Greeter
**Kind**: global class  

* [Greeter](#Greeter)
  * [new Greeter()](#new_Greeter_new)
  * [.name](#Greeter+name)

<a name="new_Greeter_new"></a>
#### new Greeter()
<a name="Greeter+name"></a>
#### greeter.name
a great name

**Kind**: instance property of <code>[Greeter](#Greeter)</code>  
<a name="setName"></a>
### setName()
**Kind**: global function  
**this**: <code>[Greeter](#Greeter)</code>  
```

* * * 

# Rendered
<a name="Greeter"></a>
### Greeter
**Kind**: global class  

* [Greeter](#Greeter)
  * [new Greeter()](#new_Greeter_new)
  * [.name](#Greeter+name)

<a name="new_Greeter_new"></a>
#### new Greeter()
<a name="Greeter+name"></a>
#### greeter.name
a great name

**Kind**: instance property of <code>[Greeter](#Greeter)</code>  
<a name="setName"></a>
### setName()
**Kind**: global function  
**this**: <code>[Greeter](#Greeter)</code>  
