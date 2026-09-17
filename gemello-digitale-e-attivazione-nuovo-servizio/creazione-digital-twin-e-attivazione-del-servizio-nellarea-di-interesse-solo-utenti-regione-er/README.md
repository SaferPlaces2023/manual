---
cover: ../../.gitbook/assets/Asset 10.jpg
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: hero
    mask: none
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# 💻 Creazione Digital Twin e attivazione del servizio nell'area di interesse - SOLO UTENTI REGIONE ER

Cliccando sull'icona "_Create a project_", si avvia l'interfaccia guidata che aiuta ad attivare il servizio e a generare il Digital Twin per l'area designata di interesse.

<figure><img src="../../.gitbook/assets/image (77).png" alt=""><figcaption><p>Create a new project</p></figcaption></figure>

Per gli utenti della Protezione Civile della Regione Emilia-Romagna abilitati, la procedura di attivazione del servizio Saferplaces segue un wizard semplificato. Questo richiede soltanto la definizione dell'area di interesse e acquisisce automaticamente tutti i layer necessari alla generazione del Digital Twin e all'attivazione del servizio.

Nell'header in alto di fianco al logo di SaferPlaces è presenta una casella di ricerca che può essere utilizzata per cercare e zoomare su:

* località e comuni
* indirizzi  - icona globo
* bacini idrografici - icona layer

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Sono state sviluppate 2 diverse modalità di attivazione della piattaforma SaferPlaces per una specifica area di interesse (AOI).\
La prima modalità attraverso la definizione di un rettangolo, selezionando SELECT BY AREA

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Select by Area</p></figcaption></figure>

La seconda modalità invece mediante la selezione di uno o più bacini idrografici

<figure><img src="../../.gitbook/assets/select_bacini.png" alt=""><figcaption><p>Select By Basins</p></figcaption></figure>

L'utente deve definire un'area di attivazione scegliendo una delle due modalità:

* Selezione di un area rettangolare - cliccando sul pulsante SELECT BY AREA
* Selezionare uno o più bacini idrografici - cliccando sul pulsante SELECT BY BASIN

Sul pannello di destra sono elencati i layers che possono essere visualizzati anche nella fase di attivazione dell'AOI.

Alcuni layers fanno riferimento a servizi GIS REST della Regione Emilia-Romagna.

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

Una volta definita l'area (Area rettangolare o bacino idrografico) , il Wizard procede automaticamente a scaricare i layer di input necessari per attivare il nuovo progetto:



[step-1-dtm-rer-raster-geotiff.md](step-1-dtm-rer-raster-geotiff.md "mention") Modello digitale del terreno&#x20;

[step-2-edifici-rer-vettoriale-shapefile.md](step-2-edifici-rer-vettoriale-shapefile.md "mention")&#x20;

[step-3-tasso-di-infiltrazione-rer-raster-geotiff.md](step-3-tasso-di-infiltrazione-rer-raster-geotiff.md "mention")

[step-4-litologia-rer-raster-geotiff.md](step-4-litologia-rer-raster-geotiff.md "mention")

[step-5-layer-geospaziali-aggiuntivi-raster-e-vettoriali-rest-service.md](step-5-layer-geospaziali-aggiuntivi-raster-e-vettoriali-rest-service.md "mention")

[step-6-crea-e-finalizza-il-progetto-rer.md](step-6-crea-e-finalizza-il-progetto-rer.md "mention")



&#x20;

### Video Esempio di creazione di gemello digitale tramite "Select by area"

{% file src="../../.gitbook/assets/Video_select_by_area (2).mp4" %}

### Video Esempio di creazione di gemello digitale tramite "Select by basin"

{% file src="../../.gitbook/assets/Video_select_by_basin (2).mp4" %}

