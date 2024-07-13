from livre import AjouterLivre

def menu_principale():
    print("1. ajouter un livre")
    print("2. rechercher livre")
    print("3. supprimer livre")
    print("4. afficher livre")
    print("5. empruter livre")
    print("6. retourner livre")
    print("Quitter")
    choix =int(input("selectionnez une option"))
    return choix
def main():
    while True:
     choix  = menu_principale()

     if choix == 1:
        def AjouterLivre():
            disponibleLivre = True
            idlivre = int(input("saisir l'Id du livre"))
            TitreLivre = input("saisir le nom du livre")
            AuteurLivre = input("saisir l'auteur du livrez")
            genreLivre = input("saisir le genre du livre")        
     elif choix == 2:
        def RechercherUnLivre_par_auteur(livre):
           for livre in catalogue:
             if livre in livre.auteur.lower() == auteur.lower():
                return livre
           return None
        def RechercherUnLivre_par_titre(livre):
           for livre in catalogue:
             if livre.auteur.lower() == auteur.lower():
                return livre
           return None
        def RechercherUnLivre_par_genre(livre):
           for livre in catalogue:
             if livre.genre.lower() == genre.lower():
                return livre
           return None 
     
