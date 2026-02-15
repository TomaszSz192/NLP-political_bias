# NLP-political_bias
Cel projektu
Celem projektu jest zbudowanie modelu NLP, który klasyfikuje teksty polityczne jako lewicowe, centrowe lub prawicowe.
Projekt pokazuje pełny pipeline przetwarzania języka naturalnego — od czyszczenia danych, przez wektoryzację, po trenowanie modeli ML.

Dane

Dane tekstowe zawierają fragmenty wypowiedzi politycznych lub artykułów.
Każdy tekst posiada etykietę określającą jego orientację polityczną.

Przykładowe cechy danych:
długość tekstów jest zróżnicowana,
klasy mogą być niezbalansowane,
język jest nieformalny i zawiera kolokwializmy.

Pipeline NLP

Czyszczenie tekstu
usuwanie znaków specjalnych,
tokenizacja,
usuwanie stopwords,
stemming/lemmatyzacja.

Wektoryzacja
TF‑IDF (unigramy + bigramy).

Modele ML

Logistic Regression,
SVM,
Random Forest,
Naive Bayes

Ewaluacja

Accuracy
Precision, Recall, F1
Confusion Matrix
