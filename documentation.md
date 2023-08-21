

| **Type** | **Clé** | **Association** | **Clé exemple** |
| -------- | ------- | --------------- | --------------- |
| - | arrhes | Acompte en pourcentage | \`${arrhes}\` |
| - | commercial | Nom et prénom du commercial associé à la commande | \`${commercial}\` |
| company | email | Adresse e-mail de l'entreprise | \`${company.email}\` |
| company.informations | rcs | RCS de l'entreprise | \`${company.informations.rcs}\` |
| company.informations | tva | Numéro de TVA de l'entreprise | \`${company.informations.tva}\` |
| company.informations | siret | Numéro SIRET de l'entreprise | \`${company.informations.siret}\` |
| company.informations | ape | Code APE de l'entreprise | \`${company.informations.ape}\` |
| company | address | Adresse de l'entreprise | \`${company.address}\` |
| company | name | Nom de l'entreprise | \`${company.name}\` |
| company | phone | Numéro de téléphone de l'entreprise | \`${company.phone}\` |
| - | paymentConditions | Conditions de paiement | \`${paymentConditions}\` |
| - | paymentPenalties | Pénalités de paiement | \`${paymentPenalties}\` |
| - | defaultInsuranceByObject | Assurance par défaut par objet | \`${defaultInsuranceByObject}\` |
| - | dateDevis | Date du devis | \`${dateDevis}\` |
| - | date | Équivalent de `dateDevis` | \`${date}\` |
| - | dateValidity | Date de validité du devis | \`${dateValidity}\` |
| deliveries | date | Date de livraison | \`${deliveries.date}\` |
| deliveries | details | Détails techniques de la livraison | \`${deliveries.details}\` |
| deliveries | address | Adresse de livraison | \`${deliveries.address}\` |
| deliveries | informations | Informations supplémentaires sur la livraison | \`${deliveries.informations}\` |
| designations | priceHT | Prix HT de la désignation | \`${designations.priceHT}\` |
| - | distance | Distance pour la commande | \`${distance}\` |
| - | furnitureInsurance | Assurance meuble | \`${furnitureInsurance}\` |
| - | groupedOrSpecial | Indique si la commande est groupée ou spéciale | \`${groupedOrSpecial}\` |
| inventory | isEmpty | Indique si l'inventaire est vide | \`${inventory.isEmpty}\` |
| inventory | volume | Volume total de l'inventaire | \`${inventory.volume}\` |
| inventory | rooms | Pièces de l'inventaire avec articles | \`${inventory.rooms}\` |
| - | isOneOneStop | Indique si la commande a un seul point d'enlèvement et de livraison | \`${isOneOneStop}\` |
| - | logoUrl | URL du logo associé | \`${logoUrl}\` |
| pickups | date | Date du ramassage | \`${pickups.date}\` |
| pickups | details | Détails techniques du ramassage | \`${pickups.details}\` |
| pickups | address | Adresse de ramassage | \`${pickups.address}\` |
| pickups | informations | Informations supplémentaires sur le ramassage | \`${pickups.informations}\` |
| - | sequence | Numéro de séquence de la commande | \`${sequence}\` |
| - | signatureBase64 | Signature encodée en base64 | \`${signatureBase64}\` |
| - | signatureDate | Date de signature | \`${signatureDate}\` |
| taxes | totalTax | Montant total de la taxe | \`${taxes.totalTax}\` |
| - | totalArrhesTTC | Montant total de l'acompte TTC | \`${totalArrhesTTC}\` |
| - | totalBalanceTTC | Solde total TTC | \`${totalBalanceTTC}\` |
| - | totalHT | Montant total hors taxes | \`${totalHT}\` |
| - | totalTTC | Montant total toutes taxes comprises | \`${totalTTC}\` |
