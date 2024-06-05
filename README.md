# INAD_API_estrazione

Le Specifiche tecniche API estrazione dei domicili digitali riportate 
nel presente repository attuano quanto previsto al paragrafo **2.5. 
Estrazione dei dati** delle **Linee Guida dell’Indice nazionale dei 
domicili digitali delle persone fisiche, dei professionisti e degli 
altri enti di diritto privato non tenuti all’iscrizione in albi, elenchi 
o registri professionali o nel registro delle imprese** (in breve INAD), 
adottate da AgID ai sensi dell'articolo 71 del Decreto Legislativo 7 
marzo 2005, n. 82 e smi con Determinazione n. 598 del 8 novembre 2021. 

L\'OpenAPI riportato in [inad_api_extraxtion.yaml](https://github.com/AgID/INAD_API_Extraction/blob/main/inad_api_extraxtion.yaml) 
(consultabile tramite [Swagger Editor](https://editor.swagger.io/?url=https://raw.githubusercontent.com/AgID/INAD_API_Extraction/main/inad_api_extraxtion.yaml)), 
definisce le modalità tecniche con cui i soggetti di cui all’articolo 2, comma 2, 
lettere a) e b) del Decreto legislativo 7 marzo 2005, n. 82 accedono ai domicili 
digitali eletti nell’INAD.

Le specifiche tecniche sono definite in coerenza con il quadro normativo 
in materia di interoperabilità dei sistemi informatici delle pubbliche 
amministrazione, e nello specifico delle:

- **Linee Guida sull’interoperabilità tecnica delle Pubbliche Amministrazioni**, 
  adottate dal AgID ai sensi dell’articolo 73, comma 3-ter, lettera b) 
  del Decreto legislativo 7 marzo 2005, n. 82;

- **Linee Guida Tecnologie e standard per la sicurezza dell’interoperabilità tramite API dei sistemi informatici**, 
  adottate dal AgID ai sensi dell’articolo 73, comma 3-ter, lettera b) 
  e dell’articolo 51 del Decreto legislativo 7 marzo 2005, n. 82.

La costruzione del trust tra INAD e i sistemi ICT delle PA è realizzato 
per il tramite della infrastruttura tecnologica della Piattaforma Digitale
Nazionale Dati per l’interoperabilità ai sensi delle:

- **Linee Guida sull’infrastruttura tecnologica della Piattaforma Digitale Nazionale Dati per l’interoperabilità dei sistemi informativi e delle basi di dati**, 
  adottate dal AgID ai sensi dell’articolo 50-ter, comma 2 del Decreto 
  legislativo 7 marzo 2005, n. 82.

Il servizio per permettere la gestione dei domicili digitali da parte dei soggetti previsti dalle 
**Linee Guida dell’Indice nazionale dei domicili digitali delle persone fisiche, dei professionisti e degli 
altri enti di diritto privato non tenuti all’iscrizione in albi, elenchi o registri professionali o nel registro delle imprese** 
è disponibile all'URL [INAD](https://domiciliodigitale.gov.it/).

Per maggiori informazioni circa l'adesione ed utilizzo della **Piattaforma Digitale Nazionale 
Dati per l’interoperabilità** si rimanda al sito della stessa disponibile all'URL [PDND interoperabilità](https://www.interop.pagopa.it/).

L'e-service erogato da AgID per la consultazione dell'**INAD** per il tramite della **Piattaforma Digitale Nazionale 
Dati per l’interoperabilità** è denominato [**INAD CONSULTAZIONE DD**](https://www.interop.pagopa.it/catalogo/2d97cffc-27cb-4705-a21d-9e1084aec9e3/).

## Verifica integrazione API estrazione dei domicili digitali

Le Pubbliche Amministrazioni interessate all'utilizzo dell'e-service **INAD CONSULTAZIONE DD** possono, per il tramite della **Piattaforma Digitale Nazionale 
Dati per l’interoperabilità** collaudo, verificare l'integrazione dei loro sistemi informatici con le stesse. 

Si precisa che l'URL del serve per effettuare la chiamata deve essere recuperato dall'OpenAPI associato all'e-serivce pubblicato sulla **Piattaforma Digitale Nazionale 
Dati per l’interoperabilità**.

A tal fine, si riporta nel file [datasetSample.csv](datasetSample.csv) un set di CF utili a verificare le risposte positive delle API estrazione dei domicili digitali



