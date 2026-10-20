# face-detection
Progetto di face detection su immagini, partendo da una combinazione di dataset e mantenendo basso il consumo di risorse.

Il codice è ampiamente commentato.
Il modello è implementato utilizzando
- estrazione delle feature con HOG (Histogram of Oriented Gradients)
- allenare un classificatore con Sklearn
- produrre una Sliding Window + Image Pyramid per rilevare volti in immagini di dimensioni arbitrarie
