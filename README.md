[![Python](https://img.shields.io/badge/python-3.7-blue.svg)](
    https://python.org)
[![CircleCI](https://circleci.com/gh/mbaudin47/hpcuqtraining.svg?style=svg)](
    https://circleci.com/gh/mbaudin47/hpcuqtraining)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Doc license](https://img.shields.io/badge/Doc%20Licence-CC--BY--SA--4.0-orange)](https://github.com/mbaudin47/hpcuqtraining/blob/master/LICENSE-doc-cc-by-sa-4.0.txt)
[![Binder](https://mybinder.org/badge_logo.svg)](
    https://mybinder.org/v2/gh/mbaudin47/hpcuqtraining/master?filepath=2020/Scripts/Calibration/Exercice-calage-bayesien-Chaboche.ipynb)

# HPC and UQ Training 

This project contains the training material for the PRACE training on High Performance Computing in Uncertainty Quantification.

*Contacts*

 - EDF : Anne Dutfoy (anne.dutfoy@edf.fr), Michaël Baudin (michael.baudin@edf.fr), Roman Sueur (roman.sueur@edf.fr), Ovidiu Mircescu (ovidiu.mircescu@edf.fr)
 - Phiméca Engineering : Gaëtan Blondet (blondet@phimeca.com)
 - IMACS : Kieran Delamotte (delamotte@imacs.polytechnique.fr)
 - CEA : Jean-Baptiste Blanchard (jean-baptiste.blanchard@cea.fr), Fabrice Gaudier (fabrice.gaudier@cea.fr)

*Partnership for Advanced Computing in Europe (PRACE), OpenTURNS  Consortium and CEA*

Cette formation, donnée dans le cadre du projet européen PRACE, propose de former les stagiaires à propager des incertitudes dans un code de calcul, selon une méthodologie en 4 étapes reconnue par la Communauté Incertitudes : spécification du problème, quantification des incertitudes, propagation, analyse de sensibilité. 

L’étape de spécification apprend au stagiaire à délimiter son problème d’incertitudes (incertitudes d’entrée, grandeur d’intérêt) et à en comprendre les caractéristiques (temps CPU d’évaluation de la fonction, gradients, …). L’étape de quantification apprend à modéliser un vecteur de variables aléatoire par une loi de probabilité, définie par jugement d’expert ou par estimation à partir de données. L’étape de propagation propage les incertitudes d’entrée jusqu’à la grandeur d’intérêt définie dans l’étape de spécification. L’étape d’analyse de sensibilité permet de comprendre l’impact relatif des incertitudes d’entrée sur l’évaluation de la grandeur d’intérêt. 
La formation aborde aussi les méthodes d'optimisation et decalibration de code, qui permet d’ajuster la loi d’une entrée aléatoire à partir de données d’une grandeur de sortie.

Les éléments théoriques présentés lors de la formation seront appliqués sur un cas jouet, à l’aide du Code OpenTURNS développé par le consortium OpenTURNS (EDF, Airbus, Onera, Phimeca, Imacs) ou du code Uranie développé par le CEA. Le langage utilisé est le Python.

La formation détaillera aussi les besoins en calcul haute performance du domaine particulier du traitement des incertitudes et développe les possibilités de calculs parallèles des plate-formes OpenTURNS et Uranie.

La formation est gratuite, ouverte à tous. Elle se déroule sur 3 jours à la Maison de la Simulation, sur le plateau de Saclay. L’inscription est obligatoire à l’adresse :

https://events.prace-ri.eu/event/931/

Si nécessaire, elle se déroule en langue anglaise.

La prochaine session aura lieu :

10-12 mai 2021, 9h30- 12h30 / 14h – 17h, Maison de la Simulation, France and online.

[feuille de route 2021]: https://github.com/mbaudin47/hpcuqtraining/blob/master/2021/Training-2021-Roadmap.rst

Pour plus de détails sur la session 2021, nous vous recommandons de consulter :

* la [feuille de route 2021].

## Licence

* Le code est disponible sous la licence LGPL.
* La formation est disponible sous la licence 
Creative Commons Attribution Share Alike 4.0 (cc-by-sa-4.0)

