# Présentation de la stack du développeur

Présentation de la stack complète du développeur mairie (maven, packages, git,
  repos mvn, test unitaire) et de l'écosystème cloud qui va autour.

Le but de cette présentation est de poser les éléments utilisés pour une
industrialisation classique des dévelopements. Le but est de montrer,
sur des exemples pratiques comment builder, packager, distribuer des
applications, dans un contexte orienté SaaS en utilisant des produits du cloud.

# Outil de présentation

Pour générer la présentation de manière à ce qu'elle puisse être éditée de
manière collaborative (en markdown), j'ai utilisé npm et plus
précisèment https://github.com/jdan/cleaver.

# Builder la présentation

1. Installer [cleaver](https://github.com/jdan/cleaver)
2. Cloner la repo : `cd git clone https://github.com/adriens/presentation-idd-cloud.git`
3. Aller dans le répertoire `cd presentation-idd-cloud`
4. Builder la présentation : `cleaver presentation.md`
