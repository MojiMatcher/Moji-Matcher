<script>
    export default {
        data() {
            return {
                
            }
        }
    }
    

</script>

<template>
    <header>
        <div>
            <a href="/">
                <img src="./assets/logo-trans.png" id="logo">
            </a>
        </div>
        <a href="#section1" class="section">Sobre</a>
        <a href="#section2" class="section">Funcionalidades</a>
        <a href="#section3" class="section">Baixar</a>
        <button id="header-button" onclick="window.location='https://github.com/MojiMatcher/Moji-Matcher';">Experimente o Moji Matcher</button>

    </header>

    <div id="home">
        <img src="./assets/libs.png" id="home-libs">
        <img src="./assets/sample.png" id="home-sample">
    </div>

    <section id="section1" class="sectionTitle">
        <h1>Sobre</h1>
        <p>Moji Matcher é um aplicativo para conhecer pessoas único projetado especificamente para indivíduos que são analfabetos ou preferem se comunicar por meio de meios visuais.<br><br><br>O aplicativo se concentra no uso de emojis como linguagem principal, permitindo que os usuários expressem-se e se conectem com outros de forma divertida e intuitiva.</p>
    </section>

    <section id="section2" class="sectionTitle">
        <h1>Funcionalidades</h1>
        <p>O algoritmo de correspondência do Moji Matcher usa uma combinação de emojis inseridos pelo usuário e preferências para sugerir correspondências compatíveis.<br><br>A funcionalidade de bate-papo do Moji Matcher também é baseada em emojis, permitindo que os usuários se comuniquem uns com os outros usando uma vasta biblioteca de emojis.<br><br> O aplicativo inclui uma variedade de recursos para facilitar a conversa, como sugestões de emojis e um "correspondente de humor" que ajuda os usuários a encontrar alguém que esteja se sentindo da mesma forma.</p>
    </section>

    <section id="section3" class="sectionTitle">
        <h1>Baixar</h1>
        <p>Ficou interessado?<br><br>Conhece alguém que precisa desse meio de comunicação para conhecer novas pessoas?<br><br>Baixe agora o Moji Matcher!</p>
    </section>

</template>
