
# Module Jsskill ( create in javascript natif) version 1

Comment utiliser ce module

---

1.Tout d'abord, vous devez déclarer dans votre page HTML le bloc
  comme ça:
   `<div id="jsskill"></div>`
2. Deuxièmement, vous pouvez mettre votre code en javascript.
   Regardez le code :

``` script
(function(){
    Jc.param({
        color: "#FFA07A", frame:"cercle",
        ladder:10, speed:1000,
        number: 5, selected:'jsskill'
    }).addBlock('Langage & Framework', [
        {name:'html/css', level: 8},{name:'angular', level:9},
        {name:'javascript', level:5},{name:'jquery', level:3},
        {name:'symfony',level:4}, {name:'php', level:5},
        {name:'c#', level:3}
    ]).animate();
})();
```

Utilisation du Module Jc

---
>Les fonctions utilitaire du module.
| Function                     | Description                    |
| ---------------------------: | :---------------------------- :|
| Jc.param(<Element option>)   | Fonction de configurations     |
| Jc.slide()                   | Fonction slide                 |
| Jc.show()                    | Fonction show                  |
| Jc.progress()                | Fonction progress              |
| Jc.animate()                 | Fonction animate               |
| Jc.addBloc()                 | Fonction addBloc               |

Linked logo: (http://keretben.com/jsskill "keretben")