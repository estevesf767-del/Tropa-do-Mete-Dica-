<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>⚔️ Tropa do Mete Dica ⚔️</title>

<meta name="description" content="Tropa do Mete Dica — União, respeito, lealdade, disciplina e evolução. Juntos somos mais fortes.">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #070707;
    color: white;
}

/* CABEÇALHO */
header {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 30px 20px;
    background:
        radial-gradient(circle at center, #5c0000 0%, #160000 35%, #070707 75%);
}

.hero {
    max-width: 900px;
}

.logo {
    width: 130px;
    height: 130px;
    margin: 0 auto 25px;
    border: 4px solid #d00000;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 55px;
    box-shadow: 0 0 35px #b00000;
}

h1 {
    font-size: clamp(38px, 8vw, 75px);
    color: #fff;
    text-shadow: 0 0 20px #d00000;
}

.hero p {
    margin-top: 15px;
    font-size: 20px;
    color: #ddd;
}

.btn {
    display: inline-block;
    margin-top: 30px;
    padding: 14px 28px;
    border-radius: 30px;
    background: #c00000;
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: .3s;
}

.btn:hover {
    transform: scale(1.05);
    background: #ed0000;
}

/* SEÇÕES */
section {
    padding: 70px 20px;
}

.container {
    max-width: 1100px;
    margin: auto;
}

.title {
    text-align: center;
    font-size: 35px;
    margin-bottom: 45px;
    color: #ff2020;
}

/* SOBRE */
.about {
    text-align: center;
    max-width: 850px;
    margin: auto;
    line-height: 1.8;
    font-size: 18px;
}

.mission {
    margin-top: 30px;
    padding: 25px;
    border-left: 4px solid #d00000;
    background: #111;
    border-radius: 10px;
}

/* MEMBROS */
.members {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 25px;
}

.member {
    background: linear-gradient(145deg, #151515, #090909);
    border: 1px solid #520000;
    border-radius: 18px;
    padding: 30px 20px;
    text-align: center;
    transition: .3s;
}

.member:hover {
    transform: translateY(-8px);
    border-color: #e00000;
    box-shadow: 0 0 25px #420000;
}

.avatar {
    width: 100px;
    height: 100px;
    margin: auto;
    border-radius: 50%;
    background: #1d1d1d;
    border: 3px solid #c00000;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 38px;
}

.member h3 {
    margin-top: 20px;
    font-size: 22px;
}

.member p {
    color: #aaa;
    margin: 10px 0 20px;
}

.social {
    display: inline-block;
    margin: 5px;
    padding: 9px 14px;
    border-radius: 20px;
    background: #8d0000;
    color: white;
    text-decoration: none;
    font-size: 14px;
}

/* VALORES */
.values {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
}

.value {
    padding: 15px 22px;
    background: #111;
    border: 1px solid #650000;
    border-radius: 30px;
}

/* FRASE */
.quote {
    text-align: center;
    padding: 70px 20px;
    background: linear-gradient(135deg, #180000, #050505);
}

.quote h2 {
    font-size: clamp(28px, 6vw, 50px);
    color: #fff;
}

.quote span {
    color: #ff2020;
}

/* RODAPÉ */
footer {
    text-align: center;
    padding: 35px 20px;
    background: #030303;
    color: #888;
}

footer strong {
    color: #e00000;
}

/* RESPONSIVO */
@media (max-width: 600px) {
    .hero p {
        font-size: 16px;
    }

    section {
        padding: 55px 15px;
    }
}
</style>
</head>

<body>

<!-- CAPA -->
<header>
    <div class="hero">

        <div class="logo">⚔️</div>

        <h1>TROPA DO METE DICA</h1>

        <p>
            🖤 Mais que uma tropa, somos uma família. 🔴
        </p>

        <a href="#sobre" class="btn">
            CONHECER A TROPA
        </a>

    </div>
</header>


<!-- SOBRE -->
<section id="sobre">
    <div class="container">

        <h2 class="title">⚔️ Sobre a Tropa</h2>

        <div class="about">

            <p>
                A <strong>Tropa do Mete Dica</strong> é uma comunidade
                formada por quatro membros.
            </p>

            <div class="mission">

                <p>
                    📌 Nossa missão é crescer juntos, compartilhar ideias,
                    criar momentos e fortalecer a amizade.
                </p>

            </div>

        </div>

    </div>
</section>


<!-- MEMBROS -->
<section>
    <div class="container">

        <h2 class="title">👥 Os Membros</h2>

        <div class="members">

            <!-- ONACH -->
            <div class="member">

                <div class="avatar">👑</div>

                <h3>ONACH SMITH</h3>

                <p>👑 Membro da Tropa</p>

                <a class="social"
                   href="#"
                   target="_blank">
                   Facebook
                </a>

                <a class="social"
                   href="#"
                   target="_blank">
                   TikTok
                </a>

            </div>


            <!-- REI DELAS -->
            <div class="member">

                <div class="avatar">🔥</div>

                <h3>REI DELAS</h3>

                <p>🔥 Membro da Tropa</p>

                <a class="social"
                   href="#"
                   target="_blank">
                   Facebook
                </a>

            </div>


            <!-- TIBOSS -->
            <div class="member">

                <div class="avatar">⚡</div>

                <h3>TIBOSS</h3>

                <p>⚡ Membro da Tropa</p>

                <a class="social"
                   href="#"
                   target="_blank">
                   Facebook
                </a>

            </div>


            <!-- SENHOR DORAMA -->
            <div class="member">

                <div class="avatar">🎭</div>

                <h3>SENHOR DORAMA</h3>

                <p>🎭 Membro da Tropa</p>

                <a class="social"
                   href="#"
                   target="_blank">
                   Facebook
                </a>

            </div>

        </div>

    </div>
</section>


<!-- REDES -->
<section>
    <div class="container">

        <h2 class="title">📱 Redes Sociais</h2>

        <div class="about">

            <p>
                👑 <strong>ONACH SMITH</strong><br>
                Facebook: Onach Itach<br>
                TikTok: @onach_smith
            </p>

            <br>

            <p>
                ⚡ <strong>TIBOSS</strong><br>
                Facebook: Adriano Armindo Esteves
            </p>

            <br>

            <p>
                🔥 <strong>REI DELAS</strong><br>
                Facebook: Tobla Rápido
            </p>

            <br>

            <p>
                🎭 <strong>SENHOR DORAMA</strong><br>
                Facebook: Monteiro Baião
            </p>

        </div>

    </div>
</section>


<!-- VALORES -->
<section>
    <div class="container">

        <h2 class="title">🤝 Nossos Valores</h2>

        <div class="values">

            <div class="value">🤝 União</div>
            <div class="value">❤️ Respeito</div>
            <div class="value">🛡️ Lealdade</div>
            <div class="value">⚔️ Disciplina</div>
            <div class="value">🚀 Evolução</div>

        </div>

    </div>
</section>


<!-- FRASE FINAL -->
<div class="quote">

    <h2>
        ⚔️ <span>TROPA DO METE DICA</span> ⚔️
    </h2>

    <br>

    <p>
        “Juntos somos mais fortes.” 🔥
    </p>

</div>


<!-- RODAPÉ -->
<footer>

    <p>
        © 2026 <strong>Tropa do Mete Dica</strong>
    </p>

    <p>
        União • Respeito • Lealdade • Disciplina • Evolução
    </p>

</footer>

</body>
</html># Tropa-do-Mete-Dica-