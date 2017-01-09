# stack-computer

  * Zásobníkový počítač má paměť, zásobník, vstup a výstup.
  * Do paměti lze ukládat jako hodnoty celá čísla, paměť je adresována přirozenými čísly.
  * Na zásobník lze ukládat adresy i hodnoty.
  * Vstup a výstup jsou posloupnosti celých čísel - vstup je posloupnost dosud nepřečtených dat, výstup posloupnost dosud zapsaných dat.
  * Program pro zásobníkový počítač je posloupnost instrukcí ukončená značkou EOP. Instrukce jsou ukončeny středníkem: 
  * EOP ... tečka za programem
  
  I;P ... instrukce I za níž následuje program P
  
  n:P ... návěští n, kterým je označen program P

## použití

maude stackComputer.maude
> red in AUTOMAT : run( TA 10 ; TV 15 ; ST ; RD ; TA 10 ; DR ; AD ; JU 5 ; WR ; RD ; 5 : WR ; EOP , 10 13) .
