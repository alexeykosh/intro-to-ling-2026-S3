# Linguistique pour les sciences des données

## Projet final

### 1. Présentation générale

Le projet personnel consiste à répondre, à l’aide de méthodes computationnelles, à une question de recherche en lien avec les thèmes abordés en cours.

Vous pourriez, par exemple, poser la question suivante : existe-t-il une association entre le nombre de phonèmes d’une langue et son nombre de locuteurs ? Cette question peut être motivée par plusieurs notions vues en cours : on suppose notamment que la taille de la population influence la complexité linguistique (voir, par exemple, Lupyan & Dale, 2010). Vous pourriez formuler l’hypothèse d’une association négative : une langue comptant davantage de locuteurs pourrait avoir un système phonologique plus simple, et le nombre de phonèmes pourrait constituer un bon indicateur de la complexité phonologique.

Un choix naturel de base de données serait alors [PHOIBLE](https://phoible.org/), qui contient des informations sur les inventaires phonémiques de plusieurs milliers de langues. Vous pourriez en extraire la taille des inventaires phonémiques pour un échantillon de langues aussi large et équilibré que possible, puis associer ces données au nombre de locuteurs de chaque langue. L’analyse pourrait consister à ajuster une régression de Poisson pour prédire le nombre de phonèmes en fonction du nombre de locuteurs, tout en tenant compte de la famille linguistique. Les langues appartenant à une même famille sont plus susceptibles d’avoir des systèmes phonologiques similaires ; la taille de leurs inventaires phonémiques pourrait donc également être plus proche.

Enfin, nous vous encourageons à prendre du recul sur vos résultats : si des études similaires ont déjà été menées, vos résultats concordent-ils avec les résultats antérieurs ? Comment les interpréter ? Par exemple, si vous ne trouvez aucune relation, que pourrait signifier ce résultat ?

### 2. Structure et format de remise

Vous devez remettre votre projet sous la forme d’un fichier Jupyter Notebook, en suivant la structure ci-dessous :

1. **Question de recherche** — À quelle question votre projet cherche-t-il à répondre ? Par exemple : existe-t-il une association entre le nombre de phonèmes d’une langue et son nombre de locuteurs ? Vous devez également expliquer pourquoi cette question mérite d’être étudiée. Vous pouvez, par exemple, présenter quelques articles pertinents et montrer en quoi les travaux antérieurs justifient l’exploration de la question choisie.

2. **Données** — Quelles données utiliserez-vous pour répondre à votre question de recherche ? Par exemple : je m’appuierai sur PHOIBLE et j’utiliserai les données x, y et z, stockées dans les colonnes a, b et c, qui correspondent aux caractéristiques suivantes. Cette section doit également présenter les étapes de prétraitement et les statistiques descriptives.

3. **Analyse** — Expliquez brièvement, dans un langage accessible, l’analyse que vous allez réaliser. Le reste de cette section sera probablement constitué de code, mais nous vous encourageons à expliquer le rôle des portions de code importantes afin que votre analyse puisse être comprise par une personne qui découvre votre projet.

4. **Conclusion** — Expliquez en quoi les résultats répondent à votre question de recherche. Si des études similaires ont déjà été menées, vos résultats concordent-ils avec les résultats antérieurs ? Comment les interpréter ? Par exemple, si vous n’avez trouvé aucune relation, que pourrait signifier ce résultat ?

### 3. Évaluation

Le projet final sera évalué selon cinq critères, pour un total de **10 points** :

1. **Originalité (3 points)**
   - **0 point :** une question de recherche sans lien avec le cours.
   - **3 points :** une question de recherche très pertinente et originale, qui mobilise et combine plusieurs thèmes vus en cours, voire introduit un nouveau thème pertinent.

2. **Conclusions (2 points)**
   - **0 point :** des conclusions qui ne témoignent pas d’une réflexion critique sur les résultats ni d’une mise en perspective à partir des notions vues en cours.
   - **2 points :** des conclusions qui examinent les résultats de manière critique, en discutant notamment des pistes de recherche futures et/ou des raisons pour lesquelles les résultats pourraient être erronés.

3. **Présentation du rapport (2 points)**
   - **0 point :** un texte incompréhensible ou mal rédigé et des figures peu claires, par exemple des graphiques sans titres d’axes ou des illustrations illisibles.
   - **2 points :** un texte clair et concis, accompagné de figures lisibles et correctement annotées.

4. **Présentation du code (2 points)**
   - **0 point :** un code confus et désorganisé, manifestement généré par une IA.
   - **2 points :** des blocs de code lisibles et bien organisés, une utilisation appropriée des fonctions et des imports, et un code bien commenté.

5. **Reproductibilité (1 point)**
   - **0 point :** un code qui produit des erreurs, des données manquantes, etc.
   - **1 point :** un code entièrement reproductible, qui s’exécute sans erreur et produit des sorties conformes aux résultats présentés.

### 4. Utilisation de l’intelligence artificielle

Toute utilisation de l’intelligence artificielle pour la rédaction, la programmation ou la conception du projet doit être déclarée. Vous devez inclure, au début du notebook, une courte déclaration précisant le modèle utilisé et les tâches pour lesquelles vous y avez eu recours. L’utilisation d’outils d’intelligence artificielle pour la collecte et l’annotation des données est encouragée, mais elle doit également être déclarée, et la procédure suivie doit être expliquée en détail.

### Références

Lupyan, G., & Dale, R. (2010). Language structure is partly determined by social structure. *PLOS ONE, 5*(1), e8559.
