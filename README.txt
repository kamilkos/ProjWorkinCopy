Projekt:
	Falki dla leniwych - Detekcja QRSow;
	
	
TODO:
	Wczytywacz plików SignalStorage(simple Event window); done
	Ustawiacz opcji analizy(simple Event window  or  cluster Pane in mainApp?); done
	Analizator (); 0.9 done
	MainApp (); 0.9 done
	Podglądacz wyników (simple Event window); done
	
	
Wczytywacz plików:
	Czytanie plików
	-możliwa zamiana separatorów wybór kolumn w txt/csv OK
	-możliwe wycięcie fragmentu z wczytanego pliku i zapisanie osobno OK
	-sygnał syntetyczny OK
	
	Reads:
		-.txt
		-.csv
		-.hea(physionet) OK
	
	
SignalStorage:	OK
	Stores:
		-signals
			-name
			-waveform
			-comment

			
Analizator:
	Analiza wybranego sygnału za pomocą wybranych (rodzin)falek i poziomów dekompozycji
		-każdy zapisywany jako sygnał OK
	
//Jeżeli zostanie czasu:
	Poszukiwanie w detalach/aproksymacji, w zgrubnie wyznaczonych miejscach:
		-minimów		-maksimów		-Miejsc zerowych
		