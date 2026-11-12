# ANN Regression - Car Price Prediction

Proiect de **machine learning** pentru estimarea prețului mașinilor second-hand folosind o **rețea neuronală artificială (ANN)** și TensorFlow/Keras.

## Descriere

Notebook-ul `ANN_Regression.ipynb`:

- încarcă datele din `Car_prices_2.csv`;
- normalizează variabilele;
- separă datele în seturi de antrenare, validare și test;
- construiește și antrenează o rețea neuronală pentru regresie;
- evaluează modelul folosind coeficientul de determinare `R²`;
- generează grafice pentru loss, `R²` și predicțiile finale.

## Variabile

Modelul folosește următoarele caracteristici:

- `Age` - vârsta mașinii, în luni;
- `KM` - numărul de kilometri;
- `Weight` - greutatea;
- `HP` - puterea motorului;
- `MetColor` - indică dacă mașina are culoare metalizată;
- `CC` - capacitatea cilindrică;
- `Doors` - numărul de uși.

Variabila prezisă este `Price`, prețul mașinii în dolari.


## Tehnologii

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

