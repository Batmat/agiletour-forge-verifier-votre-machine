Comment vérifier votre machine ?
--------------------------------

- Cloner le présent dépôt Git avec succès

```
$ git clone https://github.com/Batmat/agiletour-forge-verifier-votre-machine.git
```
et/ou
```
$ git clone git@github.com:Batmat/agiletour-forge-verifier-votre-machine.git
```

La commande ci-dessus devrait afficher à peu près :
```
Cloning into 'agiletour-forge-verifier-votre-machine'...
remote: Counting objects: 5, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 5 (delta 0), reused 5 (delta 0)
Unpacking objects: 100% (5/5), done.
```

- Vérifier la présence d'un JDK _version 7_ sur votre machine
    - Exécutez la commande java*c* (attention, le c est *très* important. 
      Cela indique que le compilateur Java est bien présent, pas seulement la machine virtuelle).
      Votre affichage devrait ressembler à 

```
$ javac -version
javac 1.7.0_25
```

Notez le "1.7.x". Vérifiez bien votre version.

Si ce n'est pas le cas, rendez-vous sur [le site suivant](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html) 
pour y télécharger l'installateur de JDK correspondant à votre plateforme.

