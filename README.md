**Telia 2024 Andmeteaduse Praktika Kodutöö**


Klientide käitumise ennustamine ja muudatusettepanekud nende lahkumise vältimiseks.
See projekt keskendub klientide käitumise ennustamisele, eesmärgiga töötada välja strateegiad nende säilitamiseks. 
Allpool on kirjeldatud projekti põhietapid ja tegevused:

1.Andmete töötlemine
	•	Andmete laadimine
	•	Kasutatakse pandas teeki andmete laadimiseks CSV failist
	•	Puuduvate väärtuste ja andmetüüpide kontroll
	•	Puuduvate väärtuste tuvastamine ja käsitlemine
	•	TotalCharges veeru teisendamine numbriliseks ja puuduvate väärtuste asendamine mediaaniga
	•	Kategooriliste tunnuste töötlemine
	•	Kategooriliste tunnuste one-hot kodeerimine

2.Uuriv andmeanalüüs
		Andmete visualiseerimine
	•	Graafikute loomine, et uurida Churn, tenure, MonthlyCharges, ja TotalCharges jaotusi
		Demograafiliste tunnuste analüüs
	•	Klientide soojaotuse ja lahkumise mõõtmise visualiseerimine

3.Tunnusinseneeria ja andmete ettevalmistus
	•	Tunnusinseneeria
	•	Oluliste tunnuste väljaselgitamine ja ettevalmistus mudeli treenimiseks
	•	Treening- ja testimiskomplektide jaotamine
	•	Andmete jagamine treening- ja testimiskomplektideks

4.Mudeli valimine ja treenimine
	•	Mudeli treenimine
	•	Kasutatakse RandomForestClassifier mudelit esialgseks treenimiseks.
	•	Mudeli hindamine
	•	Täpsuse, klassifikatsiooniaruande ja segadusmaatriksi arvutamine.

5.Mudeli tuunimine ja optimeerimine
	•	Mudeli tuunimine
	•	Parameetrite, nagu n_estimators ja max_depth, optimeerimine
	•	Ansambli mudeli kasutamine
	•	Erinevate mudelite kombinatsioonide proovimine, nagu logistiline regressioon, random forest ja gradient boosting

6.Tulemuste raporteerimine
	•	Mudeli lõplik hindamine
	•	Kasutades XGBoost mudelit, mis on osutunud efektiivseks keeruliste mustrite tuvastamisel
	•	Tähtsate tunnuste väljaselgitamine
	•	Tunnuste tähtsuse analüüsimine ja visualiseerimine
 
Kokkuvõte
	•	Projekti kokkuvõtte ja järelduste esitamine, pakkudes insight'e kliendi lahkumise ennustamise kohta ja ettepanekuid klientide hoidmise strateegiateks



Tänud lugemast!
