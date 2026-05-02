# NetSecurePro-Identity

**Identité Souveraine Post-Quantique pour les Environnements OT & Santé**

![License](https://img.shields.io/badge/License-Sovereign%20Dekode%20BSL-blue)
![PQC](https://img.shields.io/badge/PQC-Dilithium5%20%2B%20Falcon-success)
![Offline](https://img.shields.io/badge/Offline-First-100%25-brightgreen)

---

## Vision

**NetSecurePro-Identity** est le module d’identité numérique souverain de **Z-CORE OS IA v2.6**.  

Il offre une infrastructure d’identité **100 % offline**, **post-quantique** et **zéro confiance cloud étrangère**, conçue pour les systèmes critiques de santé et les environnements opérationnels (OT).

**Mission** : Reprendre le contrôle souverain des identités et des données sensibles avec un système qui dit **« NON par défaut »** à toute dépendance externe.

**Principe MILYES** : Souveraine. Signée. Traçable. Auditable.

---

## Fonctionnalités Clés

- **DID Method** : `did:zcore:` (décentralisée et souveraine)
- **Signatures Post-Quantiques** : Dilithium5 (primaire) + Falcon1024 (backup)
- **Verifiable Credentials W3C** : `MedicalCommandVC`, `NodeOperatorVC`, `PatientConsentVC`, `ResearcherVC`
- **Preuves ZKP** : Divulgation nulle, sélective et révocable
- **Protocole DZROUGE** : Intégration native avec hachage SHA256 + signature PQC
- **Fonctionnement** : 100 % offline-first sur edge hardware et Termux

---

## Architecture Z-CORE OS IA v2.6

| Module                    | Rôle principal                               | Statut     |
|---------------------------|----------------------------------------------|------------|
| GEMINI_CORE_2.6_PRO       | Noyau cognitif PQC                           | ACTIF      |
| GRONDIN v2                | Deep Packet Inspection commandes médicales   | Opérationnel |
| DZROUGE Terminal          | Exécution sécurisée locale                   | 12 nœuds   |
| AIMEDIXAL                 | Module Parkinson – DID/VC                    | Pilote     |
| CLAUDE-Z NΣ-X01           | Audit cryptographique souverain              | Validé     |

**Métriques** : 12 nœuds OT • 546 Mbps • 100 % souverain

---

## Installation Rapide

```bash
git clone https://github.com/milyes/NetSecurePro-Identity.git
cd NetSecurePro-Identity
chmod +x zcore-init.sh
./zcore-init.sh --mode=offline --pqc=dilithium5
## Objectifs

- Fournir une implémentation DID Method `did:zcore:` souveraine
- Définir des Verifiable Credentials adaptés au secteur santé (`MedicalCommandVC`, `NodeOperatorVC`, `PatientConsentVC`)
- Permettre le fonctionnement complet **offline** et en mode dégradé
- Assurer la traçabilité et l’auditabilité cryptographique
- Faciliter l’intégration avec des solutions de cybersécurité (Acronis, etc.)

## Fonctionnalités principales

- **DID Method** : `did:zcore:` (basée sur des clés locales et des registres distribués souverains)
- **Verifiable Credentials** standards pour le domaine médical
- **Support Post-Quantum Cryptography (PQC)**
- **Fonctionnement offline-first**
- **Conformité** : W3C DID, VC, RGPD, HDS, NIST PQC
- **Interopérabilité** avec ORCID et systèmes hospitaliers

## Structure du dépôt
