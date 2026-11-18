# Passer le temps

Petits jeux à lancer dans le navigateur en attendant quelque chose. Site statique : du HTML, du CSS et du JavaScript, sans build ni dépendance.

| Jeu | Dossier | Principe |
| --- | --- | --- |
| Pile de Planches | `pile-de-planches/` | Empiler des planches de 18 mm en 3D isométrique, ce qui dépasse est scié |
| Guerre des Vessies | `guerre-des-vessies/` | Vue subjective dans un bistrot : boire, manger, arroser les bots |
| Saute-Copeau | `saute-copeau/` | Faire monter un copeau de bois de planche en planche |
| Clocher contre Clocher | `clocher-contre-clocher/` | Bataille en ligne entre deux villages, du hameau à la cité |

## Lancer en local

N'importe quel serveur statique fait l'affaire :

```sh
python3 -m http.server 8000
```

puis ouvrir http://localhost:8000.

## Déployer

```sh
npx vercel deploy --prod
```

Guerre des Vessies se joue ici en solo contre des bots. Son mode multijoueur n'existe que dans la version publiée comme artifact Claude.
