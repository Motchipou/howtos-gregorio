# howtos-gregorio

README.md - v.a0.08 - 2015.06.17
mar 16.06.2015 (Date de création)

1. vim README.md
2. git status (README.md en _rouge_)
3. git add README.md
4. git status (README.md en _vert_)
5. git commit -m "README.md modif 3"
6. git push (user:Motchipou - pwd:[xxxxx])

	

GitHub tutorial  -  GitHub For Beginners: Don't Get Scared, Get Started

**_GitHub for beginners - part 1_**

=> http://readwrite.com/2013/10/02/github-for-beginners-part-1



**_GitHub tutorial  -  GitHub for beginners - part 2_**

=> http://readwrite.com/2013/10/02/github-for-beginners-part-2



### Mémento - GitHub modifications

###### Step 1. - vim README.md

###### Step 2. - get status

Le fichier 'README.md' (modifié en 'Step 1') a le statut "rouge".

Ne fait (font) pas partie des fichiers prêt à être committé (= validé) pcq
modifié ou nouvellement créé.

###### Step 3. - git add

git add README.md

###### Step 4. - git status

Le fichier 'README.md' ayant été ajouté à la liste d'attente ('git ad') 
paraît en "vert" = prêt à être validé (ou 'committé')

###### Step 5. - git commit

git commit -m "Message de commit" (Pq modif ou Description nouveau fichier


###### Step 6. - git push

git push


User name : Motchipou

Password  : xxxxxxxxxx


__Attention !!!__  
  
1. 'Cloner' le repo :

    > git clone https://github.com/Motchipou/howtos-gregorio.git   
	(voir point (9) ci-après pour plus de détails) 



## Installation sous Windows

1. En mode 'Terminal' (Sous DOS) :
   C:\Users\Etienne
	 > git --version
   > git version 1.9.5.msysgit.1

2. C:\Users\Etienne>
   > git config --global user.name "Motchipou"

3. C:\Users\Etienne>
   > git config --global user.email "moreau.etienne@gmail.com"

4. C:\Users\Etienne>
   > md github

5. C:\Users\Etienne>
   > cd github

6. C:\Users\Etienne\github>
   > git init
   > Initialized empty Git repository in C:/Users/Etienne/github/.git/

7. C:\Users\Etienne\github>
   > dir  
   Le volume dans le lecteur C s’appelle HP  
   Le numéro de série du volume est 2C7C-F0D4  
  
   Répertoire de C:\Users\Etienne\github  
  
   16/06/2015  20:57    <REP>          .  
   16/06/2015  20:57    <REP>          ..  
                  0 fichier(s)                0 octets  
                  2 Rép(s)  531.394.404.352 octets libres  

8. C:\Users\Etienne\github>
   > git remote add origin https://github.com/Motchipou/howtos-gregorio.git
  
   C:\Users\Etienne\github>
	 > dir  
   Le volume dans le lecteur C s’appelle HP  
   Le numéro de série du volume est 2C7C-F0D4  
  
   Répertoire de C:\Users\Etienne\github  
  
   16/06/2015  20:57    <REP>          .  
   16/06/2015  20:57    <REP>          ..  
                  0 fichier(s)                0 octets  
                  2 Rép(s)  531.392.933.888 octets libres  
  
 9. C:\Users\Etienne\github>
    > cd ..  

10. C:\Users\Etienne\github>
    > git clone https://github.com/Motchipou/howtos-gregorio.git   
    Cloning into 'howtos-gregorio'...   
    remote: Counting objects: 16, done.   
    remote: Compressing objects: 100% (12/12), done.  
    remote: Total 16 (delta 2), reused 15 (delta 1), pack-reused 0  
    Unpacking objects: 100% (16/16), done.  
    Checking connectivity... done.  

11. C:\Users\Etienne\github>
    > dir  
    Le volume dans le lecteur C s’appelle HP  
    Le numéro de série du volume est 2C7C-F0D4  

    Répertoire de C:\Users\Etienne\github  
  
    16/06/2015  21:28    <REP>          .  
    16/06/2015  21:28    <REP>          ..  
    16/06/2015  21:28    <REP>          howtos-gregorio  
                  0 fichier(s)                0 octets  
                  3 Rép(s)  531.393.871.872 octets libres  
  
12. C:\Users\Etienne\github>  
    > cd howtos-gregorio  

13. C:\Users\Etienne\github\howtos-gregorio>
    > dir  
    Le volume dans le lecteur C s’appelle HP   
    Le numéro de série du volume est 2C7C-F0D4   
   
    Répertoire de C:\Users\Etienne\github\howtos-gregorio   
  
    16/06/2015  21:28    <REP>          .   
    16/06/2015  21:28    <REP>          ..   
    16/06/2015  21:28             1.262 README.md   
    16/06/2015  21:28                 0 Readme.txt   
    16/06/2015  21:28               867 test.md   
                   3 fichier(s)            2.129 octets   
                   2 Rép(s)  531.393.871.872 octets libres   

14. C:\Users\Etienne\github\howtos-gregorio>   
    > gvim README.md   


