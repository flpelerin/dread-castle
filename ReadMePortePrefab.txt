Pour que le prefab de porte fonctionne suivait les étapes: 

1. Importer le package

(Si vous voulez changer de porte changer le mesh Filter, mesh Collider et material du mesh Renderer)

Pour l'ouverture avec clé : 
2. Vérifier que la porte a comme tag "KeyLocked"
3. Créer un objet clé qui devra avoir : 
	Layer : Pickable
	Tag : KeyDoor


Pour l'ouverture avec code :
2. Ajouter le tag "CodeLocked" à la porte
(à faire)
