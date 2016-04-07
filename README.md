# Rookie
keep learning !

-- the code : 
``` javascript
    (function () {
        function outer () {
                return false;
        }

        if (outer()) {
            function outer () {
                    return true;
            }    
        }

        console.log(outer());
    })();

```
