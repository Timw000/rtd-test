# Arkitektur
FCC Internetkontor är byggt i två delar:
- Ett frontend i Vue 3 som är det grafiska interface som slutanvändaren använder. Detta kommunicerar med servern för att nå försäkringsdata i Lumera.
- Ett backend i Spring Boot (Java) som kommunicerar med Lumera och innehåller den mappningslogik som behövs för att data i Lumera ska visas i FCC Internetkontor på ett bra sätt.

## Frontend
