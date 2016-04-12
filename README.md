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

<<<<<<< HEAD
checkout master branch .

master branch .....
=======
checkout dev branch ...
>>>>>>> dev
