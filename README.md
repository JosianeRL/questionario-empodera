<!DOCTYPE html>
<html lang="pt-BR">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Empodera Solidário | Violência Digital</title>

<style>

/* =========================
   CONFIGURAÇÕES GERAIS
========================= */

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #faf7fb;
    color: #333;
    min-height: 100vh;
}


/* =========================
   CABEÇALHO
========================= */

.header {
    background: #ffffff;
    padding: 18px 30px;
    border-bottom: 1px solid #eee;
}

.header-content {
    max-width: 1100px;
    margin: auto;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    color: #7b3f78;
    font-size: 22px;
    font-weight: bold;
    letter-spacing: 0.5px;
}

.header-link {
    color: #7b3f78;
    text-decoration: none;
    font-size: 14px;
}


/* =========================
   ÁREA PRINCIPAL
========================= */

.main {
    max-width: 900px;
    margin: 50px auto;
    padding: 0 20px;
}


/* =========================
   TÍTULO
========================= */

.title-area {
    text-align: center;
    margin-bottom: 35px;
}

.title-area h1 {
    color: #5d315a;
    font-size: 32px;
    margin-bottom: 15px;
}

.title-area p {
    max-width: 650px;
    margin: auto;
    color: #666;
    font-size: 16px;
    line-height: 1.6;
}


/* =========================
   CARD PRINCIPAL
========================= */

.card {
    background: white;
    border-radius: 22px;
    padding: 40px;
    box-shadow: 0 5px 25px rgba(86, 48, 84, 0.08);
}


/* =========================
   INTRODUÇÃO
========================= */

.intro {
    text-align: center;
}

.intro-icon {
    width: 70px;
    height: 70px;

    margin: 0 auto 20px;

    border-radius: 50%;

    background: #f1e5f1;

    display: flex;
    align-items: center;
    justify-content: center;

    font-size: 32px;
}

.intro h2 {
    color: #5d315a;
    font-size: 25px;
    margin-bottom: 15px;
}

.intro p {
    color: #666;
    line-height: 1.6;
    margin-bottom: 25px;
}


/* =========================
   AVISO
========================= */

.notice {
    background: #faf3fa;

    border-left: 4px solid #8d5a89;

    border-radius: 8px;

    padding: 16px;

    text-align: left;

    color: #555;

    font-size: 14px;

    line-height: 1.5;

    margin-bottom: 28px;
}


/* =========================
   BOTÕES
========================= */

.btn-primary {
    background: #7b3f78;

    color: white;

    border: none;

    border-radius: 10px;

    padding: 15px 30px;

    font-size: 16px;

    font-weight: bold;

    cursor: pointer;

    transition: 0.2s;
}

.btn-primary:hover {
    background: #653263;
}


/* =========================
   QUESTIONÁRIO
========================= */

.quiz {
    display: none;
}


/* PROGRESSO */

.progress-info {
    display: flex;

    justify-content: space-between;

    color: #777;

    font-size: 14px;

    margin-bottom: 8px;
}

.progress-container {
    width: 100%;

    height: 8px;

    background: #eee;

    border-radius: 10px;

    overflow: hidden;

    margin-bottom: 35px;
}

.progress {
    height: 100%;

    background: #7b3f78;

    width: 0%;

    transition: width 0.4s ease;
}


/* PERGUNTA */

.question-number {
    color: #8d5a89;

    font-size: 14px;

    font-weight: bold;

    margin-bottom: 10px;
}

.question {
    color: #4f2d4c;

    font-size: 24px;

    line-height: 1.4;

    margin-bottom: 18px;
}

.example {
    color: #666;

    background: #f8f5f8;

    border-radius: 10px;

    padding: 15px;

    font-size: 14px;

    line-height: 1.5;

    margin-bottom: 25px;
}


/* =========================
   RESPOSTAS
========================= */

.options {
    display: flex;

    flex-direction: column;

    gap: 12px;
}

.option {
    background: white;

    border: 2px solid #e1dce1;

    border-radius: 12px;

    padding: 16px;

    text-align: left;

    font-size: 16px;

    color: #444;

    cursor: pointer;

    transition: 0.2s;
}

.option:hover {
    border-color: #9b6a98;

    background: #fbf7fb;
}

.option.selected {
    border-color: #7b3f78;

    background: #f2e8f2;

    color: #5d315a;

    font-weight: bold;
}


