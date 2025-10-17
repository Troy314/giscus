# [giscus][giscus]

Un système de commentaires reposant sur le système de [Discussions GitHub][discussions]. Permettez aux visiteurs de votre site web de laisser des commentaires et des réactions  via GitHub ! Fortement inspiré par [utterances][utterances].

- [Open source][repo]. 🌏
- Pas de suivi, pas de publicité, gratuit pour toujours. 📡 🚫
- Pas besoin de base de données. Toutes les données sont stockées dans les discussions GitHub. :octocat:
- [Thèmes personnalisables][creating-custom-themes]! 🌗
- [Multilingue][multiple-languages]. 🌐
- [Largement configurable][advanced-usage]. 🔧
- Récupère automatiquement les nouveaux commentaires et modifications depuis GitHub. 🔃
- [Peut être auto-hébergé][self-hosting]! 🤳

> **Note :**\
> giscus est toujours en développement actif. De même, GitHub développe toujours activement son système de Discussions et l'API correspondante. Dès lors, certaines fonctionalités de giscus peuvent ne plus fonctionner ou changer à l'avenir.

## Comment cela fonctionne ?

Lorsque giscus se charge, l'[API de recherche des discussions de GitHub][search-api] est utilisée pour trouver la discussion associée à la page en fonction d'un mappage choisi (URL, `pathname`, `<title>`, etc.). Si aucune discussion correspondante ne peut être trouvée, le robot giscus créera automatiquement une nouvelle discussion la première fois que quelqu'un laissera un commentaire ou une réaction.

Pour commenter, les visiteurs doivent autoriser l'[application giscus][giscus-app] à [publier en leur nom][authorization] en utilisant le flux OAuth de GitHub. Les visiteurs peuvent également commenter directement la discussion sur GitHub. Vous pouvez modérer les commentaires sur GitHub.

[giscus]: https://giscus.app/fr
[discussions]: https://docs.github.com/en/discussions
[utterances]: https://github.com/utterance/utterances
[repo]: https://github.com/giscus/giscus
[advanced-usage]: https://github.com/giscus/giscus/blob/main/ADVANCED-USAGE.md
[creating-custom-themes]: https://github.com/giscus/giscus/blob/main/ADVANCED-USAGE.md#data-theme
[multiple-languages]: https://github.com/giscus/giscus/blob/main/CONTRIBUTING.md#adding-localizations
[self-hosting]: https://github.com/giscus/giscus/blob/main/SELF-HOSTING.md
[search-api]: https://docs.github.com/en/graphql/guides/using-the-graphql-api-for-discussions#search
[giscus-app]: https://github.com/apps/giscus
[authorization]: https://docs.github.com/en/developers/apps/identifying-and-authorizing-users-for-github-apps

## Sites utilisant giscus

- [laymonage.com][laymonage-website]
- [os.phil-opp.com][os-phil-opp]
- [Stats and R][statsandr]
- [Tech Debt Burndown Podcast][techdebtburndown]
- [**et bien plus encore!**][giscus-topic]

## Contribuer

Voir le fichier [CONTRIBUTING.md][contributing]

[giscus-component]: https://github.com/giscus/giscus-component
[repo]: https://github.com/giscus/giscus
[giscus-topic]: https://github.com/topics/giscus
[topic-howto]: https://docs.github.com/en/github/administering-a-repository/classifying-your-repository-with-topics
[advanced-usage]: https://github.com/giscus/giscus/blob/main/ADVANCED-USAGE.md
[utterances]: https://github.com/utterance/utterances
[gitalk]: https://github.com/gitalk/gitalk
[convert]: https://docs.github.com/en/discussions/managing-discussions-for-your-community/moderating-discussions#converting-an-issue-to-a-discussion
[laymonage-website]: https://laymonage.com/posts/giscus
[os-phil-opp]: https://os.phil-opp.com
[statsandr]: https://statsandr.com
[techdebtburndown]: https://techdebtburndown.com
[contributing]: https://github.com/giscus/giscus/blob/main/CONTRIBUTING.md


[![Propulsé par Vercel](public/powered-by-vercel.svg)][vercel]

[vercel]: https://vercel.com/?utm_source=giscus&utm_campaign=oss
