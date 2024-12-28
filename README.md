# Finazza1-
Application gestion financière 
# Création de la structure des fichiers
mkdir css js images
touch index.html css/style.css js/app.js README.md

# Ajout du contenu dans README.md
echo "# Finazza - Application de Gestion Financière" > README.md
echo "Gérez vos finances personnelles simplement." >> README.md

# Création du fichier index.html
cat > index.html << 'EOL'
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finazza</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="css/style.css" rel="stylesheet">
</head>
<body class="bg-gray-50">
    <div id="app">
        <header class="bg-white shadow-md">
            <div class="max-w-7xl mx-auto px-4 py-6">
                <h1 class="text-3xl font-bold text-blue-600">Finazza</h1>
            </div>
        </header>
        <main class="max-w-7xl mx-auto px-4 py-8">
            <div class="bg-white rounded-xl shadow-lg p-6">
                <h2 class="text-2xl font-bold mb-4">Gérez vos finances</h2>
                <p class="text-gray-600 mb-4">
                    Application simple et efficace pour gérer votre budget.
                </p>
                <button class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700">
                    Commencer
                </button>
            </div>
        </main>
    </div>
    <script src="js/app.js"></script>
</body>
</html>
EOL

Status : ✓ FICHIERS CRÉÉS
