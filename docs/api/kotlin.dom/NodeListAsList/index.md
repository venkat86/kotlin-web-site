---
layout: api
title: NodeListAsList
---
[stdlib](../../index.html) / [kotlin.dom](../index.html) / [NodeListAsList](index.html)

# NodeListAsList
TODO this approach generates compiler errors...
```
class NodeListAsList
```
## Description
```
class NodeListAsList
```
fun Element.addClass(varargs cssClasses: Array<String>): Boolean {
val set = this.classSet
var answer = false
for (cs in cssClasses) {
if (set.add(cs)) {
answer = true
}
}
if (answer) {
this.classSet = classSet
}
return answer
}
fun Element.removeClass(varargs cssClasses: Array<String>): Boolean {
val set = this.classSet
var answer = false
for (cs in cssClasses) {
if (set.remove(cs)) {
answer = true
}
}
if (answer) {
this.classSet = classSet
}
return answer
}

## Members
| Name | Summary |
|------|---------|
|[*.init*](_init_.html)|TODO this approach generates compiler errors...<br>&nbsp;&nbsp;`public NodeListAsList(nodeList: NodeList)`<br>|
|[get](get.html)|&nbsp;&nbsp;`open public fun get(index: Int): Node`<br>|
|[nodeList](nodeList.html)|&nbsp;&nbsp;`val nodeList: NodeList`<br>|
|[size](size.html)|&nbsp;&nbsp;`open public fun size(): Int`<br>|