# Salutations ! 👋

```c#

namespace GitHub;

class Program
{
    static void Main()
    {
        var identité = new Dictionary<string, object>
        {
            { "prenom", "Kevin" },
            { "nom", "Banzet" },
            { "âge", DateTime.Now.Year - 2004 }
        };
        var langages = new List<string> { "Python", "C#", "Java", "SQL" };
        var outils = new List<string> { "PyCharm", "Rider", "VSCode", "Eclipse", "Oracle SQL Developer" };

        Console.WriteLine($"Salut ! Je m'appelle {identité["prenom"]} {identité["nom"]} et je souhaite devenir " +
                          "un développeur informatique polyvalent. En ce moment, je possède des bases solides en " +
                          $"{string.Join(", ", langages)}. Ceci dit, j'étends mes connaissances en permanence et " +
                          "c'est pourquoi j'utilise des outils variés, tels que " +
                          $"{string.Join(", ", outils)}. " +
                          "\n\nJe reste disponible aux liens de contact annotés ci-dessous. ");
    }
}
```

## 🎯 Objectifs
Réussir le BTS auquel je me suis engagé ;

Participer à des projets collaboratifs ;

Mise en oeuvre de projets professionnels originaux.



## 📫 Me contacter : 
Par [**email**](kevin.banzet@gmail.com) ou grâce à [**LinkedIn**](https://www.linkedin.com/in/kevin-banzet/). 
### À bientôt ! 🙂
