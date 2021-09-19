# ktr-msc-ls1
import tkinter as tk

name=str(input("name:"))
company_name=str(input("company name:"))
Email=str(input("Email:"))
tel=int(input("tel:"))
tele=str(tel)

#verification du téléphone
longueur=len(tele)
if longueur !=9:
    print("le numéro de téléphone est invalide")
else:
    print("ok")

#vérification name
if len(name)<=1:
    print("erreur, le nom est trop court")
else:
     print("correcte")
     
#def verif_name(n):
 #if len(name)<=1:
   #pint("erreur, le nom est trop court")
 #else:
  #print("correcte")
 #return name
 #verif_name(Ly)
    

def Motdepasse():
    Motdepasse = tk.StringVar()
    champ = tk.Entry(user1, textvariable= Motdepasse, show='*', bg ='blue', fg='black')
    champ.focus_set()
    champ.place(x=680, y=230, anchor='w') 
    entete = tk.Label(user1='Saisir votre mot de passe', font = ('Tw Cen MT', 20))
    entete.place(x=700, y=200, anchor='w')
 
 dico={"name":"Kim","company-name":"epitech","email":"kim@gmail.com","tel":0784571489}
    
    
  
  