/* =========================
   NAVEGAÇÃO
========================= */

.navigation {
    display: flex;

    justify-content: space-between;

    align-items: center;

    margin-top: 30px;
}

.btn-back {
    background: transparent;

    border: none;

    color: #777;

    font-size: 15px;

    cursor: pointer;
}

.btn-next {
    background: #7b3f78;

    color: white;

    border: none;

    border-radius: 9px;

    padding: 13px 24px;

    font-weight: bold;

    cursor: pointer;
}


/* =========================
   RESULTADO
========================= */

.result {
    display: none;

    text-align: center;
}

.result-icon {
    width: 75px;

    height: 75px;

    border-radius: 50%;

    background: #f1e5f1;

    margin: 0 auto 20px;

    display: flex;

    align-items: center;

    justify-content: center;

    font-size: 34px;
}

.result h2 {
    color: #5d315a;

    font-size: 28px;

    margin-bottom: 15px;
}

.result-intro {
    color: #666;

    line-height: 1.6;

    margin-bottom: 25px;
}


/* =========================
   ORIENTAÇÕES
========================= */

.orientation {
    text-align: left;

    background: #faf7fb;

    border-radius: 15px;

    padding: 25px;

    margin-bottom: 20px;
}

.orientation h3 {
    color: #7b3f78;

    margin-bottom: 18px;
}

.orientation-item {
    display: flex;

    gap: 14px;

    margin-bottom: 18px;
}

.orientation-icon {
    width: 40px;

    height: 40px;

    min-width: 40px;

    background: #eee2ee;

    border-radius: 50%;

    display: flex;

    align-items: center;

    justify-content: center;
}

.orientation-item strong {
    color: #5d315a;

    display: block;

    margin-bottom: 4px;
}

.orientation-item p {
    color: #666;

    font-size: 14px;

    line-height: 1.5;
}


/* =========================
   EMERGÊNCIA
========================= */

.emergency {
    background: #fff4f4;

    border: 1px solid #f0cccc;

    border-radius: 12px;

    padding: 20px;

    text-align: left;

    margin-bottom: 25px;
}

.emergency h3 {
    color: #a52a2a;

    margin-bottom: 8px;
}

.emergency p {
    color: #555;

    font-size: 14px;

    line-height: 1.5;
}

.emergency-number {
    font-size: 22px;

    font-weight: bold;

    color: #a52a2a;
}


/* =========================
   RODAPÉ
========================= */

.footer {
    text-align: center;

    color: #888;

    font-size: 12px;

    line-height: 1.5;

    margin-top: 25px;
}


/* =========================
   CELULAR
========================= */

@media (max-width: 600px) {

    .header {
        padding: 16px;
    }

    .main {
        margin: 30px auto;
    }

    .card {
        padding: 25px 20px;

        border-radius: 16px;
    }

    .title-area h1 {
        font-size: 25px;
    }

    .question {
        font-size: 20px;
    }

    .navigation {
        gap: 10px;
    }

    .btn-next {
        padding: 12px 18px;
    }

}

</style>

</head>


<body>


<!-- =========================
     CABEÇALHO
========================= -->

<header class="header">

    <div class="header-content">

        <div class="logo">
            EMPODERA SOLIDÁRIO
        </div>

        <a href="#" class="header-link">
            Apoio e informação
        </a>

    </div>

</header>



<!-- =========================
     CONTEÚDO
========================= -->

