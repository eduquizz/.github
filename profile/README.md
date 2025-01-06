# Eduquizz

## Auteurs

Étudiants du **Groupe A** :
- [Tristan GAIDO](https://github.com/tristan-gaido)
- [Eric GILLES](https://github.com/eric-gilles)
- [Pablo LAVIRON](https://github.com/0lbap)
- [Morgan NAVEL](https://github.com/MorganNavel)
- [Enzo VIGUIER](https://github.com/enzo-viguier)

## Installation

Pour installer la suite d'outils d'Eduquizz, suivez les instructions suivantes.

1. Créez une nouvelle _workspace_ Eclipse
2. Ouvrez un terminal dans le dossier de cette _workspace_
3. Clonez les différents dépôts Git d'Eduquizz :
   ```bash
   git clone git@github.com:eduquizz/mm1.git
   git clone git@github.com:eduquizz/mm2.git
   git clone git@github.com:eduquizz/xtext.git
   git clone git@github.com:eduquizz/m2m.git
   git clone git@github.com:eduquizz/m2t.git
   ```
4. Dans Eclipse, cliquez sur <kbd>File</kbd>, puis <kbd>Open Projects from File System...</kbd>
5. Dans le champ "Import Source", cliquez sur <kbd>Directory...</kbd>
6. Sélectionnez le répertoire de la _workspace_, puis cliquez sur <kbd>Open</kbd>
7. Les projets trouvés s'affichent sous forme de liste avec des cases à cocher
8. Cochez toutes les cases sauf la première (celle de la _workspace_)
9. Cliquez sur <kbd>Finish</kbd> : tous les projets ont été importés !

> [!NOTE]
> Des erreurs de _build_ peuvent survenir après avoir chargé les projets :
> - _Cannot find class <...>_ : Vérifiez que le projet utilise bien le JRE Java 21
> - _Missing source folder <...>_ : Créez les dossiers vides manquants
> - _<...>.jar is missing_ : Corrigez le chemin du JAR dans le _Build Path_ du projet
