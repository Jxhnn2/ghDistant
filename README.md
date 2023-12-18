# README - Utilisation du Hook pre-commit

Ce dépôt utilise un hook pre-commit pour ajouter une note de vérification à chaque commit.

1. **Installation (pour les nouveaux contributeurs) :**
   - Clonez le dépôt : `git clone https://url_du_depot.git`
   - Allez dans le répertoire du dépôt : `cd nom_du_depot`

2. **Autoriser l'exécution du Hook (pour tous les contributeurs) :**
   - Ajouter le hook pre-commit du dossier hooks dans .git/hooks pour qu'il soit fonctionnel.
   
   - Exécutez la commande suivante dans le terminal (Git Bash pour Windows) :
     ```bash
     chmod +x .git/hooks/pre-commit
     ```

3. **Usage (pour tous les contributeurs) :**
   - Avant chaque commit, répondez à la question :
     ```
     Ajouter une note de vérification au commit (y/[n]) ?
     ```

   - Répondez "y" pour ajouter une note, "n" pour continuer sans ajouter de note.

4. **Mise à jour (pour tous les contributeurs) :**
   - Pour obtenir les dernières modifications du dépôt (y compris le Hook) :
     ```bash
     git pull origin master
     ```

Pour plus d'informations, contactez l'équipe de développement.