<main class="main">


    <div class="title-area">

        <h1>
            Violência Digital
        </h1>

        <p>
            Um espaço para você entender melhor o que está acontecendo
            e conhecer caminhos para buscar apoio.
        </p>

    </div>


    <div class="card">


        <!-- INTRODUÇÃO -->

        <section class="intro" id="intro">

            <div class="intro-icon">
                💜
            </div>

            <h2>
                Você está passando por uma situação de violência digital?
            </h2>

            <p>
                Responda algumas perguntas para identificar situações
                que podem estar relacionadas à violência digital.
            </p>

            <div class="notice">

                <strong>Este questionário é confidencial.</strong>

                <br>

                Nenhuma resposta é enviada ou armazenada.
                Ele serve apenas como uma orientação inicial.

            </div>

            <button
                class="btn-primary"
                onclick="startQuiz()">

                COMEÇAR QUESTIONÁRIO

            </button>

        </section>



        <!-- QUESTIONÁRIO -->

        <section class="quiz" id="quiz">


            <div class="progress-info">

                <span id="progressText">
                    Pergunta 1 de 7
                </span>

                <span id="progressPercent">
                    14%
                </span>

            </div>


            <div class="progress-container">

                <div
                    class="progress"
                    id="progress">
                </div>

            </div>


            <div class="question-number">

                PERGUNTA

            </div>


            <h2
                class="question"
                id="question">
            </h2>


            <div
                class="example"
                id="example">
            </div>


            <div
                class="options"
                id="options">

                <button
                    class="option"
                    onclick="selectAnswer(2, this)">

                    Sim

                </button>


                <button
                    class="option"
                    onclick="selectAnswer(1, this)">

                    Não tenho certeza

                </button>


                <button
                    class="option"
                    onclick="selectAnswer(0, this)">

                    Não

                </button>

            </div>


            <div class="navigation">

                <button
                    class="btn-back"
                    onclick="previousQuestion()">

                    ← Voltar

                </button>


                <button
                    class="btn-next"
                    onclick="nextQuestion()">

                    Próxima →

                </button>

            </div>


        </section>



        <!-- RESULTADO -->

        <section
            class="result"
            id="result">


            <div class="result-icon">
                💜
            </div>


            <h2>
                Você não está sozinha
            </h2>


            <p
                class="result-intro"
                id="resultText">
            </p>



            <div class="orientation">

                <h3>
                    O que você pode fazer?
                </h3>


                <div class="orientation-item">

                    <div class="orientation-icon">
                        📸
                    </div>

                    <div>

                        <strong>
                            Guarde as provas
                        </strong>

                        <p>
                            Faça prints de mensagens, publicações,
                            perfis, links e ameaças.
                        </p>

                    </div>

                </div>


                <div class="orientation-item">

                    <div class="orientation-icon">
                        🔐
                    </div>

                    <div>

                        <strong>
                            Proteja suas contas
                        </strong>

                        <p>
                            Troque suas senhas e ative a verificação
                            em duas etapas.
                        </p>

                    </div>

                </div>


                <div class="orientation-item">

                    <div class="orientation-icon">
                        🚫
                    </div>

                    <div>

                        <strong>
                            Denuncie
                        </strong>

                        <p>
                            Utilize as ferramentas de denúncia da
                            rede social ou aplicativo.
                        </p>

                    </div>

                </div>


                <div class="orientation-item">

                    <div class="orientation-icon">
                        🤝
                    </div>

                    <div>

                        <strong>
                            Procure apoio
                        </strong>

                        <p>
                            Converse com alguém de confiança e procure
                            um serviço especializado de atendimento à mulher.
                        </p>

                    </div>

                </div>

            </div>



            <div class="emergency">

                <h3>
                    🚨 Está em perigo agora?
                </h3>

                <p>

                    Em uma situação de emergência,
                    procure um local seguro e ligue:

                    <br><br>

                    <span class="emergency-number">
                        190
                    </span>

                    <br>

                    Polícia Militar

                    <br><br>

                    Para orientação e informações sobre
                    serviços de atendimento à mulher:

                    <br><br>

                    <span class="emergency-number">
                        180
                    </span>

                </p>

            </div>


            <button
                class="btn-primary"
                onclick="restartQuiz()">

                RESPONDER NOVAMENTE

            </button>


            <div class="footer">

                Este questionário oferece orientação inicial
                e não substitui atendimento profissional.

            </div>


        </section>


    </div>

</main>



<script>


/* =========================
   PERGUNTAS
========================= */

