# BootAnimationReplacer

Un semplice script per sostituire l'animazione di avvio (`bootanimation.zip`) su dispositivi Android. Progettato per sostituire il file in `system/product/media`.

## 📦 Caratteristiche

- Compatibile con la maggior parte dei dispositivi Android
- Supporta installazione tramite **Magisk** o **KernelSU**

## 🛠 Requisiti

- Dispositivo Android con permessi di root (Magisk o KernelSU)
- Un file `bootanimation.zip` personalizzato

## 🚀 Installazione

1. Scarica il progetto
2. Decomprimi lo zip
3. Copia il tuo `bootanimation.zip` nella cartella del progetto `system/product/media`
   - ⚠️ Per dispositivi che utilizzano `system/media`, rimuovi la cartella `product` e posiziona direttamente il file in `system/media`
4. Comprimi nuovamente tutto in formato ZIP
5. Installa tramite Magisk o KernelSU

## ⚠️ Avvertenze
- **L'autore non si ritiene responsabile** per eventuali danni a dispositivi o perdita di dati dovuti all'uso di questo script
