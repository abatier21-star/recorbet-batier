# RECORBET BATIER — Web/PWA V1

Carnet de chantier + clients + interventions + stock dépôt/camion + alertes.
Pas de devis, facture ou e-facturation.

La V1 fonctionne immédiatement en local dans le navigateur et est installable comme PWA. Le dossier `supabase/schema.sql` prépare la base pour la prochaine étape : compte utilisateur + sauvegarde cloud automatique. Pour une vraie mise en ligne, il faudra déployer le dossier sur un hébergement HTTPS et renseigner les clés Supabase dans `config.js`. Ne jamais mettre de clé service_role/secret dans le navigateur.
