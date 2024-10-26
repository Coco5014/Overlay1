<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Classement des Donateurs</title>
  <style>
/* Style du tableau principal */
table {
  width: 100%;
  max-width: 600px;
  margin: auto;
  border-collapse: separate;
  border-spacing: 0;
  background-color: #ffffff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
  font-family: 'Arial', sans-serif;
}

/* Style pour l'en-tête */
table thead {
  background-color: #1f8ef1;
  color: #ffffff;
}

table thead th {
  padding: 12px 16px;
  font-size: 16px;
  font-weight: bold;
  text-align: left;
}

/* Style pour les lignes du corps du tableau */
table tbody tr {
  transition: background-color 0.3s;
}

table tbody tr:nth-child(even) {
  background-color: #f8f9fa; /* Ligne de couleur alternative */
}

table tbody tr:hover {
  background-color: #e9ecef; /* Effet survol */
}

/* Style pour les cellules */
table td {
  padding: 10px 16px;
  font-size: 15px;
  color: #333;
  text-align: left;
}

/* Style spécial pour le premier rang (meilleur donateur) */
table tbody tr:first-child {
  background-color: #ffeb3b;
  font-weight: bold;
}

table tbody tr:first-child:hover {
  background-color: #ffe082;
}

/* Bordures internes pour une apparence de séparation nette */
table td, table th {
  border-bottom: 1px solid #ddd;
}

/* Style d'arrondi des coins seulement en haut */
table thead th:first-child {
  border-top-left-radius: 8px;
}

table thead th:last-child {
  border-top-right-radius: 8px;
}

/* Dernière ligne sans bordure */
table tbody tr:last-child td {
  border-bottom: none;
}

  </style>
</head>
<body>
  <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTOuW9I45Zydtlh6vIOoR8ZMOBVZzgGfSv043l2svhPPcL5QFK8ybj7inwkyMjEfyyYILNUV4kaPl8c/pubhtml?gid=814304411&single=true" width="100%" height="100%" frameborder="0"></iframe>
</body>
</html>
