SUSTAV ZA PREPOZNAVANJE LICA KORISTEĆI CLIP I FAISS ZA SKALABILNU REAL-TIME IDENTIFIKACIJU

Završni rad Autor: Antonio Labinjan

Mentor: doc. dr. sc. Nikola Tanković

Komentor: doc. dr. sc. Ivan Lorencin

Sveučilište Jurja Dobrile u Puli, Fakultet informatike

Sažetak

Prepoznavanje lica sve se češće primjenjuje u industrijama poput obrazovanja, sigurnosti i personaliziranih usluga. Ovaj rad predstavlja sustav za prepoznavanje lica koji koristi mogućnosti modela CLIP za generiranje vektorskih reprezentacija. CLIP, model treniran na multimodalnim podacima poput slika i videozapisa, stvara visokodimenzionalne značajke koje se pohranjuju u vektorsku bazu podataka za daljnje upite. Sustav je dizajniran za preciznu identifikaciju u stvarnom vremenu, s potencijalnim primjenama u praćenju prisutnosti i sigurnosnim provjerama. Konkretni primjeri uporabe uključuju evidenciju dolazaka na događaje, implementaciju naprednih sigurnosnih sustava i druge slične scenarije. 

Proces uključuje kodiranje poznatih lica u visokodimenzionalne vektore, njihovo indeksiranje pomoću FAISS vektorskog indeksa te usporedbu s nepoznatim slikama na temelju kosinusne sličnosti \cite{cosine}. Eksperimentalni rezultati pokazuju visoku točnost \cite{google_ml_accuracy, sklearn_metrics} veću od 90\% te učinkovitu izvedbu čak i na skupovima podataka s velikim brojem zapisa.
