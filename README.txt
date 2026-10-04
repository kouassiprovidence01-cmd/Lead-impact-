# Lead Impact Corporate — version test

## Ce que contient cette version
- Formulaire d'adhésion en 6 étapes, basé sur le document fourni.
- Logo Lead Impact Corporate.
- Cotisation annuelle de 10 000 FCFA.
- Coordonnées affichées : mariepaulekoffi943@gmail.com et Wave 07 19 56 84 92.
- Validation côté navigateur.
- Parcours de test jusqu'à la confirmation.
- Bouton Wave en mode démonstration : aucun paiement réel n'est déclenché.

## Mise en production Cloudflare
Cette version est volontairement un prototype front-end. Pour la version réelle :
1. Publier les fichiers sur Cloudflare Pages/Workers.
2. Ajouter une fonction serveur pour recevoir le formulaire.
3. Configurer Cloudflare Email Service ou un service d'envoi autorisé pour envoyer les réponses à mariepaulekoffi943@gmail.com.
4. Remplacer le mode de paiement de démonstration par une intégration Wave Checkout ou un lien de paiement Wave réellement fourni/validé.
5. Ne jamais mettre une clé API de paiement dans le JavaScript public.
