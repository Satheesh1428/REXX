# REXX

first statement of exec statement is /*rexx*/ 	

**How to find system libraries :**
   TSO ISRDDN  -- IT will display all system libraries in that we need go to SYSPROC . Under SYSPROC what ever libraries are theere out of  any one of them   
   we need to copy our REXX code,  so that we/anyone can execute our REXX program 
   GT0734.ISPF.DATASETS -- SYSTEM LIBRARY 
   TSO PROF -- to find your profile 
**Once you write rexx code there are multiple ways execute REXX program**

**Explicit execution**

**Implicit execution:**

**From ISPF:**
  run TSO PGMNAME   post you place your code in system library
  EXEC also you can execute to test yourself 

**REXX special varaibles :**
RC , SIGL , RETURN , 

**REXX importent syntaxes :**

SAY , PULL/ARG , PARSE WITH ARG, 

**Conditions:**
if then else / when you have multiple condition with in if then else , we you DO and END statement.
select - when- otherwise -end

**Loops:**
DO  END / DO FOREVER loops

  Options: LEAVE/ITERATE
  
**Funtions:**
REXX arithamatic : ABS, MAX, MIN, TRUNC, RANDOM, COMPARE, DATATYPE
REXX cobnversion functions: B2X, X2B, X2C, C2X, D2C, 


**How to debug your REXX code**
We to code below TRACE commands in our REXX code for debugg
TRACE I ( Trace intermediate)
TRACE R ( Trace ressults)






