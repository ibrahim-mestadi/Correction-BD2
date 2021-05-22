# Correction-BD2-2020

### q1 : Quelle déclaration est vrai lors de l'utilisation d'un curseur lors d'une boucle FOR : 
- [ ] vous devez explicitement récupérer les lignes dans une boucle de curseur FOR ;
- [ ] vous devez fermer explicitement le curseur avant la fin du programme ; 
- [x] vous n'ouvrez , ne récupère ou  ne fermez pas explicitement un curseur dans une boucle de curseur FOR ; 
- [ ] vous devez ouvrir explicitement le curseur avant la boucle cursor FOR ; 
### q2  : Vous devait supprimer le déclencheur de base de données Salary_Check. Quelle commande utilisé vous pour supprimer le déclencheur dans SQL*Plus.  
- [x] DROP TRIGGER Salary_Check ; 
- [ ] ------------------------; 
- [ ] ------------------------ ; 
* _**Astuce** (en génerale) : tout ce qui est créé par CREATE est détruit par DROP_ 
### q3 : qu'est-ce qui est Vrai pour une procédure stocké :
- [ ] Une procedure stockée est modifié par : ALTER PROCEDURE  ; 
- [x] une procédure stockée doit appartenir un schéma de base de données; 
- [x] une procédure stockée doit au moins avoir une instruction éxecutable dans le coprs de la procédure; 
- [ ] une procédure stockée utilise le mot clé DECLARE pour déclare les paramétres  ; 
- [x] Une procédure stockée est un bloc de code PL/SQL avec des paramétres stockée dans la spécifications de la procédure ; 
### q4 : soit le block suivant : 
``` sql
 FOR REC_EMP IN CUR_SAL
 LOOP
  EMP_ID (EMPLOYEE_ID) = REC_EMP.LASTNAME ;  
 END LOOP 
 CLOSE CUR_SAL ; 
 END ; 
```
- [ ] les conditions de términaison sont manquantes ;
- [ ] les affectations sont mal utilisé  ; 
- [x] le curseurs n'a pas besion d'être éxplicitement fermé ; 
- [ ] le curseurs doit être ouvert ; 
### q5 : choisit trois options vrais pour la propagation des erreurs? (choisis 3 ) 
- [x] une exception peut être levée à l'intérieur d'un Trigger  ;
- [ ] Toutes les exceptions doivent être déclaré dans la partie DECLARE  ; 
- [x] une exception peut se propager entre les appels de procédure ; 
- [ ] une exception levée à l'intérieur d'un sout block se propage au bloc parents même si traitéé localement  ;
- [x] L'usage de RAISE ne permet pas la propagation de l'exucution au block parents s'elle est déclarée localement ;  
### q6

