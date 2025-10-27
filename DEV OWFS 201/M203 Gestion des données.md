# [Playlist](https://youtube.com/playlist?list=PLKV6WevXj-lV2tqD_3ljxspt4qAFGK-M1&si=AkzSh7I-tVFpf8jk):
> [!NOTE] Resume
> ### 1. Exploiter les fonctionnalités avancées d’un SGBD relationnel 
> ### استغلال الميزات المتقدمة لنظام إدارة قواعد البيانات العلائقية
> - Maitriser le langage de programmation procédurale sous MySQL 
> - إتقان برمجة المنطق داخل قاعدة البيانات
> - Optimiser une base de données MySQL 
> - تحسين أداء القاعدة وزمن الاستجابة مع الحفاظ على الدقة والاعتمادية
> - Protéger la base de données MySQL 
> - تأمين قاعدة MySQL ضدّ الاختراق والفقدان وسوء الاستخدام
> ### 2. Exploiter les fonctionnalités des bases de données NoSQL MongoDB 
> ### استغلال ميزات قواعد بيانات MongoDB NoSQL
> - Découvrir les bases de données NoSQL 
> - اكتشف قواعد بيانات NoSQL
> - Mettre en place une base de données MongoDB 
> - إعداد قاعدة بيانات MongoDB
> - Modéliser les documents 
> - وثائق نموذجية
> - Manipuler les données avec mongoDB 
> - معالجة البيانات باستخدام MongoDB
> - Effectuer des requêtes depuis des programmes Python 
> - تنفيذ الاستعلامات من برامج بايثون
> - Sécuriser une base de données MongoDB
> - تأمين قاعدة بيانات MongoDB

## 1. <span style="color: rgb(255 100 100)">Exploiter les fonctionnalités avancées d’un SGBD relationnel </span>:
### <span style="color: rgb(50 200 50)">Maitriser le langage de programmation procédurale sous MySQL</span>:
#### <span style="color: rgb(10 150 255)">les différents types des programmes MySQL</span>:
##### Les sous-programmes:
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
			CREATE FUNCTION nom_fonction ([parameter(s)])
				RETURNS type_retour
				déclaration informative(DETERMINISTIC || READS SQL DATA || MODIFIES SQL DATA || CONTAINS SQL) 
				Instructions
			```
### <span style="color: rgb(50 200 50)">Optimiser une base de données MySQL</span>:
### <span style="color: rgb(50 200 50)">Protéger la base de données MySQL</span>: