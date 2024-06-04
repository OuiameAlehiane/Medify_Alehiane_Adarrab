![Cover](https://github.com/aritra-tech/Medify/assets/62587060/7a8cbbf3-d1c9-4e2f-8a6b-fb480a0714d5)


# Medify 💊
Medify est une application médicale Android qui traite et résout les problèmes des patients et des médecins. 

## Installation d'applications

***Vous pouvez installer et tester la dernière application Medify ci-dessous 👇***

[![Medify](https://img.shields.io/badge/Medify✅-APK-red.svg?style=for-the-badge&logo=android)](https://github.com/aritra-tech/Medify/releases/tag/1.0.0)

[Want to try the app](https://appetize.io/app/oqjrqtjcckwae4lsnghggdonpi?device=pixel4&osVersion=11.0&scale=50)

# Notre idée 💡
- Medify est une application Android qui résout non seulement le problème des patients en tant qu'utilisateurs, mais aussi celui des médecins.

- L'application propose aux utilisateurs de prendre rendez-vous avec le médecin déjà enregistré dans l'application..

- La file d'attente est triée selon la priorité et non selon le principe « premier arrivé, premier servi », ce qui permet à tous les patients d'avoir la même priorité.

- Les utilisateurs peuvent télécharger leur ordonnance qui ne conserve que le dernier téléchargement que le médecin peut vérifier.

- Les utilisateurs peuvent surveiller leurs données de santé qui sont affichées dans un graphique des 5 dernières données de leur rapport.

# Fonctionnalités de l'application🎯

- <b>Prise de rendez-vous :</b> L'utilisateur peut rechercher des médecins par leur nom, leur téléphone ou leur e-mail pour prendre rendez-vous.
Les utilisateurs doivent répondre à quelques questions concernant leur problème, de cette façon le rendez-vous est pris.
- <b>Tri des rendez-vous :</b> Nous avons conçu un algorithme qui analyse les données utilisateur, effectue des calculs et trie la file d'attente des patients en fonction de la priorité. 
De cette façon, chaque patient bénéficie d’une priorité égale.
- <b>Prescription:</b> L'utilisateur télécharge sa dernière prescription dans l'application. Ainsi, lors de la prise de rendez-vous, le médecin peut vérifier sa récente prescription. 
ordonnance et donc avoir une ordonnance n’est pas nécessaire.
- <b>Statistics:</b> L'utilisateur peut ajouter et surveiller ses 5 dernières données de rapports de santé qui sont affichées à l'aide de graphiques.
- <b>Instant UPI:</b> Lorsqu'on les interroge sur le montant des honoraires, cela semble tout à fait peu professionnel de la part des médecins lorsqu'ils doivent en parler. 
Mais à partir de maintenant, le médecin peut ajouter le détail de ses honoraires et l'application génère elle-même un code QR.
- <b>Liste de rendez-vous / file d'attente des patients :</b> Les utilisateurs peuvent consulter leur liste de rendez-vous de tous les médecins avec lesquels ils ont pris rendez-vous. 
La file d'attente des patients est une liste triée à l'aide de notre algorithme et affichée. 

## 📸 Captures d'écran

|   |   |   |
|---|---|---|
| ![1](https://github.com/aritra-tech/Medify/assets/62587060/57983983-452f-40cc-a1e6-5bea3de252f6) | ![2](https://github.com/aritra-tech/Medify/assets/62587060/fe897a3e-7a73-497c-a15b-fc1ed4737625) | ![3](https://github.com/aritra-tech/Medify/assets/62587060/b095a832-e2ce-4748-8bb4-89f102f5853d)
| ![4](https://github.com/aritra-tech/Medify/assets/62587060/61f0a2c0-7499-4c33-b3aa-ebdc8fab2487) | ![5](https://github.com/aritra-tech/Medify/assets/62587060/9e4b7d0a-aa6a-4954-afef-257c80fd6487) | ![6](https://github.com/aritra-tech/Medify/assets/62587060/665ae932-e1ee-4dcb-8c83-b5a4ce74150f)


# Construit avec🔩

- <b>[Kotlin](https://kotlinlang.org/docs/android-overview.html)</b> - We developed this project using kotlin in backend & XML to implement designs into code.
The app was developed in [Android Studio](https://developer.android.com/studio). We have also used some open source libraries like [ZXing for QR Code](https://github.com/zxing/zxing), [Chart](https://github.com/majorkik/SparkLineLayout) and some [UI libraries](https://material.io/).
- <b>[Java](https://developer.android.com/guide)</b> - As Java and Kotlin are interoperable, we used a Java class that encrypts the user data while saving in the app storage using <b>AES Encryption</b>. This way we prevent anydata leak.
- <b>[Firebase](https://firebase.google.com/docs/android/setup)</b> - Firebase is a free tool for developers so we used it to authenticate users using their email and perform similar operations. We also used firebase to store user data as well as their appointment details, and etc.
Not only that, we also used firebase to store docs that are uploaded by the  users (Prescriptions).
- <b>[Figma](https://www.figma.com/)</b> - We used Figma to design the UI / UX during the designing & prototyping phase of our project.
The design we used is minimal as well as clean. People with colorbindness will have no issues using it.
- <b>[Coroutines](https://kotlinlang.org/docs/coroutines-overview.html)</b> - For asynchronous calls and tasks to utilize threads.
- <b>[Android Architecture Components](https://developer.android.com/topic/architecture)</b> - Collection of libraries that help you design testable, and maintainable apps.
  - <b>[ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)</b> - Stores UI-related data that isn't destroyed on UI changes.
  - <b>[ViewBinding](https://developer.android.com/topic/libraries/view-binding)</b> - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
  - <b>[LiveData](https://developer.android.com/topic/libraries/architecture/livedata)</b> - LiveData was used to save and store values for viewModel calls and response of method calls.
  - <b>[Navigation Components](https://developer.android.com/guide/navigation/get-started)</b> - Navigation Component was used to navigate between fragments and pass parcelable objects
- <b>[Material Components for Android](https://github.com/material-components/material-components-android)</b> - Material Components for Android (MDC-Android) help developers execute Material Design. Developed by a core team of engineers and UX designers at Google, these components enable a reliable development workflow to build beautiful and functional Android apps.
- <b>[ZXing - QR Code Generator](https://github.com/zxing/zxing)</b> - ZXing's QR Code generator library to generate QR Code from Strings.


# Flow of the Application 🔧
![Medify (1) 1](https://user-images.githubusercontent.com/80090908/189736871-99886e3d-6c44-486b-8ee5-2dcc980526ad.png)

  

![ForTheBadge ANDROID](https://forthebadge.com/images/badges/built-for-android.svg)
![ForTheBadge GIT](https://forthebadge.com/images/badges/uses-git.svg)
