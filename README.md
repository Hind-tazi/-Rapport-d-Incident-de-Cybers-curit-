# Rapports d'Incident de Cybersécurité

## 📋 Documentation des Incidents

Ce repository contient une collection de **rapports d'incidents de cybersécurité** détaillés, incluant analyses techniques, chronologies et recommandations.

---

## 📄 Incidents Documentés

### 1. Ransomware WannaCry - Infection Réseau Interne
**Fichier** : `exam`  
**Date** : 15/04/2025

**Résumé de l'Incident** :
- Type : **Ransomware WannaCry**
- Impact : 12 postes de travail et 3 serveurs affectés
- Utilisateurs impactés : ~50 utilisateurs (finance et IT)
- Perte estimée : 15 000 € de productivité

**Éléments Clés** :
- **Vecteur d'attaque** : Email de phishing avec pièce jointe malveillante
- **Vulnérabilité exploitée** : Absence du patch MS17-010 (SMB EternalBlue)
- **Temps d'incident** : 7h30 (08:30 - 15:30)

**Sections du Rapport** :
1. ✅ Résumé de l'incident
2. ✅ Portée et impact financier/opérationnel
3. ✅ Chronologie détaillée (timeline)
4. ✅ Analyse technique (IoC, processus malveillants)
5. ✅ Mesures de confinement, éradication et récupération
6. ✅ Recommandations et améliorations
7. ✅ Suivi et amélioration continue
8. ✅ Annexes (logs IDS, liste des systèmes affectés)

---

## 🔍 Structure d'un Rapport d'Incident

Chaque rapport suit la structure NIST :

```
1. Informations Générales
   - Nom de l'incident
   - Date de découverte
   - Auteur du rapport

2. Résumé Exécutif
   - Description courte de l'incident

3. Portée et Impact
   - Systèmes impactés
   - Utilisateurs affectés
   - Impact financier/réputationnel

4. Chronologie
   - Timeline précise des événements

5. Analyse Technique
   - Vecteur d'attaque
   - Vulnérabilités exploitées
   - Indicateurs de Compromission (IoC)

6. Mesures Prises
   - Confinement
   - Éradication
   - Récupération

7. Recommandations
   - Failles identifiées
   - Mesures correctives

8. Suivi & Amélioration Continue
   - Leçons tirées
   - Actions futures
```

---

## 🛡️ Frameworks & Normes Utilisés

- **NIST Incident Response** : Structure standard d'analyse
- **ISO/IEC 27035** : Gestion des incidents de sécurité
- **MITRE ATT&CK** : Techniques d'attaque documentées
- **CIS Controls** : Recommandations de sécurité

---

## 📊 Indicateurs de Compromission (IoC)

Chaque rapport documente les IoC pour :
- Adresses IP malveillantes
- Hashes de fichiers malveillants
- Processus suspects
- Connexions réseau anormales
- Extensions de fichiers malveillants

---

## 💡 Leçons Apprises

✅ Importance cruciale des **mises à jour système**  
✅ Nécessité de **formation utilisateur** sur le phishing  
✅ **Sauvegardes régulières** essentielles pour la récupération  
✅ **Surveillance proactive** avec EDR/IDS  
✅ **Plans de réponse** aux incidents bien documentés

---

## 🔧 Outils & Technologies

- 🔍 **Analyse réseau** : tcpdump, Wireshark, IDS/IPS
- 🖥️ **Forensics** : Logs système, memory forensics
- 📊 **Documentation** : Rapports structurés, timelines
- ⚙️ **Détection** : Endpoint Detection & Response (EDR)

---

## 📞 Auteur & Contact

**Auteur** : Hind Tazi  
**Email** : Fullhind.h@gmail.com  
**Téléphone** : +1 514 892 7160  
**Localisation** : Montréal, Québec, Canada

---

## 📌 Ressources Supplémentaires

- 📖 [NIST Incident Response](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf)
- 🔗 [MITRE ATT&CK Framework](https://attack.mitre.org/)
- 🛡️ [CIS Controls](https://www.cisecurity.org/controls/)

---

**Dernière mise à jour** : 13 juin 2026  
**Confidentialité** : Ces rapports contiennent des informations sensibles. À utiliser à titre professionnel uniquement.
