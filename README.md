elif choix == 3:
         def SupprimerUnLivre(livre):
            for index, livre_catalogue in enumerate(catalogue):
               if livre_catalogue == livre:
                 del catalogue[index]
                 print(f"Livre supprimé avec succès",livre)
                 return
                 print(f"Livre non trouvé",livre)
     elif choix == 4:
         def AfficherUnLivre(livre):
             if livre:
                print(f"\nDetails du livre:")
                print(f"titre",livre.titre)
                print(f"auteur",livre.auteur)
                print(f"genre",livre.genre)
                print(f"pages",livre.page)
                print(f"etat",livre.etat)
             else:
                print("livre non trouvé.")
