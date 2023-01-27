# 3A - TP C++

[Lien repo TP2 - Hotel](https://github.com/Hugoreoo/tp2-hotel).  
[Lien repo TP3 - EasyStore](https://github.com/Hugoreoo/tp3-easystore).


# Explication du makefile

Ce script est un fichier Makefile générique pour la gestion automatique des dépendances d'un projet en C++. Il utilise le compilateur g++ (mais peut être facilement modifié pour utiliser clang++). 

Il définit également les fichiers sources (SRCS) à compiler, les fichiers objets (OBJS) résultants et le nom de l'exécutable cible (TARGET). Il y a des cibles pour nettoyer les fichiers objets (clean), supprimer l'exécutable (mrproper) et lancer l'exécutable (exe). Il y a également une cible pour inclure les dépendances (include).

En utilisant ce fichier Makefile, on peut compiler et exécuter facilement votre projet en utilisant les commandes make, make clean, make mrproper et make exe. Il gère également automatiquement les dépendances entre les fichiers, ce qui signifie que si on modifie un fichier source, seuls les fichiers qui dépendent de celui-ci seront recompilés.

# Ce qu'il nous manque à acquérir

Par exemple les fichiers de configuration pourraient améliorer notre programme en permettant de définir les paramètres de l'application sans avoir à recompiler le code.
Cela faciliterait la maintenance et la modification des paramètres de l'application. De plus, les fichiers de configuration permettent de séparer les données de 
l'application des informations de configuration, ce qui améliore la portabilité de l'application. Cela permet également de stocker les informations sensibles dans des 
fichiers séparés, ce qui améliore la sécurité de l'application. Il est donc important pour un ingénieur de savoir comment utiliser et implémenter des fichiers de 
configuration pour améliorer la qualité, la flexibilité et la sécurité de leur application.

Egalement, l'implémentation de tests unitaires pourrait améliorer notre programme en permettant de vérifier la validité des fonctionnalités et des calculs effectués. 
Cela permettrait également de détecter les bugs plus facilement et de les corriger rapidement. Les tests peuvent également servir à valider que les modifications 
apportées au code ne causent pas de régressions et maintiennent le bon fonctionnement des fonctionnalités existantes. Il est important de noter que les tests sont un 
élément clé de la qualité logicielle et de l'assurance qualité.

Ou même encore des méthodes de parallélisme pourraient être implémentées afin d'optimisé les calculs des parties indépendantes et les réalisant en parallèles, cependant
cela recquiert une compréhension parfaite du code et une mise en place particulière de l'architecture de notre programme.

Ou encore il est possible d'utiliser des outils de qualimétrie pour évaluer la qualité de notre programme. Ces outils peuvent inclure des choses comme la vérification de la couverture de code, la détection de bugs, la vérification de la conformité aux normes de codage, etc. Pour utiliser ces outils, il est généralement nécessaire de les intégrer dans notre processus de développement de manière à les utiliser de manière automatisée ou semi-automatisée. Par exemple, nous pourrions utiliser un outil de couverture de code pour vérifier automatiquement que toutes les lignes de notre code ont été exécutées lors de nos tests unitaires.

On sait qu'il est possible d'intégrer notre application à un site web en utilisant des technologies telles que l'API REST ou SOAP pour permettre à notre application de communiquer avec le site web. Cela permettrait à l'utilisateur de naviguer sur le site web et de réserver des chambres, de consulter les réservations, etc. directement depuis le site web. Il faudrait aussi implémenter une interface pour permettre à l'utilisateur de se connecter et de gérer son compte. Il faudrait également s'assurer que la sécurité soit implémentée pour protéger les données de l'utilisateur.

Tout cela sont des compétences qu'un ingénieur en informatique devrait maîtriser. Nous avons donc beaucoup appris mais cela ne représente que le début de notre apprentissage.
