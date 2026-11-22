# Dossier SWISSLIFE — Nomenclature

Format : `AAAA-MM-JJ_ENTITE_TYPE_objet.ext` — ASCII strict, `_` entre blocs, `-` entre mots, pas d'accents.

- **Date** = date du document (date du courrier/de l'email). Inconnue → `date-inconnue_`. Date tirée d'une métadonnée seulement → noter `[a-verifier]` au manifeste.
- **ENTITE** = émetteur / contrepartie : `SWISSLIFE`, `B2H` (commissaire de justice), `MAF` (courtier Mon Assurance Facile), `PMB` (envoyé par moi), `CPAM`, `FRANCE-TRAVAIL`, `MEDECIN`, etc.
- **TYPE** :
  - `CTR` contrat, conditions générales/particulières, notice, avenant, adhésion
  - `MAIL-REC` email reçu · `MAIL-ENV` email envoyé
  - `COU-REC` courrier reçu (PDF joint) · `COU-ENV` courrier envoyé
  - `DEC` décompte / avis de paiement / relevé de prestations
  - `ECH` échéancier / appel de cotisation / avis d'échéance
  - `REC` recouvrement, relance, mise en demeure
  - `ATT` attestation · `JUS` justificatif fourni · `MED` pièce médicale (→ `_SENSIBLE_MEDICAL`)
  - `NOT` notification automatique (espace client, identifiant…)
  - `REL` relevé de situation (épargne/retraite)
- **objet** = n° de demande / sinistre / contrat + objet court (ex. `arret-261T4GX_demande-pieces`).

Exemple : `2025-08-20_B2H_REC_prime-impayee-016917558_871-20EUR.pdf`

Chaque email est conservé en `.md` (en-têtes + corps texte), ses pièces jointes renommées à côté, avec le même préfixe date.
Le manifeste `00_INDEX/MANIFESTE.csv` trace : `fichier;dossier;date;entite;type;objet;source;gmail_thread_id;nom_origine;sensible;remarque`.
