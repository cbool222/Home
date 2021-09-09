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
   - ## WiFi
   
    Access Point [MikroTik RB760iGS](https://mikrotik.com/product/hex_s) obok inwertera 
    
   - ## Skrzynka Rozdzielcza: Remastered
   
    Komponent | Przeznaczenie | Sklep | Ilość 
    ------------ | ------------- | ------------- | -------------
    Skrzynka Rozdzielcza 600x500 | --- | [Allegro](https://allegro.pl/oferta/skrzynka-szafa-obudowa-abs-plastikowa-600x500x220-9786926675) | 1
    Stycznik DILM 15-10 7.5kW | Zdalne wyłączanie płyty indukcyjnej | [plcs.net.pl](https://www.plcs.net.pl/index.php/katalog-automatyki/styczniki/styczniki-eaton/styczniki-dil-m/dilm15xx-stycznik-dilm-15-75-kw.html) | 1
    Shelly 1 | Zdalne wyłączanie płyty indukcyjnej | [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/) | 1
    MEAN WELL MDR-20-5 | Zasilanie 5V | [Allegro](https://allegro.pl/oferta/zasilacz-na-szyne-din-5v-3a-15w-mean-well-mdr-20-5-11017683821) | 1
    
    


    
   
   
- # Licznik energii
  Pomiar energii zużytej, oddanej i autokonsumpcji
  
  Czujnik [Shelly 3EM](https://shelly.cloud/products/shelly-3em-smart-home-automation-energy-meter/)
