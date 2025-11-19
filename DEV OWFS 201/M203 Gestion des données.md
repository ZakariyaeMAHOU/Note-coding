## [Playlist](https://youtube.com/playlist?list=PLKV6WevXj-lV2tqD_3ljxspt4qAFGK-M1&si=AkzSh7I-tVFpf8jk): [Mongo DB](https://youtube.com/playlist?list=PLKV6WevXj-lXoIcHSYDa4m1Cjy2KGxV8k&si=m18swjl5_XAUGET_):[Copilot](https://copilot.microsoft.com/shares/XsVLHwkBoRAuFYWCgTfNH):

## 1. <span style="color: rgb(255 100 100)">Exploiter les fonctionnalités avancées d’un SGBD relationnel </span>:
### <span style="color: rgb(50 200 50)">Maitriser le langage de programmation procédurale sous MySQL</span>:
#### <span style="color: rgb(10 150 255)">Les sous-programmes</span>:
- **Un sous proramme** est un bloc d’instructions est composé de :
	- **BIGIN** : debut du bloc
	- **DECLARE**(directive optionnelle):déclare une variable, un curseur, une exception, etc. ; 
	- END : ferme le bloc
-  **Types**:
	- **Functions:** 
		- Fonctions intégrées (CURRENT_DATE(), AVG(), SUM(), ABS(), CONCAT()...)
		- Fonction définie par l'utilisateur (UDF)
```MySQL
			USE nom_bd;
			DROP FUNCTION IF EXISTS nom_fonction;
			delimiter $$
			CREATE FUNCTION nom_fonction ([parameter(s)])
				RETURNS type_retour
				déclaration informative(
					DETERMINISTIC ||
					READS SQL DATA ||
					MODIFIES SQL DATA ||
					CONTAINS SQL
				) 
				begin
					declare var type;
					set var = (select ..... from ...... where ....... );
					return var;
				end $$;
			delimiter ;
			```
=>الدوال كاترجع أنواع بسيطة (int - float - varchar) ماتقدرش ترجع (table)
- **Procédure stockée:** 
```mysql
	delimiter $$ 
	create procedure nom_procedure([parametres])
		begin
			le code sql
		end $$
		syntax pour exécuter une procédures stockée
	call nom_procedure([parametres]);
```
#### <span style="color: rgb(10 150 255)">Les variables</span>:
- **Déclaration des variables scalaires:**
![[m203-sou-programme-les-variables.png]]
- **Déclaration des variables de session (externes):**
![[m203-sou-programme-les-variables-extern.png]]
- **Portée des objets:**
		- La portée d’un objet (variable, curseur ou exception) est limitée au bloc dans lequel il est déclaré. Un objet déclaré dans un bloc est accessible dans les sous-blocs.
		- En revanche, un objet déclaré dans un sous-bloc n’est pas visible du bloc conteur.
#### <span style="color: rgb(10 150 255)">Verrouillage des tables </span>:
![[m203-sou-programme-verrouillage.png]]
![[m203-sou-programme-verrouillage-synthax.png]]
![[m203-sou-programme-verrouillage-typespng.png]]


#### <span style="color: rgb(10 150 255)">Conditions</span>:
##### if:
![[m203-condition-if.png]]
##### case:
![[m203-condition-case.png]]


#### <span style="color: rgb(10 150 255)">Les boucles</span>:
##### *Loop*:
![[m203-boucles-loop.png]]
##### *While*:
![[m203-boucles-while.png]]
##### *Repeat*:

### <span style="color: rgb(50 200 50)">Optimiser une base de données MySQL</span>:
### <span style="color: rgb(50 200 50)">Protéger la base de données MySQL</span>:
## 2. <span style="color: rgb(255 100 100)">Exploiter les fonctionnalités des bases de données NoSQL MongoDB</span>:
