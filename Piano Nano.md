# Piano Nano

- **Cieľ**: ovládať aspoň 4 klávesy (C, D, E, F)
- **Komponenty**: 4x **funkčné** spínače, reproduktor, 4x rezistor (aspoň 100Ω)

# Schéma zapojenia
![Zapojenie](klavir-wiring.png)

# Princíp fungovania
Piny, ktoré dostávajú vstup od tlačidla, dostávajú hodtotu HIGH (1). Po stlačení tlačidla sa však obvod uzemní a na pin prichádza hotnota LOW. Preto sledujeme hodnoty LOW a hráme požadovaný tón, kým je tlačidlo stlačené.
 ```
 while(digitalRead(C) == LOW)
  {
    tone(Buzz,T_C);
  }
  ```
  
  # Naše zapojenie
  (Je tam pár káblov navyše z predchádzajúceho projektu)
  
  <img src="zapojenie1.png" width=46%> <img src="zapojenie2.png" width=46%>
  ![obrázok](https://user-images.githubusercontent.com/84372947/221436431-714d1e5c-9a79-408e-95b4-7b5fec3f94ba.png)

