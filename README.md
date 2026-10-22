# Profil GitHub — Alexis Fiolleau

Ce dépôt special contient la configuration commune de mes dépôts publics.

## Contenu

| Chemin | Rôle |
| :--- | :--- |
| `profile/README.md` | Modèle de README pour les nouveaux dépôts. |
| `ISSUE_TEMPLATE/` | Formulaires de signalement de bug et de demande de fonctionnalité. |
| `FUNDING.yml` | Configuration du bouton « Sponsor ». |
| `assets/profile-social-preview.png` | Image de partage (aperçu Open Graph) du profil GitHub. |

## Utiliser le modèle de README

```bash
# 1. Récupérer le modèle
curl -fsSL https://raw.githubusercontent.com/Potowai/.github/main/profile/README.md > README.md

# 2. Adapter les champs <...> et les sections
$EDITOR README.md
```

Le modèle est volontairement court : une phrase de description, le lien vers la
démo en ligne, la stack réellement utilisée, les commandes de démarrage, la
configuration et la licence. Les badges ne sont là que s'ils reflètent
l'état réel du projet.

## Aperçu de partage

`assets/profile-social-preview.png` est l'image utilisée par GitHub comme
aperçu Open Graph du profil public. Pour la régénérer après un changement de
charte, voir le script de rendu dans le dépôt de profil :

```bash
git clone https://github.com/Potowai/Potowai.git && cd Potowai
python3 scripts/render-social-preview.py
```
