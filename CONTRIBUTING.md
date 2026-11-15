# Contribuer à la documentation Moai UHC

Merci de vouloir améliorer la documentation de Moai UHC ! Il n'y a pas besoin d'être développeur, un compte
[GitHub](https://github.com/signup) suffit et tout se fait depuis votre navigateur. Personne ne peut casser le
site : chaque modification est relue avant d'être publiée.

## 1. Signaler un problème (le plus simple)

Si vous avez repérez une erreur mais que vous ne souhaiter pas le corriger vous même, vous pouvez remplir
[Remplir ce formulaire](https://github.com/BGoodes/moai-uhc-doc/issues/new/choose). Indiquez la page
concernée et ce qui ne va pas et on va s'occuper du reste.

## 2. Corriger une page depuis Github

C'est la méthode recommandée pour les corrections et ajouts de texte.

TODO: TUTO

### Mémo de mise en forme

Les pages sont écrites en Markdown, une syntaxe très simple :

| Pour obtenir…        | Écrire…                          |
| -------------------- | -------------------------------- |
| **gras**             | `**gras**`                       |
| *italique*           | `*italique*`                     |
| un titre             | `### Mon titre`                  |
| une liste            | `- élément` (un par ligne)       |
| un lien              | `[texte](https://exemple.com)`   |
| une commande         | `` `/uhc host start` ``          |
| une image            | `![description](./img/image.png)`|

Pour un encadré d'information :

```md
:::info

Mon message.

:::
```

Le bloc tout en haut de chaque fichier (entre les `---`) permet de ranger la page dans le menu. Il ne faut donc pas la modifier.

Pour ajouter une image, glissez-la directement dans l'éditeur GitHub : le lien est inséré tout seul.

## Règles de rédaction

- La documentation est rédigée en **français**.
- Les noms de fichiers et de dossiers sont en **anglais**, en minuscules et séparés par des tirets
  (exemple: `become-host.mdx`), car ils servent à construire les URL.
- Les images vont dans un dossier `img/` à côté de la page qui les utilise.
- Une Pull Request = un sujet. Évitez de mélanger plusieurs changements sans rapport. Vous pouvez
  faire plusieurs Pull Request au besoin.
