# PHPUNIT :
- Tester une classe qui n’a aucune dépendance est généralement assez simple. La difficulté va commencer à se faire sentir (et cela devrait arriver presque tout le temps) lorsque les classes vont utiliser des dépendances. </br>.
- Nous avons deux solutions pour tester une classe : </br>
-- On peut tester la classe avec toutes ses dépendances, et si vous comptez faire ça, alors il serait bien que vous sortiez (Nan mais restez car le plus important c’est de tester le comportement de la classe).</br>
-- Ou bien, nous pouvons essayer d'isoler notre classe de ses dépendances : C’est là où interviennent les tests doubles.
- Un mock est juste une duplication d'une classe.</br>
