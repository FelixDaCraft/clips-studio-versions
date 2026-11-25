# Morso : politique de confidentialité

*Dernière mise à jour : 25 novembre 2026*

Morso est une application Windows qui fabrique des clips vidéo à partir de vidéos choisies par son utilisateur. Elle fonctionne entièrement sur l'ordinateur de l'utilisateur.

## Ce que Morso ne fait pas

- Morso ne crée aucun compte et ne demande ni nom, ni adresse e-mail, ni moyen de paiement.
- Morso n'envoie à personne les vidéos, les photos, les textes ou les clips de l'utilisateur. L'analyse des visages, la transcription et l'intelligence artificielle tournent sur l'ordinateur.
- Morso ne contient aucun outil de mesure d'audience, de publicité ou de suivi.

## Connexions à Internet

Morso se connecte à Internet seulement pour :

- **télécharger ses outils**, à la demande de l'utilisateur : le moteur d'IA Ollama (ollama.com), un modèle d'IA (bibliothèque d'Ollama) et le modèle de transcription (Hugging Face) ;
- **récupérer une vidéo** quand l'utilisateur colle un lien (par exemple YouTube) ;
- **vérifier s'il existe une nouvelle version** (version installée hors du Microsoft Store uniquement), en consultant une page publique de GitHub.

Lors de ces connexions, les services contactés (ollama.com, Hugging Face, YouTube, GitHub, Microsoft) reçoivent, comme pour toute connexion, l'adresse IP de l'ordinateur ; leurs propres politiques de confidentialité s'appliquent.

## Données conservées sur l'ordinateur

Les vidéos téléchargées, les analyses et les réglages sont rangés dans le dossier de l'application sur l'ordinateur (`%LOCALAPPDATA%`), et les clips dans le dossier choisi par l'utilisateur. Désinstaller Morso et supprimer ces dossiers efface tout.

## Photos de personnes

Les photos ajoutées pour reconnaître des personnes servent uniquement à cadrer les clips, sur l'ordinateur. L'utilisateur est responsable d'avoir le droit d'utiliser l'image des personnes filmées et photographiées.

## Contact

Pour toute question : ouvrir une demande sur https://github.com/FelixDaCraft/clips-studio-versions/issues
