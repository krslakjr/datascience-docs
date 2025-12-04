# Mini Project and Presentation of Results

# Cilj projekta

Cilj završne radionice je da polaznici samostalno primijene kompletan Data Science proces na stvarnom datasetu. Kroz ovaj mini projekat polaznici će proći sve ključne faze: od odabira podataka, njihovog čišćenja i analize, preko izrade vizualizacija, do kreiranja jednostavnog modela mašinskog učenja i interpretacije rezultata. Završna aktivnost uključuje kratku prezentaciju projekta sa fokusom na zaključke i prikaz naučenih vještina.

# Odabir dataset-a

Polaznicima se nudi izbor nekoliko javno dostupnih datasetova prilagođenih njihovom nivou znanja. Predloženi datasetovi uključuju:

- Iris dataset – klasifikacija vrsta cvjetova prema dimenzijama latica i čašica
- Titanic dataset – predviđanje preživljavanja putnika na osnovu demografskih podataka
- Prodaja proizvoda – analiza kupovine tokom vremena i osnovne prognoze
- Podaci o vremenu – rad sa vremenskim serijama
- Online ankete ili ocjene – analiza ponašanja korisnika

Polaznik bira dataset prema interesima, uz preporuku da dataset nije prevelik, kako bi analiza bila izvodiva u ograničenom vremenu.

# Faze projekta

## 1. Učitavanje i pregled podataka

Prvi korak je učitavanje podataka u Python okruženju (Pandas) i osnovni pregled dataset-a:

- broj redova i kolona
- tipovi varijabli
- prisutnost praznih vrijednosti
- osnovna statistika (describe())

Ovaj korak služi da polaznici razumiju "koji su podaci u igri" i identifikuju eventualne probleme.

## 2. Čišćenje i priprema podataka

Drugi korak podrazumijeva:

- uklanjanje ili zamjenu nedostajućih vrijednosti
- pretvaranje tipova podataka (npr. datumi)
- kreiranje novih kolona (feature engineering) ako je potrebno
- filtriranje i selekciju relevantnih podataka

Cilj je dobiti "čist" dataset spreman za analizu.

## 3. Eksplorativna analiza podataka (EDA)

Eksplorativna analiza omogućava da se otkriju obrasci, odnosi i zanimljive pojave u podacima. Polaznici trebaju:

- kreirati osnovne grafove (line chart, bar chart, scatter plot)
- provjeriti raspodjelu varijabli
- analizirati korelacije između značajki
- opisati svoje nalaze kratkim tekstom

Ovime se razvija razumijevanje podataka i uvodi logika daljih koraka.

## 4. Primjena jednostavnog ML modela

U ovoj fazi polaznici biraju jedan jednostavan model mašinskog učenja, u skladu s tipom zadatka:

- Linear Regression – za predviđanje numeričkih vrijednosti
- Logistic Regression ili Decision Tree – za klasifikaciju
- KMeans – za grupisanje (unsupervised learning)

Polaznici:

- podijele podatke na train i test
- treniraju model
- ocjenjuju performanse (accuracy, RMSE, confusion matrix…)
- ukratko opisuju šta model “pokušava da nauči”

Cilj nije perfekcija modela, nego razumijevanje procesa.

## 5. Zaključci i interpretacija

Na osnovu analize i modeliranja, polaznici trebaju napisati kratke zaključke, na primjer:

- koji faktori najviše utiču na rezultat?
- kako podaci izgledaju nakon vizualizacije?
- da li je model uspješan i zašto?
- koji su mogući uzroci grešaka?

Fokus je na interpretaciji, ne samo na brojkama.

## 6. Prezentacija 

Za kraj, polaznici pripremaju mini prezentaciju svog rada (5–7 minuta). Preporučeni elementi prezentacije:

- Kratak opis odabranog dataset-a
- Najvažniji koraci čišćenja i pripreme
- Najbolje vizualizacije (2–3 grafikona)
- Model mašinskog učenja i objašnjenje njegovih performansi
- Glavni zaključci
- Šta bi unaprijedili u budućem radu

Prezentacija može biti urađena u PowerPointu, Google Slides ili direktno iz Jupyter Notebook-a.