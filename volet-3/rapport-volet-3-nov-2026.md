# RAPPORT FINAL — VOLET 3
## Emails marketing et scénarios M1 à M5
**Projet :** simulation académique CRM HubSpot — portail 149685082  
**Date de mise à jour :** 13 novembre 2026  
**Statut :** 20 emails créés et contenus enregistrés en brouillon. Aucun envoi effectué.

> Ce projet est une simulation pédagogique indépendante. Il n'est pas affilié officiellement à Booking.com. Les noms de marque présents dans les maquettes servent uniquement au contexte académique.

## 1. Résultat global

- 20 emails de campagne présents dans HubSpot : 13 BATCH et 7 AUTOMATED.
- 20 emails au statut brouillon (DRAFT / AUTOMATED_DRAFT).
- 20 corps d'emails renseignés avec du HTML.
- Les visuels sont chargés depuis les fichiers GitHub existants.
- Chaque email comprend un objet, un texte d'aperçu, un titre, un texte principal et un CTA.
- Les emails comprennent le module de pied de page HubSpot avec liens de désabonnement et de préférences.
- Aucun destinataire n'a été affecté ; aucun envoi ni programmation n'a été réalisé.
- Les deux emails système de tickets (« Ticket received » et « Ticket closed ») sont conservés et exclus du périmètre.
- Le premier brouillon pilote « M1 · Réveillon · Votre escapade du Nouvel An » a été complété au lieu d'être supprimé.

## 2. Direction artistique appliquée

| Élément | Spécification |
|---|---|
| Bleu profond | #003B95 |
| Bleu principal | #0071C2 |
| Accent jaune | #FEBB02 |
| Fond | #F2F6FA |
| Texte | #1A1A1A |
| Typographie | Arial / Helvetica |
| Largeur cible | 600 px |
| Structure | Colonne unique, responsive |
| Style | Éditorial, premium, photographique |
| CTA | Bouton bleu, texte blanc, contraste fort |

La structure HTML repose sur des tableaux compatibles avec les clients email, avec un en-tête bleu, une image hero, un titre hiérarchisé, un texte court, un CTA, un encadré d'information et un accent jaune. Les images ne contiennent pas de texte intégré.

## 3. Bibliothèque visuelle GitHub réutilisée

Dépôt : https://github.com/manelkrichene/marketingisgtuniscrmbooking

**B2C**
- The Luxury Experience Seeker.jpg
- The Budget Optimizer.jpg
- The Business Traveler.jpg
- The Family Trip Planner.jpg
- The Spontaneous Explorer.jpg

**B2B**
- Hotel & Resort Partners.jpg
- Guesthouses & Property Managers.jpg
- Travel Agencies & Tour Operators.jpg
- Activities, Experiences & Leisure Providers.jpg

Les fichiers sources et le design system sont documentés dans :
- https://github.com/manelkrichene/marketingisgtuniscrmbooking/blob/main/volet-3/design-system.md
- https://github.com/manelkrichene/marketingisgtuniscrmbooking/tree/main/volet-3/email-designs

## 4. Détail des 20 emails

### M1 — Campagne du réveillon : fidélisation

| Email | Type | Objet |
|---|---|---|
| M1 · Réveillon · Votre escapade du Nouvel An | BATCH | Votre escapade du Nouvel An commence ici |
| M1 · Réveillon · Inspirations pour votre prochaine escapade | BATCH | Et si vous commenciez la nouvelle année ailleurs ? |
| M1 · Réveillon · Prolongez l’esprit des fêtes | BATCH | Le plaisir de voyager ne s’arrête pas au réveillon |

Objectif : entretenir l'intérêt des voyageurs et les inciter à explorer des idées de séjour pour le Nouvel An. Aucun email ne prétend qu'un contact a déjà réservé un réveillon, faute de preuve vérifiée dans les dossiers CRM.

### M2 — Guide « 10 destinations pour le Nouvel An » : acquisition et nurturing

