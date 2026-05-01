# POLITIQUE RELATIVE AUX COOKIES, AU STOCKAGE LOCAL ET AUX IDENTIFIANTS PUBLICITAIRES

**Dernière mise à jour : 02/05/2026**

## 1. Préambule

Dans le contexte d'une application mobile, le terme "cookie" couvre un ensemble de technologies permettant de stocker ou de lire des informations sur votre appareil :

- **Stockage local** (AsyncStorage, Keychain iOS, Keystore Android)
- **Cache** des données et des cartes
- **Identifiants temporaires** (tokens d'authentification)
- **Identifiants publicitaires** (IDFA sur iOS, AAID sur Android)

Cette politique détaille comment **LovMap** utilise ces technologies et quels sont vos droits.

## 2. Catégories de traceurs utilisés

### 2.1. Traceurs strictement nécessaires (sans consentement)

Ces éléments sont indispensables au fonctionnement de l'Application. Ils ne nécessitent pas votre consentement préalable conformément à l'article 82 de la loi Informatique et Libertés.

| Élément stocké | Finalité | Durée |
|---|---|---|
| Token d'authentification (Supabase) | Vous maintenir connecté entre 2 ouvertures | Jusqu'à déconnexion ou révocation |
| Préférences utilisateur (langue, thème) | Mémoriser vos choix de configuration | Permanent (effaçable) |
| Cache des cartes (Mapbox) | Accélérer le chargement des cartes déjà visitées | Variable (géré par l'OS) |
| ID Push Notification (Expo) | Vous envoyer des notifications | Tant que vous restez connecté |

Ces traceurs ne sont **jamais partagés à des tiers à des fins commerciales** et ne servent qu'au bon fonctionnement du Service.

### 2.2. Traceurs publicitaires (avec consentement)

L'Application affiche des publicités via **Google AdMob**. Sur iOS 14.5+, conformément aux règles d'Apple (App Tracking Transparency / ATT), une fenêtre vous demande explicitement votre consentement avant d'utiliser l'identifiant publicitaire de votre appareil.

| Identifiant | Finalité | Quand utilisé |
|---|---|---|
| **IDFA** (iOS) | Personnaliser les publicités, mesurer leur efficacité | Uniquement si vous avez accepté la fenêtre ATT |
| **AAID** (Android) | Idem | Selon vos paramètres Google Play |

**Si vous refusez :**
- Vous continuerez à voir des publicités, mais elles seront **non personnalisées** (générées sans utiliser votre IDFA).
- Aucun identifiant publicitaire n'est transmis à Google AdMob.
- Les revenus publicitaires sont moindres pour LovMap, mais le service reste 100 % gratuit.

**Si vous acceptez :**
- Google AdMob peut utiliser l'IDFA/AAID pour vous proposer des publicités plus pertinentes.
- AdMob peut mesurer la performance des publicités (clics, conversions).
- Aucune autre donnée personnelle n'est partagée avec les annonceurs.

### 2.3. Traceurs de monitoring (intérêt légitime)

L'Application utilise **Sentry** pour collecter automatiquement les rapports d'erreurs en cas de crash. Ces rapports contiennent :
- La stack trace du code (lignes de code à l'origine du bug)
- Le contexte technique (modèle, OS, version de l'Application)
- **Aucune donnée personnelle identifiable** (ni email, ni mot de passe, ni messages, ni géolocalisation précise)

Ce traitement repose sur **l'intérêt légitime** de l'Éditeur (article 6.1.f du RGPD) consistant à corriger les bugs et améliorer la stabilité du Service. Vous pouvez vous y opposer en nous contactant à kevinzunigamora@icloud.com.

## 3. Gestion de vos préférences

### 3.1. Identifiant publicitaire (IDFA)

**Sur iOS :**
1. Ouvrez **Réglages → Confidentialité et sécurité → Suivi**
2. Recherchez "LovMap" dans la liste
3. Activez ou désactivez le suivi à votre convenance

Vous pouvez aussi désactiver le suivi globalement pour toutes les applications via **Réglages → Confidentialité et sécurité → Suivi → Autoriser les apps à demander à suivre vos activités**.

**Sur Android :**
1. Ouvrez **Paramètres → Google → Annonces**
2. Activez "Désactiver les annonces personnalisées"
3. Vous pouvez aussi réinitialiser votre identifiant publicitaire à tout moment

### 3.2. Notifications push

**Sur iOS :** Réglages → Notifications → LovMap → désactiver
**Sur Android :** Paramètres → Applications → LovMap → Notifications → désactiver

### 3.3. Effacer toutes les données stockées

Désinstaller l'Application supprime automatiquement toutes les données stockées localement sur votre appareil (token, cache, préférences). Cela ne supprime pas les données stockées sur nos serveurs — pour cela, utilisez la fonction **Profil → Supprimer mon compte**.

## 4. Pas de cookies traditionnels

L'Application étant native (iOS / Android) et non un site web, **les cookies HTTP traditionnels ne sont pas utilisés**. Seuls les mécanismes décrits ci-dessus s'appliquent.

Notre **site web** (https://keviinzm.github.io/lovmap-legal/) ne dépose aucun cookie hors ceux strictement nécessaires (techniques) à son fonctionnement et au service GitHub Pages.

## 5. Mises à jour de cette politique

Cette politique peut être mise à jour pour refléter les évolutions techniques ou réglementaires. La date de "Dernière mise à jour" en haut du document indique la version en vigueur.

---

**Contact :**
Kévin Zuniga — kevinzunigamora@icloud.com
Site légal : https://keviinzm.github.io/lovmap-legal/
