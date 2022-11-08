# Destructuring Assignment With Alias

For example:

```javascript
const obj = { foo: 1, bar: 2 }
const { foo: newName } = obj
```

```javascript
const {
  data: clientInitData,
  suspense: suspenseInitData,
} = useClientInitQuery()
```

