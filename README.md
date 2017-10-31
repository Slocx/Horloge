#include <stdio.h>
#include <stdlib.h>
#include <string.h>

#include "actions.h"
#include "entreeSortie.h"

// Fonction principale main
// argc - nombre d'arguments passés dans argv
// argv - tableau d'arguments passés lors du lancement du programme exécutable

// "Automate de lecture des heures\n"
// "Format disponible : hh:mm:ss -> hh de 00-23, mm et ss de 00-59\n"

int main(int argc, char *argv[])
{
    int i = 0; // compteur pour la boucle
    struct lTransitions *automate[NBETATS]; // Tableau de pointeurs vers listes des transitions d'état
    int etatInitial, etatFinal; // variables que contiendront l'état initial et final de l'automate - lues dans le fichier
    short cdr; // code de retour
    char *tableHeuresTests[NBTEST]; // tableau de heures
    FILE *fout = NULL; // fichier résultat des tests

    // TODO : Initialiser tous les éléments de la tableau 'automate' à NULL

    // TODO : Initialiser tous les éléments de la tableau de test 'tableDatetests' à NULL

    // TODO : Lecture du fichier "automate.txt" (utiliser les fonctions déjà définies)

    // TODO : Lire fichier de données de test "HeuresTests.txt" (utiliser les fonctions déjà définies)

    // Ouvrir le fichier de résultats en écriture
    fout = fopen("./ResultatsHeuresTests.txt", "w");
    // TODO : Vérifier si le fichier a bien été ouvert. Sinon, envoyer une erreur et sortir du programme

    // TODO : Initialiser la lecture du tableau de heures de tests

    while (// TODO //)
    {
       // TODO - Analyser ce mot avec l'automate (faire appel à des fonctions déjà définies)

       // TODO - Ecrire le résultat de l'analyse dans le fichier résultats (faire appel à des fonctions déjà définies)
    }

    // TODO - Libérer les transitions, qui sont les structures dynamiques de l'automate (faire appel à des fonctions déjà définies)

    // TODO : Fermer le fichier de résultats

    return 0;
}
