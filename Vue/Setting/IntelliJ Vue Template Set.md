#인텔리제이에서 Vue 템플릿 세팅 단축어 만드는 법

## 왜 만들고 싶었나
HTML의 경우 ! + Tab키로 템플릿 세팅했던 것이 상당히 편했기 때문

## 만드는 방법
상단의 Preferences > Editor > Code Style > Live Templates 
라이브러리 및 프레임워크 목록에서 Vue 오픈
우측의 + 버튼 > Live Template

Abbreviation에 단축어로 세팅할 단어 선정 

```
<Vue!>
```

Template Text에 템플릿 작성

```
<template>
  <div></div>
</template>

<script>
export default {
  name: "",
  data() {
    return {
    }
  },
  created() {
  },
  mounted() {
  },
  methods: {}
}
</script>
```

*익명의 개발자가 도움을 주었습니다 *
