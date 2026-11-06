# Sources de la veille réglementaire drones

Statut : **UE, France et organismes connexes validés** par le propriétaire. Seules les sources officielles sont retenues.

Légende des statuts :
- **À valider** : proposée, non encore validée.
- **Validée** : validée par le propriétaire, prête pour la veille.
- **Rejetée** : écartée par le propriétaire.

Date de dernière vérification de l'URL : 2026-11-06.

## 1. Sources primaires UE

| # | Source | Type | URL | Statut (test du 2026-11-06) |
|---|--------|------|-----|--------|
| UE-1 | EUR-Lex : règlement d'exécution (UE) 2019/947 (exploitation) | Texte officiel (JO) | https://eur-lex.europa.eu/eli/reg_impl/2019/947/oj | Accessible (HTTP 200) |
| UE-2 | EASA : réglementation et standards drones | Page officielle de l'agence | https://www.easa.europa.eu/en/domains/drones-air-mobility/rules-standards | Accessible (HTTP 200) |
| UE-3 | EASA : AMC/GM UAS (moyens de conformité et guides) | Guidance officielle | https://www.easa.europa.eu/en/document-library/acceptable-means-of-compliance-and-guidance-material/reg/unmanned-aircraft-systems-uas | Accessible (HTTP 200) |
| UE-4 | EASA : FAQ réglementation drones | Réponses officielles | https://www.easa.europa.eu/en/newsroom-and-events/news/easa-published-faqs-european-drones-regulation | Accessible (HTTP 200) |
| UE-5 | Règlement délégué (UE) 2019/945 (conception, classes C0 à C4) | Texte officiel (JO), version consolidée | https://eur-lex.europa.eu/eli/reg_del/2019/945/oj | Accessible (HTTP 202) ; versions consolidées 2025 à vérifier |
## 2. Sources primaires France

| # | Source | Type | URL | Statut (test du 2026-11-06) |
|---|--------|------|-----|--------|
| FR-1 | SIA : AIP France, suppléments (SUP) et circulaires (AIC) | Publication officielle de la navigation aérienne | https://www.sia.aviation-civile.gouv.fr | Accessible (HTTP 200) |
| FR-2a | DGAC (publiée sur ecologie.gouv.fr) : exploitation en catégorie spécifique (mise à jour 13/07/2026) | Page officielle | https://www.ecologie.gouv.fr/exploitation-drones-en-categorie-specifique | Accessible (HTTP 200) |
| FR-2b | DGAC : formation à la catégorie ouverte (UAS) | Page officielle | https://www.ecologie.gouv.fr/formation-categorie-ouverte-uas | Accessible (HTTP 200) |
| FR-2c | DGAC : FAQ transition européenne UAS (PDF) | Document officiel | https://www.ecologie.gouv.fr/sites/default/files/documents/FAQ_Transition_europeenne_UAS.pdf | Accessible (HTTP 200) |
| FR-2d | DGAC : fiche réflexe catégorie spécifique (PDF) | Document officiel | https://www.ecologie.gouv.fr/sites/default/files/documents/Fiche_reflexe_specifique.pdf | Accessible (HTTP 200) |
| FR-2e | DGAC : site principal aviation-civile.gouv.fr | Site officiel de l'autorité | https://www.aviation-civile.gouv.fr | Inaccessible : certificat TLS expiré (vérification impossible) |
| FR-3 | « Mon espace drone » : déclaration d'opérateur | Télé-service officiel | https://monespacedrone.dsac.aviation-civile.gouv.fr (à confirmer sur aviation-civile.gouv.fr) | Inaccessible : passerelle en erreur 502 |
| FR-4 | Géoportail : carte des zones de restriction drones (DGAC / IGN) | Carte officielle | https://cartes.gouv.fr (ancien www.geoportail.gouv.fr redirige ici) | Accessible (HTTP 200) |
| FR-5 | Légifrance : arrêté du 3 décembre 2020 (scénarios standard nationaux) et textes nationaux | Texte officiel (JORF) | https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000053435245 (titre de l'arrêté à confirmer) | Inaccessible : HTTP 403 du proxy |
## 3. Organismes connexes (primaires)

| # | Source | Type | URL | Statut (test du 2026-11-06) |
|---|--------|------|-----|--------|
| CO-1 | CNIL : drones et captation d'images (RGPD) | Autorité officielle | https://www.cnil.fr (page drones à confirmer) | Accessible (HTTP 200) |
| CO-2 | ANFR : fréquences et équipements radio des drones | Autorité officielle | https://www.anfr.fr (page drones à confirmer) | Accessible (HTTP 200) |
## 4. Points à vérifier avant validation

- **Scénarios nationaux** (arrêté du 3 décembre 2020) : selon des sources secondaires, la réglementation UE ne permettait leur usage que jusqu'au 1er janvier 2026. Le texte officiel doit confirmer ce point avant toute publication.
- **Déclaration** : les sources secondaires se contredisent sur la durée de validité (24 mois ou 5 ans) et sur le portail. À vérifier sur aviation-civile.gouv.fr.

- Les informations sur le passage aux scénarios européens au 1er janvier 2026 proviennent de questions parlementaires. Elles doivent être confirmées dans les textes UE ou français avant d'être retenues.
- L'AIC France A 011/26 (zones de conflit) : son application aux drones reste à établir.

## 5. Alertes

- Mode : **alerte immédiate** (demandé par le propriétaire).
- Limite à noter : une routine planifiée n'est pas un temps réel. Elle vérifie à intervalle régulier. Des abonnements officiels (alertes EUR-Lex, lettres EASA, notifications SIA) peuvent réduire ce délai. À confirmer pour chaque source.
- Canal de notification : à définir.
