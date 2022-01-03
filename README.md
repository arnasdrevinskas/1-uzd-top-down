Problema - Surasti blogąją versija ir atvaizduoti jį ekrane.

Analizė

Įvestis yra versijų skaičius ir blogoji versija, o išvestis pirmoji bloga versija. Skaičiai yra sveikieji dėl to naudosime int tipą. Duomenys/kintamieji,kurie bus naudojami:
	
	1. Įvestis: Versijų skaičius.
	2. Įvestis: Blogoji versija.
	3. Išvestis: Pirmoji bloga versija.

Formulės.
	
	1. Vidurys = (kaire + dešinė) / 2
	

Algoritmo konstravimas/projektavimas.
	
	1. int left = 1; Įvedama pati pirmiausia versija. (kairioji riba)
	2. int right = n; Įvedama pati paskutiniausia versija. (dešinioji riba)
	3. Pradedame paiešką, kad sumažintume diapazoną. Kadangi reikia ieškoti pirmosios 	netinkamos versijos.
	4. Kairė turi buti < dešinėj ribai, kitaip sprendinių nebūtų.
	5. Surandame pirmąją blogąją versiją.
	


