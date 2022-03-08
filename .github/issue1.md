---
title: Exercice 1 : Diagramme des UC en plantUML ({{ date | date('dddd, MMMM Do') }})
---
En vous inspirant du code suivant (pour ne pas démarrer à vide), réalisez un diagramme des UC correspondant au sujet.
```plantuml
@startuml

usecase r as "Participer \n à un chantier"
usecase d as "Déclarer une \n demande de stage"

actor Employés
actor Entreprise 

'Pour aligner les 2 acteurs :
r -[hidden]-> d

Employés -> r
Entreprise -> d

@enduml
```