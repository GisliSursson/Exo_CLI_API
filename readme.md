<h1>Exercice CLI (Command Line Interface) et API</h1>
<p>Exercice réalisé par Pierre T. et Victor M. dans le cadre du Master TNAH de l'Ecole des chartes. Outil CLI permettant d'interagir avec l'API RNA (Registre National des Associations).<a href="https://api.gouv.fr/les-api/api_rna">Voir la documentation de l'API</a>.</p>
<p>Exécute une recherche sur RNA en utilisant [QUERY] dans le libellé des associations.
    Syntaxe : python(3) rna.py search [query] [res_par_page (max=100, def=20)] [num_page (def=1)].
    En cas de query à plusieurs mots, les mettre entre guillemets. Exemple : 'football association'.</p>
