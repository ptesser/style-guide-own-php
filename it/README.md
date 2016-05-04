# Style Guide (own): PHP - ITA

Queste linee guida sono in parte perzonalizzate, anche se fanno un riepilogo di quelle migliori che ho trovato da fonti esterne e che utilizzo nei miei progetti.


## Naming

I nomi di variabili, metodi devono essere in lowerCase.

    $nameIsSet = false;


I nomi delle classi devono essere in CamelCase.

    class ClassName
    {
        some code ...
    }


I nomi dei file si distinguono in due categorie:

- file che contengono classi, devono essere nominati come il nome della classe in CamelCase.php
- file procedurali o che contengono delle configurazioni, devono essere in lowerCase.php

## Indentation

L'indentazione deve essere di 4 (spazi/tabs) questo per favorire la leggibilitá deal codice.

## Spacing

Ogni riga di codice all'interno di uno stesso blocco deve essere separata da una linea vuota a meno che le righe successive non appartengano ad una stessa logica o che si stia dichiarando/inizializzando una serie di variabili.

Ogni blocco di codice (if, while, for, switch) deve essere separato, sia prima che dopo, da una riga vuota.

    some code ...

    if(some condition){ # block of code

    }

    other code ...

Non devono essere presenti spaziature fra TODO

Separare TODO

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
