# ❤️ Comment recevoir sa réponse par email

Pour recevoir un email dès qu'elle clique sur "Oui ! ❤️", configure Formspree (gratuit) :

## Étapes

1. **Va sur [formspree.io](https://formspree.io)** et crée un compte gratuit
2. **Clique sur "New Form"** et donne un nom (ex: "Valentine")
3. **Copie ton Form ID** : dans l'URL de ton form, tu verras `https://formspree.io/f/XXXXXXX` — copie la partie `XXXXXXX`
4. **Ouvre `index.html`** et remplace `YOUR_FORMSPREE_ID` à la ligne ~100 par ton ID :
   ```javascript
   const FORMSPREE_ID = 'ton_id_ici';
   ```

C'est tout ! Quand elle cliquera sur "Oui", tu recevras un email avec :
- Sa réponse ("Oui")
- La date et l'heure

## Pour tester

Ouvre `index.html` dans ton navigateur (double-clic sur le fichier ou glisse-le dans Chrome/Firefox).

## Pour lui envoyer

- Mets le fichier en ligne (Netlify Drop, GitHub Pages, etc.) et envoie-lui le lien
- Ou utilise un outil comme "Live Server" dans VS Code pour créer un lien local
