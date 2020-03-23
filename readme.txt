Dans MainActivity, nous avons créé un objet SharedPreferences.
En utilisant la méthode onCreate, activity_main.xml a été connecté en Java. 
J'ai utilisé la méthode onClick, pour le bouton [enregistrer]. 
J'ai utilisé la méthode viewActivity2 pour le bouton [aller à la deuxième activité].
Dans la deuxième activité, j'ai posté "Passage vers la deuxième activité" via Toast.
Pour le bouton [enregistrer], j'ai utilisé comme arrière-plan une image (de dessinable) et pour [aller à la deuxième activité] une couleur.
Dans MySharedPreference, nous avons initialisé SharedPreferences dans le constructeur. 
En utilisant la méthode save (), j'ai mis la chaîne donnée dans l'éditeur,
Dans clearSharedPreferences (), nous supprimons toutes les valeurs.
Dans SecondActivity, nous avons créé un objet SharedPreferences.