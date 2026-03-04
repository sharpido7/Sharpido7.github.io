<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Random Question</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-white d-flex align-items-center justify-content-center vh-100">

<div class="container text-center">
    <div class="card shadow-lg p-4 bg-light text-dark">
        <h3 class="mb-4">🤔 Your Question Is:</h3>
        <h2 id="question"></h2>
       
    </div>
</div>

<script>
const questions = [
   "1","2","3","4"
     

];

function newQuestion() {
    const randomIndex = Math.floor(Math.random() * questions.length);
    document.getElementById("question").innerText = questions[randomIndex];
}

// Show a question immediately when page loads
newQuestion();
</script>

</body>
</html>

