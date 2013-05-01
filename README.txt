Projekt:
	Falki dla leniwych - Detekcja QRSow;
	
	
TODO:
	Wczytywacz plików do SignalStorage(simple Event window);
	Ustawiacz opcji analizy(simple Event window  or  cluster Pane in mainApp?);
	Analizator ();
	MainApp ();
	Podgl¹dacz wyników (simple Event window);
	
	
Wczytywacz plików:
	Czytanie plików:
	-mo¿liwa zamiana separatorów, wybór kolumn w txt/csv
	-mo¿liwe wyciêcie fragmentu z wczytanego pliku i zapisanie osobno
	
	
SignalStorage:
	Reads:
		-.txt
		-.csv
		-.hea(physionet)
	
	Stores:
		-signals
			-MainReadedSignal
			-ChildSignals(after analysis)

			
Analizator 
	Analiza wybranego sygna³u za pomoc¹ wybranych (rodzin)falek i poziomów dekompozycji
		-ka¿dy zapisywany jako sygna³
	
	Poszukiwanie w detalach/aproksymacji, w zgrubnie wyznaczonych miejscach:
		-minimów
		-maksimów
		-Miejsc zerowych
		