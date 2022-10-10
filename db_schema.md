# Database schema

1. Collection name: Auth
  - Fields:
    * Username - String (Required)
    * Password - String (Required)

2. Collection name: Player
  - Fields:
    * Name - String (Required)
    * Pokemon - Array<Document>
      * Name - String (Required)
      * ID - Integer (Required)
      * Types - Array<Object<String>>
      * Stats - Array<Object>
        1. Stat - Object
	2. Base stat - Integer
      * Moves - Array<Object> 

