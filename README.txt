Projekt:
	Falki dla leniwych - Detekcja QRSow;
	
	
TODO:
	Wczytywacz plik�w do SignalStorage(simple Event window);
	Ustawiacz opcji analizy(simple Event window  or  cluster Pane in mainApp?);
	Analizator ();
	MainApp ();
	Podgl�dacz wynik�w (simple Event window);
	
	
Wczytywacz plik�w:
	Czytanie plik�w:
	-mo�liwa zamiana separator�w, wyb�r kolumn w txt/csv
	-mo�liwe wyci�cie fragmentu z wczytanego pliku i zapisanie osobno
	
	
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
	Analiza wybranego sygna�u za pomoc� wybranych (rodzin)falek i poziom�w dekompozycji
		-ka�dy zapisywany jako sygna�
	
	Poszukiwanie w detalach/aproksymacji, w zgrubnie wyznaczonych miejscach:
		-minim�w
		-maksim�w
		-Miejsc zerowych
		