# Boolkaichi

## INDICE

1. [Panoramica](#panoramica)
2. [Linguaggi usati](#linguaggi-usati)
3. [Scelta dell’arma](#milestone-1---scelta-dellarma)
    1. [Flow](#flow-1)
4. [Allenamento](#milestone-2---allenamento)
    1. [Flow](#flow-2)

## Panoramica

Questo esercizio, ispirato al torneo Tenkaichi di Dragon Ball, è stato svolto il collaborazione con [Simone D'Urso](https://github.com/SimoneDUrso).
Tale piccolo progetto è da intendersi come esercitazione su console, principalmente per il ripasso dei metodi per gli array.
L'esercizio è suddiviso in Milestone.

## Linguaggi usati
HTML, Javascript vanilla.

## Milestone 1 - Scelta dell’arma
Ogni combattente sceglierà casualmente un'arma dalla relativa lista. Una volta scelta, un'arma non sarà più disponibile per i successivi combattenti.

### Flow 1
- Creo un ciclo FOR che itera ogni combattente dell'array 'fighters'
    - Genero un indice casuale per la selezione randomica di un arma dell'array 'weapons'
    - Estraggo il potere del combattente corrente
    - Estraggo il potere dell'arma
    - Calcolo il potere totale
    - Stampo su console i dettagli
    - Rimuovo l'arma appena scelta dall'array 'weapons', così da non essere più selezionabile dagli altri combattenti

## Milestone 2 - Allenamento
Ogni combattente si sottoporrà ad un allenamento che incrementerà (o forse no) la sua potenza, moltiplicandola per un numero casuale tra 1 e 100.

### Flow 2