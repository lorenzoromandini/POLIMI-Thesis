# Detecting signals of deforestation and desertification using vegetation indices: Evidence on Myanmar, Mozambique and Ethiopia use cases

MSc Thesis in Computer Science and Engineering - Politecnico di Milano

**Graduated:** March 2026

Author: Lorenzo Romandini (ID: 10939723)

Advisor: Prof. Chiara Francalanci

---

## Notice

Due to an NDA (Non-Disclosure Agreement) signed with a third party, the full thesis content cannot be publicly disclosed. This repository serves as a local container for the thesis files and demonstrates the work completed for the MSc degree to potential readers or employers.

---

## Brief Description

This thesis explores the detectability of environmental degradation (deforestation and desertification) using coarse-resolution satellite vegetation indices. Using MODIS MOD09A1 data (NDVI, SAVI, NDMI, NDWI) aggregated to geohash-based spatial units, the study applies Random Forest models as statistical probes to assess whether vegetation index time series retain separable signals associated with land degradation processes in Myanmar (deforestation), Mozambique, and Ethiopia (desertification) from 2018 to 2024.

---

## Abstract

Environmental degradation processes such as deforestation and desertification pose significant challenges for monitoring at regional and global scales. Remote sensing provides continuous observations of vegetation dynamics; however, it remains unclear whether coarse-resolution vegetation indices retain statistically observable signals of land degradation once data are spatially aggregated. This thesis investigates whether vegetation indices derived from MODIS MOD09A1 surface reflectance — NDVI, SAVI, NDMI, and NDWI — exhibit statistically separable structure compatible with deforestation in Myanmar and desertification-related dynamics in Mozambique and Ethiopia during the period 2018--2024.

The study adopts a descriptive analytical framework in which machine learning models are used as probes of statistical separability rather than as predictive tools. Vegetation-index time series are aggregated to geohash-based spatial units and analysed using Random Forest models, with reference datasets describing stand-replacement forest loss and land productivity dynamics providing proxy supervisory signals.

Results indicate that aggregated vegetation indices retain clear separable signals for abrupt disturbances such as deforestation, whereas gradual degradation processes associated with desertification exhibit weaker separability. This contrast reflects process-dependent observability, whereby low-amplitude vegetation changes become attenuated by spatial aggregation, environmental variability, and proxy semantics. Overall, the study highlights both the potential and structural limitations of coarse-resolution vegetation indices for assessing land degradation and emphasises the importance of interpreting remote sensing analyses in relation to observation scale and representational constraints.

**Keywords:** land degradation, remote sensing, vegetation indices, deforestation, desertification, spatial aggregation.

---

## Abstract (italiano)

Processi di degrado ambientale quali deforestazione e desertificazione rappresentano una sfida significativa per il monitoraggio su scala regionale e globale. Il telerilevamento satellitare consente l'osservazione continua delle dinamiche della vegetazione; tuttavia, rimane aperta la questione se gli indici di vegetazione a risoluzione spaziale grossolana conservino segnali statisticamente osservabili del degrado del territorio una volta sottoposti ad aggregazione spaziale. Questa tesi analizza se gli indici di vegetazione derivati dalla riflettanza superficiale MODIS MOD09A1 — NDVI, SAVI, NDMI e NDWI — presentino una struttura statisticamente separabile compatibile con fenomeni di deforestazione in Myanmar e con dinamiche di desertificazione in Mozambico ed Etiopia nel periodo 2018--2024.

Lo studio adotta un approccio analitico descrittivo nel quale i modelli di apprendimento automatico sono impiegati come strumenti di analisi della separabilità statistica piuttosto che come sistemi predittivi. Le serie temporali degli indici di vegetazione vengono aggregate in unità spaziali basate su geohash e analizzate mediante modelli Random Forest, utilizzando dataset di riferimento relativi alla perdita di copertura forestale e alle dinamiche di produttività del suolo come segnali supervisivi di tipo proxy.

I risultati evidenziano che gli indici di vegetazione aggregati mantengono segnali separabili chiari nel caso di disturbi improvvisi quali la deforestazione, mentre i processi di degrado graduale associati alla desertificazione mostrano livelli di separabilità più deboli. Tale contrasto riflette una osservabilità dipendente dal processo, in cui variazioni della vegetazione a bassa ampiezza risultano attenuate dall'aggregazione spaziale, dalla variabilità ambientale e dalla semantica dei proxy utilizzati. Nel complesso, il lavoro mette in luce sia il potenziale sia i limiti strutturali degli indici di vegetazione a risoluzione grossolana per l'analisi del degrado ambientale e sottolinea l'importanza di interpretare i risultati del telerilevamento in relazione alla scala di osservazione e ai vincoli rappresentazionali.

**Parole chiave:** degrado del suolo, telerilevamento, indici di vegetazione, deforestazione, desertificazione, aggregazione spaziale.
