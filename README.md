# Prediction du prix Bitcoin
## Réseaux Neuronaux Récurrents
![Image](https://github.com/user-attachments/assets/557c2257-4b86-4f77-ac57-a45b6fa28ca8)
## Qu’est ce que le vanishing/ exploding Gradient Problem ?
![Image](https://github.com/user-attachments/assets/b74dcf1f-cc56-4a0c-8426-015f49703831)
Exemple : Imaginez que vous devez mémoriser un texte long, mais que votre mémoire diminue progressivement au fil du temps. Cela représente la disparition du gradient.
          Si au contraire, chaque nouveau mot ajouté amplifie à l'excès votre mémoire, cela correspond au gradient explosif.
## Comment les LSTM permettent d’éviter le vanishing gradient ?
![Image](https://github.com/user-attachments/assets/ecdd2f7e-a842-427c-85f1-826431cc3e42)
![Image](https://github.com/user-attachments/assets/def47bc7-2972-4ac3-97ca-7f7072d08d68)
Exemple : Imaginez une liste de courses. Vous notez les éléments (ajout d'information), supprimez ceux déjà achetés (oubli), et consultez la liste pour voir ce qu'il reste (sortie).
