### Algorithmie

#### 1)

Voici la représentation d'un filesystem

avec des dossiers et des fichiers.
les fichiers ont une taille en bit. 

Calculer la taille totale du filesystem

``` py
filesystem = {
    'Documents': {
        'work' : {
            'CV.txt': 10,
            'contract.pdf': 255,
        }
    },
    'Downloads': {
        'ubuntu.22.04.iso': 15000,
        'image.png': 241,
        ''
    },
    'Code': {
        'api': {
            'main.py': 100,
            'src': {
                'utils.py': 20,
                'time.py': 46',
            }
            'config.json': 35
        }
        'web': {
            'index.html': 96,
            'img': {
                'logo.png': 12,
                'background': 30,
            }
        }
    }
}

# 15859
```

#### 2)

Une fourmi est sur une grille de taille N * N, qui contient des récompenses de valeur differentes

Elle part du coin en haut à gauche et droit arriver en bas à droite. 
A chaque fois elle peut se déplacer uniquement soit vers la droite, soit vers le bas

On veut maximiser la somme des récompneses.

Quelle est la complexité de la solution ? Pourquoi ? Proposer un algo

``` 
board = [
    [1, 2, 0, 1, 4],
    [3, 3, 0, 2, 0],
    [1, 0, 0, 0, 1],
    [3, 0, 2, 0, 1],
    [0, 5, 0, 2, 0]
]

# 15
```
