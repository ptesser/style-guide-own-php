# Style Guide (own): PHP - ITA

Queste linee guida sono in parte perzonalizzate, anche se fanno un riepilogo di quelle migliori che ho trovato da fonti esterne e che utilizzo nei miei progetti.


## Naming

I nomi di variabili, metodi devono essere in lowerCase.


    public function getAnimals()
    {
        $nameIsSet = false;
        # some code ... :D
    }

I nomi delle classi devono essere in CamelCase.

    class ClassName
    {
        some code ...
    }


I nomi dei file si distinguono in due categorie:

- file che contengono classi, devono essere nominati come il nome della classe in CamelCase.php
- file procedurali o che contengono delle configurazioni, devono essere in lowerCase.php

## Indentation

L'indentazione deve essere di 4 (spazi/tabs) questo per favorire la leggibilitá del codice.

## Spacing

La parentesi graffa di apertura di una classe o di un metodo, va nella riga successiva, come visulizzato nella sezione Naming.


Ogni riga di codice all'interno di uno stesso blocco deve essere separata da una linea vuota a meno che le righe successive non appartengano ad una stessa logica o che si stia dichiarando/inizializzando una serie di variabili.

Ogni blocco di codice (if, while, for, switch) deve essere separato, sia prima che dopo, da una riga vuota.

    some code ...

    if(some condition){ # block of code

    }

    other code ...

Non devono essere presenti spaziature fra la keywork relativa al blocco di codice `if(some condition){}` e la prima parantesi. La paretesi graffa di apertura del blocco deve stare sulla stessa linea.

Separare con uno spazio tutte il codice presente all'interno blocco.

    if(test === true)
    # oppure
    for($i = 0; $i < 10; $i++){}

## Quotation Mark

Vanno utilizzati sempre i doppi apici.

## Test condition

Il controllo di una condizione logica deve essere effettuato sempre con il triplo operatore (=== invece di ==).

## Documentation

Seguire lo standard offerto da PHPDocumentator.

## Force style guide





## References/Resource

- http://www.php-fig.org/psr/psr-2/
- https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
