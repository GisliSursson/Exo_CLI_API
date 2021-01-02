# Exercice CLI (Command Line Interface) et API
Exercice réalisé par Pierre T. et Victor M. lors du cours de Python de M. Clérice dans le cadre du Master TNAH de l'Ecole des chartes. Outil CLI permettant d'interagir avec l'API RNA (Registre National des Associations) afin de trouver les associations correspondant à un thème donné (*query*). Voir la [documentation](https://api.gouv.fr/les-api/api_rna) de l'API.

# Syntaxe (terminal *bash*)

```bash
python(3) rna.py search [query] [res_par_page (max=100, def=20)] [num_page (def=1)]
```
En cas de query à plusieurs mots, les mettre entre guillemets. Exemple : 'football association'.
## Informations renvoyées :
- Numéro d'identifiant
- Nom
- Date de création
- Commune
- Département
- Objet

## *Requirements*
- Python3
- Click
- Requests
- CSV
