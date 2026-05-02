# NetSecurePro-Identity

**Standard ouvert d’identité souveraine pour les systèmes de santé et les environnements OT critiques**

[![License: Sovereign Dekode](https://img.shields.io/badge/License-Sovereign%20Dekode-blue.svg)](LICENSE)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXXX)
[![Version](https://img.shields.io/badge/version-1.0.0-success)](https://github.com/MZoubirou/NetSecurePro-Identity)

---

## Contexte

**NetSecurePro-Identity** est un protocole d’identité numérique souveraine conçu pour les environnements médicaux et opérationnels critiques (OT). Il permet de gérer des identités et des attestations vérifiables **hors ligne**, tout en garantissant la conformité RGPD, HDS et les standards W3C DID.

Ce projet fait partie de l’initiative **Z-CORE OS IA v2.6** et du système **GRONDIN v2** (commandes médicales sécurisées).

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
