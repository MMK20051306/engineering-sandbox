VERSION FRANÇAISE

Phase 0 : Analyse préalable & décryptage du cahier des charges 
Le piège classique est d'ouvrir le logiciel de dessin (CAO) immédiatement. C'est la première source d'erreurs : oubli de cotes, erreurs d'échelle ou mauvais choix de procédés de fabrication.
La Phase 0 est une étape purement intellectuelle et manuelle. C'est le moment où l'on prend une feuille, un surligneur, et où l'on traduit les exigences textuelles du client en actions géométriques et logiques claires.

La méthodologie :
Pour décoder n'importe quel projet industriel, l'ingénieur applique une méthode stricte en 5 étapes :

A. LIRE le cahier des charges : Analyser le texte brut transmis par le client pour en extraire la fonction de la pièce, ses dimensions limites, ses formes, ses fixations et son matériau.

B. TRADUIRE le cahier des charges dans une grille de décryptage : Remplir un tableau de correspondance technique divisé en trois colonnes :
Ce que je lis dans le texte (La donnée brute).
Pourquoi c'est écrit ? (L'explication physique, mécanique ou métier).
Ce que je vais dessiner concrètement (L'action géométrique sur le logiciel).

C. FAIRE le schéma de principe manuel : Réaliser un croquis à main levée sur papier. Ce brouillon technique permet de poser graphiquement l'Origine mécanique (le point [0,0] en bas à gauche), de tracer l'encombrement global et de calculer mathématiquement l'adresse exacte (coordonnées X, Y) de chaque fonction (trous, rainures) avant la modélisation.

D. VÉRIFIER à l'aide d’une check-list "Prêt pour la CAO" : Valider un filtre de sécurité sous forme de liste de contrôle. On ne démarre le logiciel informatique que si 100 % des cases sont cochées.
E. RÉDIGER la synthèse d'analyse : Rédiger un paragraphe de synthèse technique (Analyse Fonctionnelle) destiné au dossier de définition pour valider la faisabilité industrielle du projet.

Application au projet 01 : le gousset d'assemblage
A. LIRE le cahier des charges technique du client
Le gousset d'assemblage sert de nœud de jonction pour lier et renforcer l'assemblage de plusieurs poutres, profils ou tôles (par boulonnage ou rivetage).
Nom du composant : Gousset de jonction structurelle à 4 points
Dimensions globales : 150 × 150 mm
Épaisseur nominale : 6 mm (Matériau : PMMA / Plexiglas)
Géométrie : Profil triangulaire avec coins cassés (chanfreins de 10 mm à 45° pour éliminer les concentrations de contraintes)
Fixations : 4 perçages traversants de ∅ 8,5 mm positionnés pour le passage de boulons standard M8.
B. TRADUIRE le cahier des charges dans une grille de décryptage
Ce que je lis dans le texte
Pourquoi c'est écrit ?
 (L'explication simple)
 Ce que je vais dessiner concrètement
Profil triangulaire (150150 mm)
C'est l'encombrement global maximal et la forme de base de la pièce
Tracer un triangle rectangle de 150 mm de base et 150 mm de hauteur à l'origine de l'esquisse
Chanfreins de 10mm à 45°
Élimine les angles vifs pour la sécurité des opérateurs et supprime les concentrations de contraintes mécaniques
Utiliser l'outil Chanfrein d'esquisse sur les 3 sommets du triangle
4 trous de 8,5 mm pour vis M8
Une vis M8 fait 8 mm de diamètre. Un perçage à 8,5 mm offre un jeu fonctionnel de 0,5 mm pour insérer la vis sans forcer
Tracer 4 cercles de 8,5 mm et leur attribuer des coordonnées positionnelles X, Y rigoureuses
Épaisseur 6mm (PMMA / Plastique)
Définit la troisième dimension du volume et dicte le choix de la machine de production
• En CAO : Réaliser une extrusion de 6mm
• En FAO : Configurer les paramètres de coupe pour du PMMA de 6mm


C. FAIRE le croquis manuel et le calcul des coordonnées
Avant d'ouvrir la CAO, le schéma à main levée permet de cartographier les coordonnées cartésiennes de positionnement des centres des perçages par rapport à l'Origine (0,0) située sur le coin inférieur gauche de la plaque brute :
Point d'Origine (0,0) = Coin inférieur gauche de la pièce.
Centre Trou N°1 (Bas-Gauche) : X=25mm , Y=25mm
Centre Trou N°2 (Bas-Droite) : X=80mm , Y=25mm
Centre Trou N°3 (Haut-Gauche) : X=25mm , Y=80mm
Centre Trou N°4 (Centre géométrique) : X=70mm , Y=70mm
![Croquis Manuel de la Phase 0](schema_principe_phase0.png)
D. VÉRIFIER à l'aide d’une check-list "Prêt pour la CAO"
* [ ] **Forme de base validée :** Triangle rectangle de 150 × 150 mm 
* [ ] **Nombre et géométrie des trous validés :** 4 trous de ∅ 8,5 mm
* [ ] **Coordonnées de positionnement prêtes :** Tous les entraxes par rapport à l'origine (0,0) sont calculés et notés 
* [ ] **Procédé et Matériau validés :** PMMA 6 mm ➔ Découpeuse Laser CO2
E. RÉDIGER le rapport d'analyse fonctionnelle
Phase 0 – Analyse fonctionnelle et décryptage du besoin :
À la réception du cahier des charges, nous avons procédé à l'analyse des contraintes géométriques et matérielles. L'étude montre que la pièce est un gousset 2D d'épaisseur 6 mm en PMMA, nécessitant un détourage triangulaire chanfreiné et le perçage de 4 trous de passage M8 (∅  8,5 mm). Ce type de géométrie plane est idéalement adapté à une fabrication par découpe laser CO2.








ENGLISH VERSION
Phase 0: Requirements analysis & blueprint decoding methodology
The classic mistake is to open the CAD software immediately. This is the primary source of engineering errors, leading to missing dimensions, scaling issues, or incorrect manufacturing process selection.
Phase 0 is a purely intellectual and manual step. It is the exact moment when you take a notebook and a highlighter to translate the client’s raw text requirements into clear geometric definitions and logical manufacturing actions.

The methodology
To decode any engineering or industrial project, an engineer applies a strict 5-step methodology:

A. READ the technical specifications: Analyze the raw requirements document provided by the client to extract the component’s function, maximum boundary dimensions, shapes, hole patterns, and material specs.
B. TRANSLATE the requirements specification into a decoding matrix: Complete an engineering technical matrix divided into three distinct columns:
What I read in the text (The raw data constraint)
Why it is written? (The physical, mechanical, or trade explanation)
What I will actually draw (The specific geometric action required in the software)

C. DO the manual principle sketch: Draw a freehand sketch on a sheet of paper. This technical draft is crucial to graphically establish the Mechanical Origin (the [0,0] point at the bottom left corner), sketch the overall boundaries, and mathematically calculate the exact coordinates (X, Y) for every feature (holes, slots) prior to modeling.

D. VERIFY using a 'CAD-Ready' checklist: Review a safety gating checklist. Software modeling should only begin if 100% of the check boxes are validated.
E. DRAFT the analysis synthesis report: Write a concise functional analysis summary destined for the engineering definition file to validate the technical feasibility of the manufacturing process.

 Application to Project 01: structural gusset plate
A. READ the client's technical specifications
The structural gusset plate serves as a joint node to bind and reinforce the assembly of multiple beams, profiles, or sheets (via bolting or riveting).
Component Name: 4-Point Structural Joint Gusset
Overall Dimensions: 150 × 150 mm
Nominal Thickness: 6 mm (Material: PMMA / Acrylic)
Geometry: Triangular profile with broken corners (10 mm chamfers at 45° to eliminate stress concentrations)
Fasteners: 4 through-holes of ∅ 8.5 mm positioned to clear standard M8 bolts.
B. TRANSLATE the requirements specification into a decoding matrix: 
What I read in the text
Why it is written? 
(Simple explanation)
What I will actually draw
Triangular profile  (150150 mm)
Defines the maximum boundary envelope and the primary shape of the component
Sketch a right triangle with a 150 mm base and a 150 mm height anchored at the sketch origin
Chamfers of 10 mm at 45°
Eliminates sharp edges for operator safety and removes localized mechanical stress concentrations
Use the Sketch Chamfer tool on the 3 vertices (corners) of the triangle
4 holes of 8.5  mm for M8 bolts
An M8 bolt has an 8 mm major diameter. A hole drilled at 8.5 mm provides a 0.5 mm functional clearance to slide the bolt in smoothly
Sketch 4 circles of 8.5 mm and apply strict X, Y positional dimensions to their centers
Thickness of 6 mm (PMMA / Plastic)
Establishes the third dimension of the solid volume and dictates the production machinery
• In CAD: Execute a 6 mm solid extrusion
• In CAM: Configure cutting parameters optimized for 6 mm PMMA 


C. DO manual sketching & coordinate computation
Before launching the CAD software, a freehand drawing maps out the Cartesian coordinates to locate the hole centers relative to the Mechanical Origin (0,0) fixed at the bottom-left corner of the raw stock plate:
Origin Point (0,0) = Bottom-left corner of the component.
Hole N°1 Center (Bottom-Left): X=25mm , Y=25mm
Hole N°2 Center (Bottom-Right): X=80mm , Y=25mm
Hole N°3 Center (Top-Left): X=25mm , Y=80mm
Hole N°4 Center (Geometric Center): X=70mm , Y=70mm
D. VERIFY using a 'CAD-Ready' checklist 
* [ ] **Primary shape validated:** Right triangle measuring 150150 mm
* [ ] **Hole quantity and geometry validated:** 4 holes of ø 8.5 mm
* [ ] **Positional coordinates ready:** All centerline distances from the (0,0) origins are calculated and drafted
* [ ] **Process and Material validated:** 6 mm PMMA ➔ CO2 Laser Cutter
E. DRAFT the analysis synthesis report
Phase 0 – Functional Analysis & Requirement Decoding:
Upon receipt of the technical specifications, we proceeded to analyze the geometric and material constraints. The study indicates that the component is a 2D gusset plate with a nominal thickness of 6 mm made of PMMA, requiring a chamfered triangular profiling and the drilling of 4 clearance holes for M8 hardware (∅  8.5 mm). This type of planar geometry is ideally suited for manufacturing via CO2 laser cutting.


