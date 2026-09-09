# 1ere faute (Omission du point-virgule) 

## Message d'erreur 

``` bash
c1-exo3_main.cpp:5:40: error: expected ';' after expression
    5 |     std::cout << "Yaounde" << std::endl
      |                                        ^
      |                                        ;
1 error generated.
```

## Ligne signalée : 
Ligne 5

## Ligne réellement fautive : 
Ligne 5

## Étape de la chaine qui a parlé
Le compilateur 

# 2eme faute (Cout au lieu de cout) 

## Message d'erreur 

``` bash
c1-exo3_main.cpp:4:10: error: no member named 'Cout' in namespace 'std'; did you mean 'cout'?
    4 |     std::Cout << "EPONSE MEKONTSO Ben-salem Emmanuel" << std::endl;
      |     ~~~~~^~~~
      |          cout
/usr/bin/../lib/gcc/x86_64-linux-gnu/13/../../../../include/c++/13/iostream:63:18: note: 'cout' declared here
   63 |   extern ostream cout;          ///< Linked to standard output
      |                  ^
1 error generated.
```

## Ligne signalée : 
Ligne 4

## Ligne réellement fautive : 
Ligne 4

## Étape de la chaine qui a parlé
Le compilateur 

# 3eme faute (Omission de la ligne #include <iostream>) 

## Message d'erreur 

``` bash
c1-exo3_main.cpp:3:5: error: use of undeclared identifier 'std'
    3 |     std::cout << "EPONSE MEKONTSO Ben-salem Emmanuel" << std::endl;
      |     ^
c1-exo3_main.cpp:3:58: error: use of undeclared identifier 'std'
    3 |     std::cout << "EPONSE MEKONTSO Ben-salem Emmanuel" << std::endl;
      |                                                          ^
c1-exo3_main.cpp:4:5: error: use of undeclared identifier 'std'
    4 |     std::cout << "Yaounde" << std::endl;
      |     ^
c1-exo3_main.cpp:4:31: error: use of undeclared identifier 'std'
    4 |     std::cout << "Yaounde" << std::endl;
      |                               ^
4 errors generated.
```

## Ligne signalée : 
Ligne 3, ligne 4

## Ligne réellement fautive : 
Ligne 1

## Étape de la chaine qui a parlé
Le compilateur 
