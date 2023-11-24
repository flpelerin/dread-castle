# dread-castle player

Pour que le Player fonctionne suivait les étapes : 

1. Importer le package
2. Pour les mouvements : Aller dans Window > Package Manager > Cliquer sur la section "Packages" et sélectionner "Unity Registry" > Chercher "input" dans la barre de recherche > télécharger "input system" (le projet se rechargera)
4. Pour les interactions : Ajouter au projet un layer "Pickable" et l'attribuer aux objets à ramasser (Attention ! Les objets ramassables doivent avoir un rigidBody et un collider, en cas de mesh collider cocher la case "Convex")
5.  Pour que les touches fonctionnent : Aller dans Edit > Project Settings > Input Manager > Décocher "Use Physical Keys" (permet d'utiliser AZERTY)
