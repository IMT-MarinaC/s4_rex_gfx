# 🐙 Projet Octolotl - GFX

> **Rapport d'analyse et de conception d'une pieuvre imaginaire en GFX.**
> 
> [🔗 Voir le rapport interactif en direct](https://imt-marinac.github.io/s4_rex_gfx/)

---

## 📝 Présentation du projet
Ce projet s'inscrit dans le cadre de l'UE **GFX**. L'objectif était de concevoir, modéliser, animer et intégrer une créature imaginaire en respectant un pipeline de production 3D complet pour le web.

L'**Octolotl** est une fusion morphologique entre un axolotl (tête, branchies) et une pieuvre (tentacules, système de mouvement).

## 🚀 Technologies utilisées
*   **Modélisation & Animation** : Blender 5.1.0
*   **Format d'export** : glTF 2.0 (.GLB) 
*   **Intégration Web** : HTML5 / CSS3 (Architecture Mobile-First).
*   **Rendu 3D Web** : Google `<model-viewer>` & Three.js (Scripting personnalisé pour le multi-track animation).

## 🛠️ Pipeline Technique
1.  **Conception** : Brainstorming et création de concepts via IA (Gemini) et références biologiques.
2.  **Rigging** : Mise en place d'une armature complexe pour les 8 tentacules.
3.  **Modélisation** : Création du maillage (Mesh).
4.  **Texturing** : Travail sur les shaders pour obtenir un aspect "Pearl-Skin" humide.
5.  **Animation** : Création de cycles d'ondulation organiques.
6.  **Déploiement** : Intégration dans un rapport interactif responsive.

## 📈 Retour d'Expérience (REX)
Le rapport complet inclut une description du modèle ainsi qu'une analyse des défis rencontrés, notamment :
*   La gestion de l'**UV Mapping** sur des formes organiques complexes.
*   Le script JavaScript développé pour synchroniser plusieurs pistes d'animations simultanées dans le navigateur.
*   L'optimisation de la scénographie via l'**IBL (Image Based Lighting)**.
