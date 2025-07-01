# C#ulatrice 🧮

Une calculatrice console en C# qui rend hommage à l'art noble de la programmation COBOL ! 

## Description

**C#ulatrice** est une calculatrice interactive en mode console développée en C#.

### Fonctionnalités

- ✅ **Addition** - Parce que 1 + 1 = 2 (même en COBOL)
- ✅ **Soustraction** - Pour retirer ce qui ne sert plus
- ✅ **Multiplication** - Multiplier les possibilités
- ✅ **Division** - Diviser pour mieux régner (avec gestion du zéro !)
- ✅ **Puissance** - Élever au rang supérieur
- ✅ **Mémoire persistante** - Les résultats sont conservés entre les opérations
- ✅ **Réinitialisation** - Pour repartir à zéro
- ✅ **Interface utilisateur soignée** - Avec des bordures en ASCII art digne du mainframe

## Utilisation

1. Lancez l'application
2. Choisissez une opération dans le menu principal (1-6)
3. Entrez vos nombres quand demandé
4. Le résultat est automatiquement conservé en mémoire pour les calculs suivants
5. Tapez 'M' à tout moment pour revenir au menu principal
6. Option 6 pour nettoyer la mémoire
7. Option 0 pour quitter... mais attention au message de confirmation !

## Easter Eggs 🥚

- **Message de sortie** : Une petite leçon d'humilité informatique vous attend à la sortie
- **Syntaxe COBOL** : Le menu principal arbore fièrement des `DISPLAY` statements
- **Références nostalgiques** : Parce que le COBOL, c'est du sérieux !

## Structure du projet

```
C_ulatrice/
├── Program.cs              # Point d'entrée principal
├── Menu/
│   └── MenuPrincipal.cs    # Gestion de l'affichage du menu
└── README.md
```

## Particularités techniques

- **Gestion robuste des entrées** : Validation des saisies utilisateur
- **Gestion des erreurs** : Division par zéro et entrées invalides
- **Interface console soignée** : Effacement d'écran et formatage ASCII
- **Mémoire persistante** : Conservation des résultats entre opérations
- **Navigation intuitive** : Retour au menu avec 'M'

## Exemple d'utilisation

```
******************************************
 DISPLAY "*     Choisir l'operation   *".
 DISPLAY "*---------------------------*".
 DISPLAY "* 1 - Addition              *".
 DISPLAY "* 2 - Soustraction          *".
 DISPLAY "* 3 - Multiplication        *".
 DISPLAY "* 4 - Division              *".
 DISPLAY "* 5 - Puissance             *".
 DISPLAY "* 6 - Réinitialisation      *".
 DISPLAY "* 0 - Quitter le programme  *".
******************************************
```

## Contribution

Les contributions sont les bienvenues ! Surtout si elles ajoutent plus de références COBOL. 

## Licence

Ce projet est sous licence MIT - Parce que même le code legacy mérite d'être libre !

## Remerciements

Un grand merci à COBOL pour avoir inspiré cette œuvre d'art moderne. Que les `WORKING-STORAGE SECTION` soient avec vous ! 🙏

---

*"Dans le doute, utilisez COBOL. Dans le doute absolu, utilisez cette calculatrice C#."*
