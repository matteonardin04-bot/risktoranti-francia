# Cos'è un Cloropleth?

## A cosa serve
- Visualizzare distribuzioni geograche di dati statistici
- Confrontare aree sullo stesso indicatore (densità, tasso, percentuale, . . . )
- Identicare pattern spaziali: cluster, gradienti, anomalie

## Buone pratiche
- Usa palette sequenziali per dati ordinati (es. densità di popolazione)
- Usa palette divergenti per dati con un punto neutro (es. variazione percentuale)
- Normalizza per area o popolazione, altrimenti la mappa mostra solo dove vivono le persone
- Indica sempre unità di misura e fonte dei dati

## Librerie principali in R

#Tabella
| Libreria       | Scopo         |
| -------------- | ------------- |
| sf             | geometrie vettoriali (shapele, GeoJSON, . . . ) |
| ggplot2        | visualizzazione, mappe via geom_sf() |
| tmap           | mappe tematiche, statiche e interattive |
| leaflet        | mappe interattive in HTML |

## Link

