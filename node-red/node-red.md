# Node Red Dashboard

- **Cieľ**: zobrazovať dáta z mobilných senzorov, ktoré sú posielané cez MQTT

# Schéma zapojenia
Exportovaný json tohto zapojenia je dostupný v priečinku node-red pod názvom node-red-code.json
![Schéma](Snímka.PNG)

# Princíp fungovania
Čítame vstupné dáta z troch kanálov a zobrazujeme ich na dashboarde. 
Pri intenzite svetla dáta filtrujeme a hlásime, či je intenzita svetla vyskoá alebo nízka.
 
  
  # Výsledný dashboard
  ![Dashboard](Snímka2.PNG)


