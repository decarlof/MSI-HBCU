This python code finds the match (intersection) between two list.

It supports fuzzy match, to handle misspelling or typing errors. The result includes the Levenshtein distance between the two strings under comparison (100 is perfect match)

Example searching for::

    ['Cambrxidge Collxdege', 'Canada College', 'Chaboet College', 'Chemmeketa Comunity Collage']

gives::

    Exact Match: ['Canada College']
    Fuzzy Match [(92, 'Cambridge College'), (100, 'Canada College'), (97, 'Chabot College'), (93, 'Chemeketa Community College')]