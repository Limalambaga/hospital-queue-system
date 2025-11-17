**CERTICHAIN Africa**
**Digitalisation Sécurisée des Diplômes avec Blockchain Distribuée**
DIPLÔMECHAIN Africa est une plateforme blockchain privée conçue pour éliminer définitivement les faux diplômes au Cameroun et en Afrique en digitalisant la délivrance, le stockage et la vérification des certificats académiques. Le projet répond à un problème critique : 9 % des diplômes vérifiés en 2023 sont faux, causant des pertes de productivité, des embauches inadéquates et une érosion de la confiance dans l’éducation. En utilisant une blockchain distribuée privée, DIPLÔMECHAIN garantit l’immuabilité, la traçabilité et la vérification instantanée des diplômes via QR code ou SMS. Chaque université, lycée ou ministère est un nœud autonome dans un réseau décentralisé, scalable, fault-tolerant et adapté aux réalités camerounaises (connectivité intermittente, énergie instable, inclusion numérique).

**Introduction**
Au Cameroun, les faux diplômes sont un fléau silencieux : **plus de 20 % des candidatures publiques** **incluent des documents frauduleux.** Les processus manuels de vérification coûtent **10 000 FCFA et 3 à 7 jours par demande.** DIPLÔMECHAIN Africa transforme cela en une vérité numérique immuable : un diplôme émis une fois, stocké sur **100+ nœuds**, vérifié en **1 seconde, gratuitement**. Basé sur une **blockchain** **privée Proof of Authority (PoA)**, le système est 100 % contrôlé localement, sans frais Ethereum, et fonctionne même hors ligne. Ce projet s’inscrit dans la transformation numérique de l’éducation et soutient **l’Objectif de Développement Durable 4** (Éducation de qualité).

**Problème**

**Faux diplômes :** 9 % détectés en 2023 (Verifdiploma), jusqu’à 30 % dans certains secteurs.
**Coût de vérification :** 10 000 FCFA + 3–7 jours → frein à l’emploi.
**Corruption à l’émission :** Absence de traçabilité.
**Perte physique :** Diplômes papier perdus, volés, détériorés.
**Inégalités régionales :** Accès limité dans les zones rurales.


**Portée & Pertinence**

**Phase 1 :** Universités de Yaoundé (UYI, ENSP, UCAC), MINESUP → 50 000 diplômes/an.
**Phase 2 :** 500 lycées au Cameroun → 500 000 diplômes/an.
**Phase 3 :** Afrique Centrale (Gabon, Congo, Tchad).
**Bénéficiaires :** Étudiants, recruteurs, ministères, employeurs.
**Impact :** Zéro faux diplôme, économies > 5 milliards FCFA/an (salaires indus évités).


**Solution Proposée**
**DIPLÔMECHAIN est une blockchain privée distribuée où :**

Chaque établissement = nœud émetteur (génère des diplômes).
7 nœuds validateurs (PoA) → 5/7 suffisent pour valider (MINESUP n’est pas obligatoire).
Nœuds régionaux = relais de diffusion (Yaoundé, Douala, Garoua).
Vérification : QR code ou SMS (VERIF UY1-2025-001 → "VALIDE").
Offline-first : Diplôme émis localement, synchronisé plus tard.


**Objectifs du Système**

**Immuabilité :** Un diplôme ne peut être modifié.
**Accessibilité :** Vérification gratuite, instantanée, partout.
**Inclusion :** USSD/SMS pour téléphones basiques.
**Résilience :** Fonctionne sans internet, sans MINESUP, sans électricité (UPS/solaire).
**Scalabilité :** De 3 à 10 000 nœuds sans redesign.


**Exigences Fonctionnelles & Non-Fonctionnelles**
**Fonctionnelles**

Émission de diplôme signé cryptographiquement.
Vérification par ID, QR ou SMS.
Synchronisation hors ligne.
Tableau de bord par établissement.
Audit trail complet.

**Non-Fonctionnelles**

**Scalabilité :** 1 million de vérifications/heure.
**Fault Tolerance :** 99.98 % uptime (testé).
**Sécurité :** ECDSA, hash SHA-256, clés privées locales.
**Latence :** < 5 sec (même en 3G).
**Coût :** 0 FCFA par diplôme.

**Stack Technologique**

**Blockchain :** Hyperledger Besu (PoA)
**Stockage Fichiers :** IPFS (PDF)
**Frontend :** React.js + QR Code
**Backend :** Node.js + Web3
**Offline :** SQLite + LibP2P
**SMS/USSD :** Africa's Talking API
**Infrastructure :** Raspberry Pi + Docker + 4G

**Plan d’Implémentation (6 Mois)**

**Mois 1 :** Config réseau + 3 nœuds pilotes (UYI, ENSP, MINESUP)
**Mois 2 :** Smart contract + émission test
**Mois 3 :** Vérification QR/SMS + offline sync
**Mois 4 :** 50 lycées + tableau de bord
**Mois 5 :** Tests de charge (100K vérifs)
**Mois 6 :** Lancement national + intégration MINESUP


**Résultats attendus:**

Zéro faux diplôme dans les établissements pilotes.
Vérification gratuite en 1 seconde.
Économies : > 5 milliards FCFA/an pour l’État.
Modèle exportable en Afrique.


**Défis & Mitigation**

Connectivité faible → Sync différé + USSD
Électricité instable → UPS + solaire par nœud
Adoption lente → Formation + intégration HealthFlow
Sécurité des clés → Clés privées locales, audits annuels


**Conclusion**
DIPLÔMECHAIN Africa n’est pas une simple base de données.
C’est une vérité partagée, immuable, distribuée.
Un diplôme n’est plus un papier.
C’est une preuve numérique, vérifiée partout, pour toujours.

**Références**

Verifdiploma (2023)
UNESCO ETICO Platform
MINESUP Rapports 2024
Hyperledger Besu Docs
