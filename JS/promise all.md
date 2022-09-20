
```
Promise.all( [ a, b, b ... ] )
        .then((A) => {
        
        })
        .catch((error) => {
        
        })
```


```
Promise.all( [ 
        getCommonCode({ display_yn: true, parent_code_type: '@' }),
        getCommonCode({ display_yn: true, parent_code_type: '@@' })

] )
        .then((response_list) => {
         const [ @_type_cd_options_list , @@_type_cd_options_list ] = response_list
        
        })
        .catch((error) => {
        
        })
```
