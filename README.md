# C Grammar Modification , An ANTLR Project.
Our Tasks Was to : Modify Code Standars In C  
#### We Defined in regex the name formula for the names of : 
- ## Declarations : 
- [x] Structures  : (Std_Return_s)
- [x] Enumerations: (Std_Return_e)
- [x] Types
- [x] API Definitions (Functions)
- ## Global :
- [x] Struct      Variables
- [x] Union       Variables 
- [x] Enumeration Variables
- [x] Other       Variables
- ## Local 
- [x] Function    Parameters
- [x] Struct      Variables
- [x] Union       Variables
- [x] Enumeration Variables
- [x] Other       Variables

## Notes: 
- Grammar Rules Were specified in a JSON File **"myJSON.JSON"** which was parsed using JSON File parsing library in Java
- Included in our project files **"t.expr"** , a file that contains some test cases,at least one test case for each rule we specified
- The logic of overridden visitors can be found in **Replace.java** 
- The idea is that it compares the input (the programmer input) or in our case the test case , with the rules we have already defined in our JSON file , and if the input violates one of our rules , we print that violation as an error message containing the line and the type of violation
- :+1: This Project is done as a response to Compilers Course spring 2021 SFE coursework project, **Dr Marwa** and **Eng.Ahmed Bakr**
