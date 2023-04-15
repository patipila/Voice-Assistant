#	Wirtualny asystent głosowy
Nasz wirtualny asystent może przyjąć różne imiona. Obecnie Jaca jest komputerowym asystentem napisanym w Python 3.10 na system Windows.  Bot potrafi wykonać podstawowe czynności np. otwieranie stron, sprawdzanie pogody, tworzenie krótkich notatek z wikipedii.

# Wymagania
Upewnij się, że masz Pythona 3.10.

 

     pip install SpeechRecognition
	 pip install pyttsx3
     pip install pyjokes
     pip install playsound
     pip install wikipedia
     pip install pyowm
     pip install pyaudio
Jeżeli wystąpi problem z  zainstalowaniem pyaudio należy użyć w terminalu następujących komend:

    pip install pipwin
    pipwin install pyaudio

Ponadto należy pobrać z załączonego folderu:

 - assistant_on.mp3 
 - assistant_off.mp3 
 - ludzik.png 
 - ludzik.ico
 - ustawienia.png
 - mikro.png

  # Uruchomienie

 Program należy uruchomić poprzez podwójne kliknięcie na plik:

     Asystent.py

Po kliknięciu na mikrofon odtworzony zostanie krótki dźwięk. Gdy się on zakończy należy powiedzieć komendę, którą asystent ma wykonać. 

Może pojawić się problem ze ścieżką do odtworzenia dźwięku assistant_on.mp3. Należy wtedy zmienić ścieżkę względną na bezwzględną.
 

    playsound('/path/to/a/sound/file/you/want/to/play.mp3')
   
Uwaga: pamiętaj również o szybkim i bezpiecznym połączeniu internetowym, aby uruchomić ten program. Ponieważ używa on rozpoznawania mowy Google do zrozumienia poleceń.

   # Wyłączanie
   Program będzie inicjowany do momentu przetworzenia słów:
•	Goodbye
•	Ok bye
•	Stop

# Funkcje

Poszczególne funkcje są wykonywane poprzez wypowiedzenie odpowiednich komend.

•	Sprawdzenie prognozy pogody w wybranym mieście:

    weather nazwa_miasta

•	Otwieranie stron internetowych takich jak: youtube, netflix, primevideo, google, gmail i wikipedia:

 

    open nazwa_strony

 
•	Podanie daty oraz godziny:

    date

•	Powiedzenie  żartu:

    joke

•	Podanie  wiadomości oraz aktualnych danych covidowych:

    covid

•	Podanie ogólnych wiadomości:

    news

•	Utworzenie notatek odnośnie wybranych haseł w Wikipedii:

    wyszukiwana_fraza wikipedia

 # Inspiracje 
Program używa pliki dźwiękowe pobrane z aplikacji ITunes.  Ponadto korzystałyśmy z już powstałych asystentów np. https://github.com/rituraj97/RUBY-Desktop-Assistant-GUI oraz https://github.com/adammaly004/Virtual_Assistant
 



> Written with [StackEdit](https://stackedit.io/).



