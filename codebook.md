# CODEBOOK
## Describing variables used in the final tidy data set of cemetery interments in Pinellas County Florida
1. **Surname** | *Class:Character* - The surname of the person interred. 
2. **First_Name** | *Class:Character* - The first name of the person interred.
3. **Middle_Name_MI** | *Class:Character* - The full middle name(s), or just the initial(s) of the person interred.  This could also include a maiden name.
4. **Honorific** | *Class:Character* - Title such as "Dr.","Rabbi", or "Rev." of the person interred. Abbreviated or full text.
5. **Suffix1** | *Class:Character* - Ordinate designation(e.g. "Jr.", "Sr.","II","IV",etcetera) of the person interred.
6. **Suffix2** | *Class:Character* - Overflow in the case where person interred had more than one suffix.
7. **Born_Year** | *Class:Numeric* - Year person interred was born. Four digit numeric.
8. **Born_Month** | *Class:Numeric* - Month person interred was born. Two digit numeric. Use leading zero for months below 10.
9. **Born_Day** | *Class:Numeric* - Day person interred was born. Two digit numeric. Use leading zero for days below 10.
10. **Died_Year** | *Class:Numeric* - Year person interred died. Four digit numeric.
11. **Died_Month** | *Class:Numeric* - Month person interred died. Two digit numeric. Use leading zero for months below 10.
12. **Died_Day** | *Class:Numeric* - Day person interred died. Two digit numeric. Use leading zero for days below 10.
13. **Born** | *Class:Date* - Full date represented as YYYY/MM/DD person interred was born.  **NOTE this is not available for a large number of observations.  Born_Year is the highest detail known for these records.
14. **Died** | *Class:Date* - Full date represented as YYYY/MM/DD person interred died. **NOTE this is not available for a large number of observations.  Died_Year is the highest detail known for these records.
15. **Inscription** | *Class:Character* - Text written on headstone of person interred.
16. **Cemetery** | *Class:Character* - Name of cemetery in which person interred was interred.

