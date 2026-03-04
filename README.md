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
    " Mchezo wa komborela una pande mbili anayejificha na anayetafuta Ukihusianisha na Biblia Mhusika wa kujificha ni nani, Mhusika wa kutafuta ni nani katiya Mungu na Wanadamu?",
    "Tunawezaje kumtafuta Mungu na kumuona?",
    "Tunathibitishaje kuwa Tunampenda Yesu?",
    "Kwa nini tumtafute Mungu? Taja Mstari wa Biblia",
    "Katika Mathayo 8:11-112 Imesemwa kwamba wengi watakuja kutoka mashariki na magharibi na kuchukua nafasi katika ufalme wa mbinguni na wahusika wa ufalme watatupwa nje katika giza, ambapo kutakuwa na kilio na kusaga meno,Wewe ni wa wapi?",
    "Mbingu ya kwanza na nchi ya kwanza zlikuwa zimepita na mbigu mpya na dunia mpya zikaumbwa( Ufu 21:1) Wewe ni wa wapi?",
     

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

