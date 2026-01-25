# 🚀 Instructions de Déploiement GitHub - U.S. Crépy en Valois Football

## Étape 1 : Créer le Repository sur GitHub

### Ouvrez votre navigateur et suivez ces étapes :

1. **Allez sur GitHub** : [https://github.com/new](https://github.com/new)
   
2. **Connectez-vous** si nécessaire

3. **Remplissez le formulaire** :
   - **Repository name** : `us-crepy-en-valois-football-website`
   - **Description** : `Site officiel de l'U.S. Crépy en Valois Football (FFF #500503)`
   - **Visibilité** : Public ✅
   - **NE PAS** cocher "Add a README file"
   - **NE PAS** cocher "Add .gitignore"
   - **NE PAS** cocher "Choose a license"

4. **Cliquez sur** "Create repository"

5. **Copiez l'URL** de votre repository (elle ressemblera à) :
   ```
   https://github.com/VOTRE_NOM_UTILISATEUR/us-crepy-en-valois-football-website.git
   ```

---

## Étape 2 : Pousser le Code sur GitHub

### Une fois le repository créé, revenez ici et exécutez ces commandes :

**IMPORTANT** : Remplacez `VOTRE_NOM_UTILISATEUR` par votre vrai nom d'utilisateur GitHub !

```bash
# 1. Ajouter le remote GitHub
git remote add origin https://github.com/VOTRE_NOM_UTILISATEUR/us-crepy-en-valois-football-website.git

# 2. Vérifier que le remote est bien ajouté
git remote -v

# 3. Renommer la branche en main
git branch -M main

# 4. Pousser le code sur GitHub
git push -u origin main
```

---

## Étape 3 : Activer GitHub Pages

1. **Retournez sur GitHub** dans votre repository
2. Cliquez sur **"Settings"** (Paramètres)
3. Dans le menu de gauche, cliquez sur **"Pages"**
4. Sous **"Source"** :
   - Sélectionnez la branche : **main**
   - Sélectionnez le dossier : **/ (root)**
5. Cliquez sur **"Save"**

---

## 🎉 Votre Site Sera Disponible À :

```
https://VOTRE_NOM_UTILISATEUR.github.io/us-crepy-en-valois-football-website/
```

Le déploiement prend **1-2 minutes**. GitHub vous montrera l'URL exacte dans la section Pages.

---

## ✅ Checklist

- [ ] Repository créé sur GitHub
- [ ] URL du repository copiée
- [ ] Commandes git exécutées (remote add, push)
- [ ] GitHub Pages activé
- [ ] Site web accessible en ligne

---

## 🆘 En Cas de Problème

### Erreur "remote origin already exists"
```bash
git remote remove origin
git remote add origin https://github.com/VOTRE_NOM_UTILISATEUR/us-crepy-en-valois-football-website.git
```

### Erreur d'authentification
GitHub peut vous demander de vous authentifier. Utilisez :
- Votre nom d'utilisateur GitHub
- Un **Personal Access Token** (pas votre mot de passe)

Pour créer un token : [https://github.com/settings/tokens](https://github.com/settings/tokens)

---

**Prêt à commencer ?** Ouvrez [https://github.com/new](https://github.com/new) dans votre navigateur !
