# Tp1-INF231
Exercice en C sur structure de donnée II (9 exercices)
exercise 9: le produit des vecteurs x matrice ( il est constituer des commentaire a une ligne representer par // qui explique chaque paragraphe de codes ) 

#include <stdio.h>
int main(void) {
    int n, m;
    printf("entrez la taille du vecteur :\n");
    scanf("%d", &n);
    printf("colonnes de la matrice:\m");
    scanf("%d", &m);
    double v[n], A[n][m], res[m];
    // lecture du vecteur
    for (int i = 0; i < n; i++) 
{
        printf("v[%d] = ", i);
        scanf("%lf", &v[i]);
    }
    // lecture de la matrice
    for (int i = 0; i < n; i++) 
{
        for (int j = 0; j < m; j++) 
{
            printf("A[%d][%d] = ", i, j);
            scanf("%lf", &A[i][j]);
        }
    }
    // initialisation du résultat
    for (int j = 0; j < m; j++) res[j] = 0; 
// calcul produit vecteur x matrice
    for (int i = 0; i < n; i++)
 {
        for (int j = 0; j < m; j++)
 {
            res[j] += v[i] * A[i][j];
        }
    }
// affichage résultat
    printf("Résultat : [");
    for (int j = 0; j < m; j++) 
{
        printf("%g", res[j]);
        if (j < m - 1) printf(", ");
    }
    printf("]\n");
    return 0;
}
