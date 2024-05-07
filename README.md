EXERCICE N°2 :
On considère la déclaration de la classe Matrice suivante :
class Matrice {
private:
 int nbl;
 int nbc;
 int tab[Nmax][Nmax];
public:
 Matrice(int l, int c) ;// constructeur qui initialise les éléments à 0
 void saisie() ;// méthode qui permet de saisir les éléments du
tableau tab
 Matrice(const Matrice& other) // constructeur de recopie
 ~Matrice() ;// destructeur
 …..
 } ;
On demande de rajouter à cette classe :
- Une surcharge de l'opérateur d'affectation = entre deux matrices de même
dimension
- Une surcharge de l'opérateur de post-incrémentation (++) qui permet
d’incrémenter toutes les valeurs de la matrice de 1
- Une surcharge de l'opérateur d'addition + entre deux matrices de même
dimension
- Une surcharge de l'opérateur de multiplication * entre deux matrices de
dimensions adéquates.
- Une surcharge de l’opérateur d’extraction << pour afficher les éléments
d’une matrice
Donner ensuite la déclaration complète de la classe Matrice puis implémenter
les fonctions de surcharge d’opérateurs en dehors de la classe
