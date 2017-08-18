# webstorm-live-templates
Collection of javascript webstorm live templates for uses in node.js and beyond


## install (windows version tested) 
- open webstorm
- Go to Settings
- file > Settings or Ctlr + Alt + s
- Settings → Editor → Postfix Templates.

![Photo](https://i.imgur.com/FI3mVaB.png)
```
---------------

function $name$($param$){
    var $result$ = $END$;
    return $result$;
}
---------------


for( var $X$ = 0; $X$ < $2dArray$.length; $X$++ ){
    for( var $Y$ = 0; $Y$ < $2dArray$[$X$].length; $Y$++ ){
        var $value$ = $2dArray$[$X$][$Y$];
        $END$
    }
}
---------------

console.log($data$$END$);

/*
 Function - $name$()
 Describe - $desc$
 Created  - $date$ at $time$
 */
 $END$
 ---------------

 function $name$($paramater$){
    $END$
	return $result$;
}
---------------


"$String$"
```
