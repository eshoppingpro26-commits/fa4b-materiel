# Affiches et tracts Free Air 4 Brussels

Fichiers générés à partir des 4 PDF fournis par le graphiste
(`FLYER_FULL COLOUR_NLFR.pdf`, `FLYER_BLACK_NLFR.pdf`,
`FLYER A4_FULL COLOUR_NLFR.pdf`, `FLYER A4_BLACK_NLFR.pdf`).

Les originaux étaient bilingues, 2 pages : page 1 en français, page 2 en néerlandais.
Ils ont été découpés en fichiers séparés par langue.

## Ce qu'il y a dans le dossier

| Fichier | Format | À quoi ça sert |
|---|---|---|
| `FA4B-affiche-A4-*` | A4, 1 page | Affiche pour fenêtre, vitrine, panneau. Généré en agrandissant le tract A5 (212 dpi, propre pour une impression maison). |
| `FA4B-tract-A5-*` | A5, 1 page | Le tract seul, tel que fourni par le graphiste. À distribuer en main propre ou en boîte aux lettres. |
| `FA4B-planche-A4-4tracts-*` | A4, 1 page | Planche d'impression : 4 tracts A5 sur une feuille A4, à imprimer puis découper. Le plus économique pour distribuer en nombre. |
| `*-apercu.jpg` | 900 px | Aperçus web de l'affiche, à mettre sur le site. Pas destinés à l'impression. |

Chaque fichier existe en 4 déclinaisons : `couleur` ou `noir` (noir et blanc,
pour une impression économique), et `FR` ou `NL`.

## Attention

Le fichier d'origine nommé « FLYER A4 » n'est **pas** une affiche A4 :
c'est une planche de 4 tracts A5 destinée à l'imposition. C'est pour ça
qu'elle est renommée `planche-A4-4tracts` ici.

## Mise en ligne sur fa4b.net (Squarespace)

1. Charger les PDF via l'onglet **Fichiers** d'un bloc Bouton temporaire.
2. Squarespace les héberge sur `https://fa4b.net/s/<nom-du-fichier>.pdf`.
3. Charger les 2 aperçus JPG comme images normales.
4. Coller `section-affiches-FR.html` sur la page FR et `section-affiches-NL.html`
   sur la page NL, dans un bloc Code, juste après la section de l'événement
   du 13 septembre.
5. Remplacer les URL marquées `REMPLACER` dans le code par les vraies URL.
