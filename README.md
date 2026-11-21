# Verbes en Herbe

Petit jeu pour enfant pour s'entraîner à conjuguer les verbes français, dans une seule page web.

**Jouer en ligne :** https://maximeguillaume.github.io/verbes-en-herbe/

## Ce que propose le jeu

- Groupes : 1er groupe, 2e groupe, 3e groupe, être et avoir (50 verbes).
- Temps : présent, imparfait, futur simple, passé composé (avec l'accord du participe passé avec « être »).
- Séries de 5, 10 ou 20 questions, avec étoiles, confettis et sons.
- Après une erreur : la bonne réponse avec la terminaison soulignée, et le tableau complet du verbe.
- Un deuxième essai quand seuls les accents sont faux.
- À la fin : la liste des erreurs et un bouton pour les revoir.

## Utilisation

Ouvrir `index.html` dans un navigateur. Rien à installer.

### Installer comme une application (iPhone, iPad)

1. Ouvrir https://maximeguillaume.github.io/verbes-en-herbe/ dans **Safari**.
2. Toucher le bouton **Partager**, puis **Sur l'écran d'accueil**.
3. Le jeu s'ouvre ensuite en plein écran depuis son icône, et fonctionne aussi sans connexion après la première ouverture.

Sur Android (Chrome) : menu ⋮ puis **Installer l'application**.

<img src="icons/logo-1024.png" alt="Logo Verbes en Herbe" width="160">

## Ajouter des verbes

Dans le script de `index.html` :

- **1er et 2e groupe** : ajouter l'infinitif à la liste correspondante, les terminaisons sont calculées automatiquement.
- **3e groupe** : ajouter une ligne au tableau `IRR` avec les 6 formes du présent, la base du futur et le participe passé.
