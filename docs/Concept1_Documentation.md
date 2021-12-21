  # Concept1  <br> 
     
  ```plantuml 
  @startuml 
  class Concept1 
  { 
  string : property11 
  string : property12 
  string : property13 
  } 
  BaseConcept <|-- Concept1 
  INamedConcept <|.. Concept1 
  ScopeProvider <|.. Concept1 
  @enduml 
  ``` 
     
  This is the documentation for concept1. 
  ____________________________________________
  You can write here text in a basic markdown syntax. 
     
  **Extends:** BaseConcept  <br> 
     
  **Implements:**  <br> 
  INamedConcept  <br> ScopeProvider  <br> 
     
  **Properties:**  <br> 
  property11 : string  <br> property12 : string  <br> property13 : string  <br> 
     
  **Children:**  <br> 
  child11 : [Concept2](Concept2_Documentation.md )  <br> child12 : [Concept2](Concept2_Documentation.md )  <br> child13 : [Concept3](Concept3_Documentation.md )  <br> 
     
  **Editor:**  <br> 
  concept1 ( property11 : {property11} , property12 : {property12} , property13 : {property13} , NEWLINE <br> child11 : %child11% , child13 : %child13% , child12 ( (child12)* ) ) 
