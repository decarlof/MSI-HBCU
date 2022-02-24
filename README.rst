This python code finds the match (intersection) between two list.

It supports fuzzy match, to handle misspelling or typing errors. The result include a probability match score (0-100 with 100 equal to perfect match)

Example searching for::

['Cambrxidge Collxdege', 'Canada College', 'Chabot College', 'Chemeketa Community College']

gives:

::

Exact Match: ['Canada College', 'Chabot College', 'Chemeketa Community College']
Fuzzy Match [(92, 'Cambridge College'), (100, 'Canada College'), (100, 'Chabot College'), (100, 'Chemeketa Community College')]