| Email | Type | Objet |
|---|---|---|
| M2 · Guide · 10 destinations pour le Nouvel An | BATCH | 10 destinations pour accueillir la nouvelle année |
| M2 · Nurturing 1 · Votre guide est prêt | AUTOMATED | Votre guide des 10 destinations vous attend |
| M2 · Nurturing 2 · Choisir sa destination | AUTOMATED | Quelle destination correspond à votre envie de Nouvel An ? |
| M2 · Nurturing 3 · Préparer son séjour | AUTOMATED | De l’inspiration à votre prochain séjour |
| M2 · Guide · Escapades selon votre style | BATCH | Quel style d’escapade pour le Nouvel An ? |

Objectif : soutenir l'acquisition par le téléchargement du guide et nourrir l'intérêt jusqu'à la préparation d'un séjour.

**Dépendance non finalisée :** le PDF du guide et une URL de téléchargement réelle ne sont pas encore hébergés ou reliés. Les CTA actuels sont des liens de démonstration vers Booking.com et ne doivent pas être considérés comme des liens de téléchargement fonctionnels. La page de destination, le formulaire et le blog SEO ne sont pas créés dans cette opération.

### M3 — Relance de recherche abandonnée : conversion

| Email | Type | Objet |
|---|---|---|
| M3 · Recherche abandonnée · Reprendre votre recherche | AUTOMATED | Vous souhaitez reprendre votre recherche ? |
| M3 · Recherche abandonnée · Besoin d’inspiration ? | AUTOMATED | Encore à la recherche du bon séjour ? |

Objectif : encourager un visiteur à reprendre son projet de recherche. Les emails restent génériques : aucun historique de navigation ou de séjour consulté n'est injecté. Le déclenchement sur visite de page n'est pas opérationnel.

### M4 — Campagne B2B : séminaires d'entreprise

| Email | Type | Objet |
|---|---|---|
| M4 · Séminaires · Votre prochain séminaire d’entreprise | BATCH | Organisez votre prochain séminaire en toute sérénité |
| M4 · Séminaires · Accueillir des groupes | BATCH | Votre établissement peut-il accueillir un séminaire ? |
| M4 · Séminaires · Construire une offre de groupe | BATCH | Une offre claire pour les événements professionnels |
| M4 · Séminaires · Expériences pour les équipes | BATCH | Ajoutez une expérience à votre prochain séminaire |
| M4 · Séminaires · Demande de devis groupe | BATCH | Parlons de votre prochain événement professionnel |
| M4 · Séminaires · Préparer votre espace | BATCH | Votre espace est-il prêt pour un groupe professionnel ? |
| M4 · Séminaires · Collaboration et visibilité | BATCH | Faites connaître votre offre dédiée aux groupes |
| M4 · Séminaires · Dernière étape de votre demande | BATCH | Finalisons les informations de votre offre groupe |

Objectif : acquisition B2B auprès des décideurs d'entreprises qui organisent des séminaires. Les huit emails ont été corrigés pour s'adresser aux organisateurs d'événements et leur proposer de préparer une demande de devis groupe, plutôt qu'aux hôtels ou prestataires comme destinataires.

**Dépendances non finalisées :** aucune liste d'entreprises clientes ni aucun formulaire de demande de devis groupe n'a été créé ou relié. Les images réutilisées illustrent les types de lieux et d'expériences, pas des offres réellement disponibles. Les emails ne sont associés à aucun destinataire.

### M5 — Lead scoring : priorisation

| Email | Type | Objet |
|---|---|---|
| M5 · Scoring · Votre intérêt nous aide à mieux vous orienter | AUTOMATED | Quel contenu souhaitez-vous recevoir ensuite ? |
| M5 · Scoring · Signal d’intérêt commercial | AUTOMATED | Votre projet mérite un échange adapté |

Objectif : encourager des interactions explicites et recueillir des signaux d'intérêt mesurables. Les clics et réponses peuvent servir de signaux dans un modèle de scoring une fois les données disponibles. Les ouvertures seules ne sont pas considérées comme une preuve suffisante d'intention.

## 5. Paramètres HubSpot

