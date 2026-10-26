# 🎣 Pêche automatique

Petit assistant Windows pour le mini-jeu de pêche de **Voler un œuf / Steal An Egg** sur Roblox. Il repère l’interface à l’écran, lance la ligne et effectue les clics de pêche.

Prérequis : **Windows 64 bits** et Roblox installé.

## Démarrage rapide

1. Télécharge **PecheAuto.exe** depuis la section **Releases** de ce dépôt.
2. Vérifie son empreinte et consulte le rapport antivirus ci-dessous avant de l’ouvrir.
3. Vérifie que ton Roblox est en anglais.
4. Lance le programme, puis équipe ta canne au bord du bassin dans Roblox.
5. Garde le jeu visible au premier plan et appuie sur **F8**.
6. Appuie sur **F9** pour arrêter.

| Commande | Action |
| --- | --- |
| **F8** | Démarrer / mettre en pause |
| **F9** | Arrêter et relâcher le clic |
| **Démarrer dans 3 s** | Laisser trois secondes pour revenir dans le jeu |

Le programme se met en pause quand Roblox perd le premier plan. Reviens dans le jeu et presse F8 pour reprendre.

## Réglages

- **Relancer la canne automatiquement** : enchaîner les cycles. Désactivé, tu lances toi-même ; l’assistant effectue les clics de pêche, puis s’arrête après le cycle.
- **Maintien au lancer** : **1 100 ms** par défaut.
- **Réessai après** : **8 s** par défaut avant une nouvelle tentative si le lancer n’a pas abouti.

Les réglages s’appliquent au prochain démarrage avec F8. Une fenêtre Roblox agrandie, sans menu ni fenêtre superposée, facilite la détection.

## Fonctionnement et limites

L’outil lit les pixels affichés et utilise la souris Windows. Il ne demande pas de droits administrateur, n’enregistre pas les captures et n’utilise pas de connexion réseau.

Il est adapté à l’interface de pêche de référence. Une mise à jour du jeu peut nécessiter un ajustement. La logique a été testée hors jeu ; le fonctionnement complet en partie réelle reste à confirmer.

Si F8/F9 est déjà utilisé, le programme le signale. Si la pêche n’est pas reconnue, vérifie que la canne est équipée et que **Hold to Cast** apparaît.



