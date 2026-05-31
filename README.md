# Klassificering av ansiktsuttryck med CNN

Examensuppgift i kursen Deep Learning.

Det här projektet bygger ett neuralt nätverk (CNN) som klassificerar
ansiktsuttryck i sju kategorier: angry, disgust, fear, happy, neutral,
sad och surprise. Datan kommer från FER-2013 och består av gråskalebilder
i storleken 48x48 pixlar.

## Innehåll

- `ansiktsuttryck_klassificering.ipynb` – notebook med all kod, analys och resultat
- `best_model.keras` – den tränade modellen

## Resultat

Modellen får runt 52% rätt på testdatan. Bäst klarar den happy och surprise,
sämst fear och disgust. Hela analysen finns i notebooken.

## Köra projektet

Datan (mappen `data/`) ingår inte i repot eftersom den är för stor.
Den laddas ner separat från FER-2013 och läggs i en `data/`-mapp med
undermapparna `train/` och `test/`.