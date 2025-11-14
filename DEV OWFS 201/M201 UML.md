
> [!NOTE] Goal
> - تحليل احتياجات العميل وصياغة **cahier des charges**.
>- نمذجة المشروع باستعمال **UML** (Use Case, Classes, Séquence...).
>- تصميم **wireframes** و **maquettes UX/UI**.
>- اختيار الحلول والتقنيات المناسبة (langages, frameworks, BDD).
>- التخطيط للتنفيذ، الاختبار، النشر، والصيانة.

# [Playlist](https://youtube.com/playlist?list=PLKV6WevXj-lWNY1-w-UxB3YH8wbitNY6d&si=2NIwbgrcPtKG6Ba5):[ChatGPT](https://github.com/copilot/share/ca4d0222-0264-8017-9842-5e0f841221a1):
## <span style="color: rgb(255 100 100)">Partie1: Modéliser un projet web</span>:
### <span style="color: rgb(50 200 50)">Cycle de vie d'un projet web</span>:
#### Définition:
- définiet les différentes étapes par lesquelles un projet pass, de sa maintenance. Il fournit une structure et une compréhension communes de l'avancement du projet et des activité impliquées.
#### Etapes principales du cycle de vie d’un projet web:
 ![[m201-etape-principale.png]]
 1. تحليل الاحتياجات / مواصفات الاحتياجات (Analyse des besoins / spécifications)
  2. التصميم (Conception)
  3. التطوير (Développement / Codage)
  4. الاختبارات والنشر (Tests et déploiement)
  5.   الصيانة والتطوّر (Maintenance et évolutivité)
#### Les modèles:
- Modèle en cascade
![[m201-cascad.png]]
- Modèle en V
![[m201-v.png]]

### <span style="color: rgb(50 200 50);text-decoration:underline">Diagramme de cas d’utilisation</span>:
![[m201-d-cas-utilisation.png]]
#### <span style="color: rgb(10 150 255)">1. Identifier les acteurs</span>:
![[m201-d-cas-utilisation-acteur+cas.png]]
#### <span style="color: rgb(10 150 255)">2. Identifier les cas d'utilisation</span>:
###### syntax: 
	- ✅gerer les client
	- ❌generation les client
###### types: 
	- Cas général (gerer les client)
	- Cas spécefique (ajouter les client)
#### <span style="color: rgb(10 150 255)">3. Relation entre les acteurs et les cas d'utilisation</span>:
![[m201-d-cas-utilisation-relation(acteur&cas).png]]
#### <span style="color: rgb(10 150 255)">4. Relation entre cas d'utilisation</span>:
![[m201-d-cas-utilisation-relation-entre-cas&cas.png]]

#### <span style="color: rgb(10 150 255)">5. Generalisation</span>:
- entre les acteurs:
![[m201-d-cas-utilisation-generalisation-acteurs.png]]
- entre les cas:
![[m201-d-cas-utilisation-generalisation-cas.png]]

### <span style="color: rgb(50 200 50);text-decoration:underline">Diagramme de classes</span>:
#### <span style="color: rgb(10 150 255)">Composants d'un diagramme de classes UML</span>:
##### <span style="color: cyan">Classes</span>:
![[m201-d-classes-classe.png]]
(+) -> public : الكل يقدر يستعملها
(-) -> private : غير الكلاس نفسها تقدر تستعملها
(#) -> protected : الكلاس والورثة ديالها يقدرو يستعملوها
(~) -> package : الكلاسات اللي فـ نفس الحزمة يقدرو يستعملوها
![[m201-d-classes-visibilite.png]]
##### <span style="color: cyan">Relations entre les classes</span>:
- Association
- Aggregation
- Composition
- Héritage 
##### <span style="color: cyan">Les cardinalités</span>:
![[m201-d-classes-classe-cardinalite.png]]
![[m201-d-classes-classe-relation-entre-les-classe.png]]
![[m201-d-classes-classe-relation-entre-les-classe1.png]]


#### Exercice:
![[exercice-diagram-de -class.png]]
![[solution-dc.png]]

### <span style="color: rgb(50 200 50);text-decoration:underline">Diagramme de séquence</span>:
### <span style="color: rgb(50 200 50)">Elaborer des diagrammes UML à l’aide d’un outil de modélisation</span>:
## <span style="color: rgb(255 100 100)">Partie2: Représenter la vue dynamique d’un système</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Diagramme d'état</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Diagramme d'activités</span>:
## <span style="color: rgb(255 100 100)">Partie3: Créer une maquette pour le développement web</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">L'expérience et l’interface utilisateur</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Structurer un wireframe sur papier</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Structurer un wireframe avec Figma</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Créer une première maquette avec Figma</span>:
## <span style="color: rgb(255 100 100)">Partie4: Préparer l’environnement de développement web</span>:

### <span style="color: rgb(50 200 50);text-decoration:underline">Appréhender l’environnement de développement web</span>:
### <span style="color: rgb(50 200 50);text-decoration:underline">Choisir les Frameworks de développement web</span>: