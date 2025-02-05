# ClasseurDoc

# **ClasseurDoc - Gestion de fichiers pour étudiants du Cégep**  

## **📌 Description**  
Le projet **ClasseurDoc** est une application Java visant à aider les étudiants du **Cégep** à mieux organiser leurs fichiers de cours. Beaucoup de jeunes étudiants rencontrent des difficultés pour classer leurs documents numériques, ce qui peut entraîner une **désorganisation extrême** et potentiellement nuire à leur réussite académique.  

Ce programme permet aux étudiants de **créer automatiquement une structure de dossiers bien organisée** pour leurs cours, en fonction de leur méthode de classement préférée.  

---

## **🎯 Fonctionnalités**
- 📂 **Création automatique de dossiers** pour chaque cours.  
- 🗂 **Deux types de classement disponibles** :  
  1. **Par semaine** (Semaine 1, Semaine 2, ... jusqu'à Semaine 15).  
  2. **Par catégorie** (Cours, Travaux, Solutions).  
- 📍 **Choix du répertoire de sauvegarde** via un explorateur de fichiers (`JFileChooser`).  
- ⚡ **Interface simple via `JOptionPane`** pour une interaction rapide.  

---

## **🚀 Installation et utilisation**
### **1️⃣ Prérequis**
- **Java JDK 8 ou supérieur** installé sur votre ordinateur.  
- Un **IDE Java** (Eclipse, IntelliJ IDEA, NetBeans) ou un terminal avec `javac`.  

### **2️⃣ Compilation et exécution**
#### **Avec un IDE (Eclipse, IntelliJ, NetBeans)**
1. Clone ou télécharge le projet.  
2. Ouvre le fichier `Etudes.java` dans ton IDE.  
3. Exécute le programme.  

#### **Avec un terminal**
1. Place-toi dans le dossier contenant le fichier `Etudes.java`.  
2. Compile le fichier :  
   ```sh
   javac Etudes.java
   ```
3. Exécute le programme :  
   ```sh
   java Etudes
   ```

---

## **🛠 Mode d'emploi**
1. **Lance le programme**.  
2. **Indique le nombre de dossiers à créer** (correspondant aux différents cours).  
3. **Choisis un mode de classement** :  
   - `1` → Classe les fichiers **par semaine** (`Semaine1`, `Semaine2`, ...).  
   - `2` → Classe les fichiers **par catégorie** (`Cours`, `Travaux`, `Solutions`).  
4. **Sélectionne l’emplacement où tu veux créer les dossiers**.  
5. **Les dossiers sont créés automatiquement** et organisés selon ton choix ! 🎉  

---

## **📝 Exemples de structure générée**
### **1️⃣ Mode "Par semaine" (`1`)**
Si tu as 2 cours **(Math, Informatique)** et que tu choisis ce mode, la structure générée sera :  
```
📂 Math  
    ├── 📂 Semaine1  
    ├── 📂 Semaine2  
    ├── 📂 ...  
    ├── 📂 Semaine15  
📂 Informatique  
    ├── 📂 Semaine1  
    ├── 📂 Semaine2  
    ├── 📂 ...  
    ├── 📂 Semaine15  
```

### **2️⃣ Mode "Par catégorie" (`2`)**
Si tu choisis ce mode, voici la structure des dossiers :  
```
📂 Math  
    ├── 📂 Cours  
    ├── 📂 Travaux  
    ├── 📂 Solutions  
📂 Informatique  
    ├── 📂 Cours  
    ├── 📂 Travaux  
    ├── 📂 Solutions  

---
