```
:render-header="renderHeader"

renderHeader(h, { column }) {
      const label = column.label.split('/')
      const arr = []
      label.forEach((obj) => {
        arr.push(h('div', obj))
      })
      return h('div', arr)
    },
    
```

한 개의 row에서 두 개 이상의 항목을 도출하고 싶을 때 사용한다.
