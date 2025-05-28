<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Présentation GSB Frais - Application Android</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      padding: 20px;
      background-color: #f8f9fa;
    }
    h2 {
      color: #2c3e50;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: left;
    }
    th {
      background-color: #007BFF;
      color: white;
    }
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    .note {
      background-color: #fff3cd;
      padding: 10px;
      border-left: 4px solid #ffeeba;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h2>🧬 Cas Galaxy Swiss Bourdin (GSB)</h2>
  <p>Le cas <strong>Galaxy Swiss Bourdin (GSB)</strong> est un projet pédagogique fréquemment utilisé dans les formations en informatique, notamment en <strong>BTS Services Informatiques aux Organisations (SIO)</strong>.</p>
  <p>Il simule la fusion de deux laboratoires pharmaceutiques, <em>Galaxy</em> et <em>Swiss Bourdin</em>, pour former une entité unique : <strong>Galaxy Swiss Bourdin</strong>.</p>
  <p>Cette fusion a mis en évidence la nécessité d’unifier et de moderniser les systèmes d’information, en particulier pour la gestion des <strong>frais professionnels des visiteurs médicaux</strong>.</p>

  <h2>📱 Objectif de l'application Android "GSB Frais"</h2>
  <p>L’application mobile <strong>GSB Frais</strong> a été développée pour permettre aux utilisateurs de gérer leurs frais professionnels directement depuis leur smartphone Android.</p>
  <p>Elle permet aux <strong>visiteurs médicaux</strong> de saisir leurs dépenses (déplacements, repas, hébergements, etc.), et aux <strong>comptables</strong> de consulter et traiter ces frais via un back-office connecté à l’API.</p>
  <p>Elle communique avec un serveur via des <strong>services web PHP</strong> pour accéder aux données à distance.</p>

  <h2>🧑‍💻 Fonctionnalités principales</h2>

  <h3>✅ Pour les visiteurs médicaux :</h3>
  <ul>
    <li>Saisie des frais forfaitisés et hors forfait.</li>
    <li>Ajout de justificatifs pour les frais hors forfait (photo du ticket, etc.).</li>
    <li>Consultation de l'état des fiches de frais (enregistré, validé, remboursé).</li>
    <li>Affichage du résumé des frais du mois.</li>
  </ul>

  <h3>💼 Pour les comptables :</h3>
  <ul>
    <li>Accès aux fiches saisies via le back-office web.</li>
    <li>Validation ou refus des frais soumis.</li>
    <li>Suivi des remboursements en coordination avec l’application web.</li>
  </ul>

  <h3>🔧 Pour les administrateurs :</h3>
  <ul>
    <li>Gestion des comptes utilisateurs.</li>
    <li>Supervision du système côté serveur (API PHP).</li>
  </ul>

  <h2>🔐 Identifiants de connexion</h2>
  <table>
    <thead>
      <tr>
        <th>Rôle</th>
        <th>Identifiant</th>
        <th>Mot de passe</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Visiteur</td>
        <td>churoro-b@gmail.com</td>
        <td>1</td>
      </tr>
      <tr>
        <td>Comptable</td>
        <td>feitan-m@gmail.com</td>
        <td>1</td>
      </tr>
      <tr>
        <td>Administrateur</td>
        <td>gon-i@gmail.com</td>
        <td>1</td>
      </tr>
    </tbody>
  </table>

  <div class="note">
    ⚠️ Ces identifiants sont utilisés dans les environnements de test ou de démonstration. Il est recommandé de les modifier pour des raisons de sécurité lors d'une mise en production.
  </div>

  <h2>🛠️ Technologies utilisées</h2>
  <ul>
    <li><strong>Langages :</strong> Java (Android), XML (interfaces), PHP (API)</li>
    <li><strong>Base de données :</strong> MySQL (côté serveur)</li>
    <li><strong>Outils :</strong> Android Studio, Postman, Visual Studio Code, GitHub</li>
  </ul>

</body>
</html>
