
Tu peux **modifier le titre d’un fichier, d’un commit, ou même le nom du dépôt GitHub** si tu as fait une faute de frappe. Voici comment corriger chaque type d’erreur, avec des vidéos qui te montrent les manipulations dans VS Code et sur GitHub.

---

## 🧠 1. Modifier le nom d’un fichier dans GitHub

Si tu veux corriger le **nom d’un fichier** (ex. `main.c` → `main_code.c`) :

### Méthode via VS Code :
```bash
git mv ancien_nom.c nouveau_nom.c
git commit -m "Renommage du fichier"
git push
```

👉 [Ajouter et modifier un fichier avec git | formation git et GitHub](https://www.youtube.com/watch?v=-QHFh16mBUE) te montre comment modifier un fichier, le renommer, et valider les changements avec un commit propre.

👉 [Git22-Modifier ou ajouter un fichier sans refaire un nouveau ...](https://www.youtube.com/watch?v=5YUjb3u_Mrw) te montre comment modifier un fichier sans recréer tout le commit, idéal pour corriger une faute de frappe dans le nom.

---

## 🧾 2. Modifier le message d’un commit (si tu n’as pas encore pushé)

Si tu veux corriger une faute dans le **message du dernier commit** :

```bash
git commit --amend
```

👉 [Pousser les modifications sur GitHub](https://www.youtube.com/watch?v=U5d-o_N-b4Q) te montre comment modifier ton commit local avant de le pousser, y compris le message.

---

## 📦 3. Modifier le nom du dépôt GitHub (titre principal)

Si tu veux corriger le **nom du projet** (ex. `esp32-projet` → `esp32-projet-final`) :

1. Va sur ton dépôt GitHub
2. Clique sur **Settings**
3. Dans la section **Repository name**, modifie le nom
4. Clique sur **Rename**

👉 [Créer un repository avec GIT et GITHUB](https://www.youtube.com/watch?v=85lbuuFIXG4) te montre comment créer et configurer ton dépôt, y compris le nom.

👉 [Votre code en ligne sur Github en 10mn](https://www.youtube.com/watch?v=76hFN6kcV04) te montre comment publier ton projet et organiser ton dépôt, ce qui inclut le nom du repository.

---

## 🧩 4. Modifier un fichier directement sur GitHub

Si tu veux corriger un titre ou une faute dans un fichier `.md`, `.txt`, etc. :

1. Va sur le fichier dans GitHub
2. Clique sur l’icône **crayon** (Edit)
3. Corrige le texte ou le nom
4. Ajoute un message de commit
5. Clique sur **Commit changes**

👉 [Apprendre à utiliser facilement Git et Github !](https://www.youtube.com/watch?v=OpgmGI49Uxg) te montre comment modifier un fichier directement sur GitHub sans passer par VS Code.

👉 [Formation Git & GitHub FR: III.4 Indexer ses modifications](https://www.youtube.com/watch?v=aJgcytk9V6w) t’explique comment indexer et valider tes modifications proprement.

---

💡 En résumé :
- **Fichier mal nommé** → `git mv`
- **Message de commit mal écrit** → `git commit --amend`
- **Nom du dépôt mal orthographié** → Modifier dans GitHub > Settings
- **Texte dans un fichier** → Modifier directement sur GitHub ou via VS Code

Tu veux que je t’aide à corriger un nom précis ou à faire le commit proprement dans ton projet ESP32 ?
