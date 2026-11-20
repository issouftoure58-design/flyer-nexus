# flyer-nexus

Le flyer digital de NEXUS, ouvert par un QR code.

- `index.html` : le flyer, lisible sur téléphone et imprimable en A5.
- `flyer-nexus.pdf` : le même, en PDF.
- `issouf-toure.vcf` : la fiche contact à enregistrer.

## Ce que fait cette page, et ce qu'elle ne fait pas

- Aucun programme (pas de JavaScript), aucun formulaire, aucun cookie, aucune mesure d'audience.
- Rien n'est chargé depuis un autre site : polices du téléphone, images et fichiers servis d'ici.
- Une règle de sécurité du navigateur (`Content-Security-Policy`, en tête de `index.html`) interdit tout programme, tout envoi de formulaire et tout chargement extérieur, même si quelqu'un tentait d'en ajouter.
- Les deux téléchargements ne partent que si on appuie dessus.
- Ouverte dans un navigateur, une page web n'a accès ni aux photos, ni aux contacts, ni aux messages du téléphone.

Pour vérifier sans nous croire sur parole : lire `index.html` ici, ou soumettre l'adresse au contrôle de sécurité de Google (Transparency Report) ou à VirusTotal.