- Expéditeur : Booking.com (nom d'affichage de la simulation).
- Adresse de réponse : krichenem@gmail.com.
- Type d'abonnement sélectionné : Marketing Information.
- Emails BATCH : 13.
- Emails AUTOMATED : 7.
- Destinataires : aucun.
- Programmation : aucune.
- Envois : aucun.
- Les emails AUTOMATED sont des brouillons de contenu destinés à une future séquence ; ils ne sont pas activés par un workflow.

## 6. Contrôles effectués

- Le premier email pilote a été modifié dans HubSpot, puis prévisualisé.
- La prévisualisation du pilote confirme un corps HTML non vide, le chargement de l'URL d'image GitHub, le CTA et le pied de page de désabonnement.
- Des prévisualisations ont été exécutées pour plusieurs emails représentatifs des scénarios M1, M2, M3, M4 et M5.
- Après correction, un email M4 a été prévisualisé à nouveau : image GitHub, objet et CTA de demande de devis présents.
- La recherche CRM finale retourne 20 emails de campagne au statut brouillon, plus les deux emails système conservés.
- Les 20 contenus ont été enregistrés avec succès dans HubSpot.

**Limite du contrôle :** les prévisualisations ont été contrôlées par échantillonnage, pas une à une pour les 20 emails. Les URLs GitHub sont intégrées dans les HTML et apparaissent dans les rendus HubSpot ; cela confirme leur présence dans le rendu, mais ne constitue pas un test de délivrabilité sur Gmail, Outlook ou mobile réel.

## 7. Fonctionnalités préparées mais non activées

| Fonctionnalité du scénario | État |
|---|---|
| Listes actives / segmentation | Segments CRM antérieurs disponibles, mais aucune nouvelle audience assignée à ces 20 emails |
| Campagnes HubSpot M1–M5 | Non créées/associées dans cette opération |
| Smart content par destination | Non activé |
| Test A/B de l'objet | Non configuré |
| Page de destination et formulaire M2 | Non créés |
| Guide téléchargeable | PDF/URL non relié |
| Blog et SEO M2 | Non créés |
| Suivi de navigation M3 | Non configuré |
| Workflow nurturing M2 | Emails AUTOMATED préparés, workflow non créé |
| Workflow de recherche abandonnée M3 | Non créé |
| Liste entreprises cibles M4 | Non créée |
| Formulaire devis groupe M4 | Non créé |
| Lead scoring M5 | Emails préparés, scoring automatique non activé |
| Workflows de qualification MQL | Non créés |

Le portail est utilisé en offre gratuite. Les fonctionnalités d'automatisation avancée, de smart content, de tests A/B et de lead scoring natif dépendent de niveaux d'abonnement et de permissions qui ne sont pas disponibles dans le cadre de cette simulation. Aucun résultat ne doit être présenté comme automatique ou mesuré tant que ces fonctions ne sont pas activées et que des données réelles ne sont pas collectées.

## 8. Conditions avant tout usage réel

1. Créer et héberger le PDF « 10 destinations pour le Nouvel An », puis remplacer le lien de démonstration.
2. Construire la page de destination, le formulaire et la page de confirmation.
3. Remplacer les CTA génériques par des URLs de destination fonctionnelles et vérifiées.
4. Créer les campagnes HubSpot M1–M5 et associer les emails pertinents.
5. Définir les listes et vérifier les consentements marketing et les exclusions.
6. Créer les audiences d'entreprises et le formulaire de devis groupe pour M4.
7. Vérifier le pied de page légal, l'adresse d'entreprise et les informations de l'expéditeur.
8. Prévisualiser chaque email sur desktop et mobile, puis réaliser un test d'envoi interne autorisé avant toute campagne réelle.
9. Ne déclencher les emails automatisés qu'après configuration et test des workflows.

## 9. Conclusion

Le livrable email du volet 3 est constitué : **20 emails brouillons, 20 contenus HTML renseignés, 13 BATCH et 7 AUTOMATED**, avec la charte graphique validée et les neuf images GitHub réutilisées.

Le volet 3 n'est toutefois pas une campagne opérationnelle : aucun email n'a été envoyé, aucune audience n'a été affectée, aucun workflow n'a été activé et plusieurs dépendances (guide PDF, page, formulaires, tracking et scoring) restent à construire. Les indicateurs d'ouverture, de clic, de conversion, de MQL et de réservations ne sont donc pas encore mesurables.
