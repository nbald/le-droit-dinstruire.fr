# Le droit d'instruire

Le guide de référence sur l'instruction en famille en France, fondé sur l'analyse de la jurisprudence.

**Site : [le-droit-dinstruire.fr](https://le-droit-dinstruire.fr)**

## De quoi s'agit-il ?

Depuis la loi du 24 août 2021, l'instruction en famille (IEF) est soumise à autorisation préalable. Les familles font face à un paysage administratif et juridique complexe. Ce site rassemble plus de 159 décisions de justice (2013–2026) et explique, en langage clair, ce que dit réellement la jurisprudence — de la stratégie de dépôt au recours contentieux.

## Stack technique

- [MkDocs](https://www.mkdocs.org/) avec [Material for MkDocs](https://squidfunnel.github.io/mkdocs-material/)
- Contenu en français, rédigé en Markdown

## Lancer le site en local

```bash
pip install -r requirements.txt
mkdocs serve -a 0.0.0.0:8008
```

Le site sera accessible sur `http://localhost:8008`.

## Structure du projet

```
docs/
├── preparer/       # Préparer sa demande d'autorisation
├── contester/      # Contester un refus
├── europe/         # Droit européen (CEDH, comparaison)
├── apres/          # Après l'autorisation (contrôles, enquêtes)
├── cout-humain/    # Le coût humain
├── decisions/      # 159 décisions de justice (texte intégral)
├── a-propos/       # Qui sommes-nous et glossaire
└── index.md        # Page d'accueil
mkdocs.yml          # Configuration du site
```

## Licence

Le contenu est sous licence [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — voir [LICENSE](LICENSE).
