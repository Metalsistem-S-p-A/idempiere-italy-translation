- [Linee guida per la nomenclatura e lo stile in Idempiere](#linee-guida-per-la-nomenclatura-e-lo-stile-in-idempiere)
  - [Tabella delle scelte stilistiche](#tabella-delle-scelte-stilistiche)
  - [Regole grammaticali e stilistiche generali](#regole-grammaticali-e-stilistiche-generali)
  - [Tabella delle scelte di abbreviazioni](#tabella-delle-scelte-di-abbreviazioni)
  - [Tabella delle scelte di sinonimi](#tabella-delle-scelte-di-sinonimi)


# Linee guida per la nomenclatura e lo stile in Idempiere

IDempiere utilizza per scelta anglosassone la **Title Case** (es. "Questo È Un Campo"), uno stile tipico dei titoli in inglese. Tuttavia, questa scelta non è ottimale per l'italiano.

Si è deciso di adottare la **Sentence case** (es. "Questo è un campo") per le seguenti ragioni:

- **Migliora la leggibilità**: la capitalizzazione naturale è più fluida e meno "rigida".
- **Si adatta meglio all'italiano**: in italiano, l'uso della maiuscola all'inizio di ogni parola è innaturale.
- **Seguiamo le tendenze moderne**: anche in inglese, le interfacce moderne dei grandi marchi (Google, Microsoft, Apple, etc...) tendono a preferire la **Sentence case** per migliorare l'usabilità.
- **Mantenere coerenza con altre parti del sistema**: se i messaggi di errore, le descrizioni e altri testi seguono la sentence case, è bene uniformare tutto il sistema.

## Tabella delle scelte stilistiche
Una lista esemplificativa dello stilo da adottare è la seguente.

| Scelta            | Stile adottato         | Esempio                  |
|------------------|-------------------------|--------------------------|
| Capitalizzazione | Sentence case           | "Nome del cliente"       |
| Pulsanti         | Sentence case           | "Salva impostazioni"     |
| Menu             | Sentence case           | "Gestione ordini"        |
| Titoli           | Sentence case           | "Dati dell'anagrafica"   |
| Sigle            | Maiuscolo               | "IVA", "CF", "IBAN"      |
| Date             | Formato italiano        | "25/12/2024"             |
| Importi          | Con separatore migliaia | "1.234,56 €"             |
| Nomi di report   | Sentence case           | "Situazione magazzino"   |

## Regole grammaticali e stilistiche generali
- **Evitare l'uso eccessivo di maiuscole**: solo i nomi propri e le sigle vanno in maiuscolo.
- **Evitare abbreviazioni non necessarie**: scrivere "Quantità disponibile" invece di "Q.tà disp."
- **Mantenere coerenza terminologica**: utilizzare sempre lo stesso termine per riferirsi a un concetto (es. "Cliente" e non talvolta "Cliente" e talvolta "Anagrafica cliente").
- **Usare la punteggiatura correttamente**: non inserire punti finali nei titoli o nelle etichette di campo.

Queste regole garantiranno un'interfaccia più chiara, leggibile e coerente con la lingua italiana.

## Tabella delle scelte di abbreviazioni
Nel caso si renda necessario ricorrere ad abbreviazioni o troncature, rifarsi alla tabella seguente, per quanto possibile, nel tentativo di mantenere coerenza tra la abbreviazioni scelte.

| Termine esteso    | Abbreviazione        |
|-------------------|----------------------|
| Numero            | N.                   |
| Distinta base     | DiBa                 |
| Quantità          | Q.tà                 |
| Business partner  | BP                   |
| Unità di misura   | UdM                  |
| Partita IVA       | P.IVA                |
| Codice fiscale    | C.F.                 |

## Tabella delle scelte di sinonimi
Per lo stesso motivo mantenere coerenza tra i sinonimi scelti. Salvo eccezioni, rifarsi alla tabella seguente.

| Termine scelto        | Sinonimi (da evitare)                 |
|-----------------------|---------------------------------------|
| riga e righe          | linea, linee                          |
| obiettivo, obiettivi  | obbiettivo, obiettivi                 |
| È (ALT+0200)          | E'                                    |
| intestazione          | testata                               |
| piè di pagina         | fondo pagina                          |
| attività              | compito, compiti                      |
| approfondimento       | drill                                 |
| ubicazione            | area di stoccaggio                    |
| finestre informative  | info window, finestre di informazione |
| workflow              | flusso di lavoro                      |