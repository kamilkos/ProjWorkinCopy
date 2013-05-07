Projekt:
	Falki dla leniwych - Detekcja QRSow;
	
	
TODO:
	Wczytywacz plików SignalStorage(simple Event window);
	Ustawiacz opcji analizy(simple Event window  or  cluster Pane in mainApp?);
	Analizator ();
	MainApp ();
	Podglądacz wyników (simple Event window);
	
	
Wczytywacz plików:
	Czytanie plików
	-możliwa zamiana separatorów wybór kolumn w txt/csv
	-możliwe wycięcie fragmentu z wczytanego pliku i zapisanie osobno
	
	Reads:
		-.txt
		-.csv
		-.hea(physionet)
	
	
SignalStorage:	
	Stores:
		-signals
			-name
			-waveform
			-comment

			
Analizator:
	Analiza wybranego sygnału za pomocą wybranych (rodzin)falek i poziomów dekompozycji
		-każdy zapisywany jako sygnał
	
//Jeżeli zostanie czasu:
	Poszukiwanie w detalach/aproksymacji, w zgrubnie wyznaczonych miejscach:
		-minimów		-maksimów		-Miejsc zerowych
		