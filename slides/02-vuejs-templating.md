---
marp: true
paginate: true
footer: Adrien Bouyssou (macdrien.github.io)
transition: push
---

# VueJS templating introduction

---


## Value injection

`{{ variableToInject }}`

```javascript
<div>
    <p>{{ user.username }}</p>
    <p>{{ user.address }}</p>
</div>
```

```javascript
<p>{{ user.username.trim().toLowerCase() }}</p>
```
