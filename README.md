# SmartHome
- # Piwnica
  - ## Hydrofor
    - ### Stany pompy

        Odczyt stanów pompy:

        * Zasilanie
        * Praca
        * Błąd

        "Zasilanie" oraz "Błąd" przy pomocy przekaźników [PK-1P 230 V](https://www.fif.com.pl/pl/przekazniki-elektromagnetyczne/306-przekaznik-elektromagnetyczny-pk-1p-230-v.html),
        a "Praca" przy pomocy styku pomocniczego **22DILE**

    - ### Reset pompy
    
      - #### Automatyczny

        Zdalny reset logiki/timera przy pomocy [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/)

      - #### Manualny

        Przełącznik **M22-WRK** podłączony do **Shelly 1**

   - ## Zimna woda
      - ### Pomiar przepływu wody
      
        Pomiar cieczy z wykorystaniem czujnika [YF-B7](https://www.seeedstudio.com/Water-Flow-Sensor-YF-B7-p-2884.html).
        
        Umiejscowione za wyjściem z licznkika wody (Pomiar żużycia wody państwowej) oraz za zbiornikiem wody ze studni
        
      - ### Zawór trójdrożny

        Połączenie wody państwowej i wody ze studni przełączanie manualnie lub automatycznie na podstawie danych z hydroforu.
        
        Można wykorzystać zawór **IB-Q20-3** lub **IB-Q25-3**
        
        [Instrukcja](http://www.download.insbud.net/pl/manuals/pl_ib-qxx-3.pdf)
- # Licznik energii
  Pomiar energii zużytej, oddanej i autokonsumpcji
  
  Czujnik [Shelly 3EM](https://shelly.cloud/products/shelly-3em-smart-home-automation-energy-meter/)