const questions = [

    {
        question:
        "Alguém está enviando mensagens que fazem você se sentir ameaçada, com medo ou intimidada?",

        example:
        "Por exemplo: mensagens ameaçando machucar você, sua família ou divulgar informações pessoais."
    },

    {
        question:
        "Alguém está perseguindo ou monitorando você pela internet?",

        example:
        "Por exemplo: cria novas contas depois de ser bloqueado, acompanha constantemente suas redes ou envia muitas mensagens."
    },

    {
        question:
        "Alguém compartilhou ou ameaçou compartilhar fotos ou vídeos íntimos seus sem sua autorização?",

        example:
        "Por exemplo: alguém ameaça publicar ou envia para outras pessoas uma imagem íntima que você compartilhou em particular."
    },

    {
        question:
        "Alguém está usando a internet para humilhar, ofender ou espalhar informações sobre você?",

        example:
        "Por exemplo: publicar comentários ofensivos, boatos ou informações para prejudicar sua imagem."
    },

    {
        question:
        "Alguém tenta controlar suas redes sociais, celular, senhas ou com quem você conversa?",

        example:
        "Por exemplo: exigir suas senhas, verificar suas conversas ou controlar quem você pode seguir e conversar."
    },

    {
        question:
        "Você recebeu ameaças relacionadas à divulgação de informações, fotos ou conversas pessoais?",

        example:
        "Por exemplo: alguém diz que vai divulgar suas conversas ou imagens caso você não faça o que essa pessoa quer."
    },

    {
        question:
        "Essa situação está fazendo você sentir medo, insegurança, vergonha ou sofrimento emocional?",

        example:
        "Se a situação está afetando seu bem-estar ou fazendo você se sentir insegura, você pode procurar apoio."
    }

];


let currentQuestion = 0;

let answers = [];



/* =========================
   INICIAR
========================= */

function startQuiz() {

    document.getElementById("intro").style.display = "none";

    document.getElementById("quiz").style.display = "block";

    showQuestion();

}



/* =========================
   MOSTRAR PERGUNTA
========================= */

function showQuestion() {

    const question = questions[currentQuestion];


    document.getElementById("question").textContent =
        question.question;


    document.getElementById("example").textContent =
        question.example;


    const number =
        currentQuestion + 1;


    document.getElementById("progressText").textContent =
        "Pergunta " + number +
        " de " +
        questions.length;


    const percentage =
        Math.round(
            (number / questions.length) * 100
        );


    document.getElementById("progressPercent").textContent =
        percentage + "%";


    document.getElementById("progress").style.width =
        percentage + "%";


    const options =
        document.querySelectorAll(".option");


    options.forEach(function(option) {

        option.classList.remove("selected");

    });


    if (answers[currentQuestion] !== undefined) {

        const selected =
            answers[currentQuestion];


        if (selected === 2) {
            options[0].classList.add("selected");
        }

        if (selected === 1) {
            options[1].classList.add("selected");
        }

        if (selected === 0) {
            options[2].classList.add("selected");
        }

    }

}



/* =========================
   SELECIONAR RESPOSTA
========================= */

function selectAnswer(value, button) {

    answers[currentQuestion] = value;


    const options =
        document.querySelectorAll(".option");


    options.forEach(function(option) {

        option.classList.remove("selected");

    });


    button.classList.add("selected");

}



/* =========================
   PRÓXIMA
========================= */

function nextQuestion() {

    if (
        answers[currentQuestion] === undefined
    ) {

        alert(
            "Escolha uma opção antes de continuar."
        );

        return;

    }


    if (
        currentQuestion <
        questions.length - 1
    ) {

        currentQuestion++;

        showQuestion();

    }

    else {

        showResult();

    }

}



/* =========================
   VOLTAR
========================= */

function previousQuestion() {

    if (currentQuestion > 0) {

        currentQuestion--;

        showQuestion();

    }

}



/* =========================
   RESULTADO
========================= */

function showResult() {

    document.getElementById("quiz").style.display =
        "none";


    document.getElementById("result").style.display =
        "block";


    const yesAnswers =
        answers.filter(
            function(answer) {

                return answer === 2;

            }
        ).length;


    let text;


    if (yesAnswers >= 3) {

        text =
        "Algumas das situações relatadas podem estar relacionadas a formas de violência digital. É importante preservar as provas e considerar buscar orientação de um serviço especializado.";

    }

    else if (yesAnswers >= 1) {

        text =
        "Algumas situações relatadas merecem atenção. Mesmo que você não tenha certeza sobre o que está acontecendo, você pode buscar orientação e conversar com alguém de confiança.";

    }

    else {

        text =
        "Nenhuma das situações apresentadas foi identificada nas suas respostas. Se algo mudar ou se você estiver se sentindo insegura, procure apoio.";

    }


    document.getElementById("resultText").textContent =
        text;

}



/* =========================
   REINICIAR
========================= */

function restartQuiz() {

    currentQuestion = 0;

    answers = [];


    document.getElementById("result").style.display =
        "none";


    document.getElementById("intro").style.display =
        "block";

}

</script>


</body>

</html>
