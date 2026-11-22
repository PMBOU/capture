# PASSATION — Dossier SwissLife (reprise sur le PC)

*Rédigé le 22/11/2026 par la session cloud. La session qui lit ce fichier tourne sur le PC de l'utilisateur et a accès à C:\atelier-local, à Documents, à Mon Drive et au NAS. Elle reprend le travail à partir d'ici.*

## Contexte
- Utilisateur : Pierre-Matthieu Bourlier (Gévezé, 35), ancien dirigeant de Baty-Home (liquidation judiciaire prononcée le 09/12/2025 par le TC de Saint-Malo).
- Demande : (1) réunir et classer TOUS les documents SwissLife (mails, atelier local, NAS, Drive) selon la norme GED `AAAA-MM-JJ_ENTITE_TYPE_objet` ; (2) analyser le contrat de prévoyance et les courriers, puis engager les démarches pour faire valoir ses droits ; (3) identifier des avocats spécialisés.
- **Fait** (session cloud, depuis Gmail uniquement) : classement de tout le dossier, chronologie, analyse juridique, recherche d'avocats, projets de courriers. Gmail est **épuisé** : inutile de le refouiller.
- **Reste à faire** : fouiller les sources locales (ci-dessous), compléter le dossier, mettre l'analyse à jour, finaliser les courriers avec l'utilisateur.

## À lire d'abord, dans cet ordre
1. `README.md` (arborescence)
2. `00_INDEX/NOMENCLATURE.md` (règles de nommage : les appliquer strictement)
3. `01_PREVOYANCE_016917558/ANALYSE_JURIDIQUE_ET_STRATEGIE.md` (analyse, moyens, chiffrage, plan d'action, questions)
4. `01_PREVOYANCE_016917558/CHRONOLOGIE_FAITS.md` (faits sourcés et §7 « Pièces manquantes »)
5. `07_DEMARCHES/` (projets de courriers : **aucun n'est envoyé**)
6. `00_INDEX/RECHERCHE_AVOCATS_ET_RECOURS.md`

## Contrats
| Contrat | Nature | Dossier |
|---|---|---|
| 016917558 (client AJ175103) | SwissLife Prévoyance Indépendants : **le litige** | 01_PREVOYANCE_016917558 |
| 016917557 (adhérent 045874106) | Santé Entreprise / Dirigeants | 02_SANTE_016917557 |
| 0010569593001 | PER individuel (SLPERTNS) : rachat 2622ONA | 03_VIE-RETRAITE_0010569593001 |
| 0010716098001 | Assurance vie Stratégic Premium : rachat 2622OOO | 04_VIE-RETRAITE_0010716098001 |
Courtier : Mon Assurance Facile (Yvonnick Dubourg). Commissaire de justice : B2H (réf. H613825).

## Le litige en bref
Arrêt de travail continu depuis le 06/05/2025 (affection psychiatrique, sinistre 08069874). Refus du 02/07/2025 : il faut une hospitalisation d'au moins 1 nuitée en établissement spécialisé. Hospitalisation à partir du 29/01/2026, puis du 18/02 au 02/04/2026 (polyclinique Saint-Laurent, étiquette « Lit : PSY »). Classement sans suite du 22/07/2026 pour « suspension de garantie depuis le 13/02/2026 ». Résiliation en juin 2026. Arguments principaux :
- sinistre antérieur à la suspension (art. 2.4.5) ;
- mise en demeure du 13/01/2026 portant sur une cotisation non échue (février) ;
- notice contractuelle 5939C jamais produite ;
- délai de résiliation non respecté ;
- devoir de conseil du courtier.
Enjeu : environ 27 à 30 k€ échus, plus 3 000 €/mois.

## Tâches de cette session (sur le PC)
1. **Chercher** dans C:\atelier-local, Documents, Mon Drive (Google Drive synchronisé) et le NAS (demander à l'utilisateur la lettre de lecteur ou le chemin \\NAS) les fichiers contenant : SwissLife, Swiss Life, 016917558, 016917557, 0010569593001, 0010716098001, AJ175103, 045874106, 5939C, B2H, H613825, Saint-Laurent, Mon Assurance Facile, Ma Santé Facile, prévoyance. Chercher aussi dans le contenu des PDF (pdftotext si disponible).
2. **Priorités**, d'après le §7 de la chronologie :
   - **notice d'information 5939C** (la pièce la plus importante) ;
   - demande d'adhésion et déclaration de santé de 2021 ; documents et devis du courtier, avec l'option « rachat conditions d'hospitalisation psychiatrique » ;
   - informations annuelles et échéanciers 2023-2026 ;
   - relevés bancaires montrant les prélèvements ou rejets SwissLife 2025-2026 ;
   - preuve de paiement B2H (871,20 €) ; paiement éventuel des 269,30 € ;
   - lettre de résiliation datée ; avis de réception signés ;
   - comptes rendus d'hospitalisation et bulletins de situation (29/01/2026 ; 18/02 au 02/04/2026) ;
   - attestation frais généraux 2025 et justificatifs de charges ;
   - contrat collectif SwissLife Prévoyance Entreprises + de Baty-Home ;
   - montants des rachats du PER et de l'assurance vie (décomptes).
3. **Copier** (jamais déplacer ni supprimer) dans le bon sous-dossier, renommer selon la nomenclature, dédoublonner par md5 contre l'existant. Pièces médicales dans `_SENSIBLE_MEDICAL`. Ajouter une ligne par fichier dans `00_INDEX/MANIFESTE.csv`. Ne jamais inventer de date.
4. **Mettre à jour** `CHRONOLOGIE_FAITS.md` (§7) et `ANALYSE_JURIDIQUE_ET_STRATEGIE.md` avec les trouvailles. En particulier : si la notice 5939C est trouvée, vérifier si la clause psychiatrique (« hospitalisation d'au moins 1 nuitée ») et la phrase « Seuls sont pris en charge (...) les sinistres pour lesquels l'hospitalisation est survenue pendant la période de validité du contrat » y figurent. C'est déterminant pour l'enjeu.
5. **Poser à l'utilisateur** les questions du §7 de l'analyse si elles n'ont pas de réponse : nuitée du 29/01/2026 ; arrêt continu ; paiement B2H et des 269,30 € ; réception de la mise en demeure de janvier ; protection juridique.
6. **Finaliser** les courriers de `07_DEMARCHES/` (remplir les [À COMPLÉTER]). **Ne rien envoyer** sans accord explicite de l'utilisateur, et conseiller de les faire relire par un avocat spécialisé en assurance de personnes (Me Xavier Odinot, avocat actuel de l'utilisateur, traite le conflit Baty-Home/Vandin, pas SwissLife).

## Règles
- Originaux intacts (copies uniquement) ; opérations réversibles.
- Ne pas diffuser de données sensibles (pièces médicales, n° de sécurité sociale, pièce d'identité, IBAN) en dehors de ce dossier.
- Le dossier est aussi versionné sur GitHub (dépôt PMBOU/capture, branche `claude/swisslife-dossier-contrats-n7kce4`), sans les pièces sensibles. Pas besoin de pousser depuis le PC, sauf si l'utilisateur le demande.
