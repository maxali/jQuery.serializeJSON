# jQuery.toJSON
Serialize form to JSON


Simple, add this line and boom!
```javascript
// $('#formid').toJSON();  ==> {...}
jQuery.fn.extend({toJSON:function(){var c=$(this).serializeArray(),a={};$.map(c,function(b){a[b.name]=b.value});return a}});
```
