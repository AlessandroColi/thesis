# Abstract :it:

Questa tesi descrive l'intero processo di progettazione e sviluppo di un progetto Kotlin Multiplatform, partendo dall'analisi dei requisiti, comprendendo le fasi di progettazione, sviluppo, validazione e infine la fase di integrazione all'interno di PulvReAKt. 

Il Progetto si propone di gestire in maniera ottimale le comunicazioni tra molteplici entità, offrendo loro la possibilità di mandare messaggi specificando il destinatario e di leggere messaggi da un mittente specifico. Per offrire tali funzionalità il Progetto sfrutta il protocollo MQTT e gestisce autonomamente i topic al suo interno in modo tale da garantire di operare come atteso dall'utente.

Il Progetto è stato sviluppato autonomamente e può essere inserito, con leggeri adattamenti, all'interno di qualsiasi progetto Kotlin Multiplatform interessato alla funzionalità offerte dal progetto per uno o più target tra quelli per cui è stato sviluppato (JVM, Native e NodeJS). In particolare nell'ambito di questa tesi il progetto è stato anche integrato nel più ampio contesto del progetto PulvReAKt, all'interno del quale ha il compito di gestire le comunicazioni remote tra le entità del progetto dislocate in siti differenti.

Infine, con lo scopo di dare un'evidenza pratica delle prestazioni del progetto sviluppato nelle diverse condizioni di lavoro, in questa tesi viene riportato anche un confronto tra i tempi di esecuzione sulle diverse piattaforme interessate. Questo semplice dato mostra in maniera chiara come il progetto performi in diverse condizioni e può quindi rappresentare un elemento di scelta nel caso di futura integrazione in nuovi progetti.

# Abstract :uk:

This thesis describes the entire design and development process for a Kotlin Multiplatform project, starting with requirements analysis, encompassing the design, development, validation, and finally the integration phase within PulvReAKt.

The project aims to optimally manage communications between multiple entities, offering them the ability to send messages specifying the recipient and read messages from a specific sender. To offer these features, the project leverages the MQTT protocol and autonomously manages its topics to ensure it operates as expected by the user.

The project was developed independently and can be inserted, with slight adaptations, into any Kotlin Multiplatform project interested in the functionality offered by the project for one or more of its intended targets (JVM, Native, and NodeJS). Specifically, within this thesis, the project was also integrated into the broader PulvReAKt project, where it manages remote communications between project entities located at different sites.

Finally, to provide practical evidence of the project's performance under different working conditions, this thesis also reports a comparison of execution times across the various platforms involved. This simple data clearly demonstrates how the project performs under different conditions and can therefore be a key consideration for future integration into new projects.
