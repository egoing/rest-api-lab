# POST
```javascript
fetch('topic', {
    method:'POST', 
    headers:{'content-type':'application/json'},
    body:JSON.stringify({
        title:'fetch', body:'fetch is ...'
    })
})
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```
# GET collection
```javascript
fetch('topic')
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```
# GET element
```javascript
fetch('topic/1')
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```
# PUT
```javascript
fetch('topic/1', {
    method:'put', 
    headers:{'content-type':'application/json'},
    body:JSON.stringify({
        title:'fetch'
    })
})
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```
## PATCH
``` javascript
fetch('topic/1', {
    method:'PATCH', 
    headers:{'content-type':'application/json'},
    body:JSON.stringify({
        title:'fetch'
    })
})
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```
## DELETE
```javascript
fetch('topic/1', {
    method:'DELETE'
})
    .then(
        function(type){
            return type.json()
        }
    )
    .then(
        function(result){
            console.log(result);
        }
    )
```