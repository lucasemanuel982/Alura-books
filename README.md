<h1>AluraBooks</h1>
    <p><strong>AluraBooks</strong> é uma aplicação web focada em oferecer uma experiência de usuário otimizada para dispositivos móveis. Utilizamos a abordagem <em>Mobile First</em> para garantir que a interface seja responsiva e acessível em qualquer dispositivo. Além disso, incorporamos a biblioteca <strong>Swiper</strong> para implementar carrosséis interativos e dinâmicos.</p>

<div class="section">
        <h2>📱 Abordagem Mobile First</h2>
        <p>A abordagem <em>Mobile First</em> foi priorizada no desenvolvimento deste projeto para assegurar que a experiência do usuário em dispositivos móveis seja impecável. Isso significa que o design e as funcionalidades foram inicialmente pensadas para telas menores e, posteriormente, adaptadas para dispositivos com telas maiores.</p>
    </div>

<div class="section">
        <h2>🔄 Swiper - Biblioteca de Carrossel</h2>
        <p>Utilizamos a biblioteca <a href="https://swiperjs.com/" target="_blank">Swiper</a> para implementar carrosséis responsivos e touch-friendly. A Swiper permite a criação de sliders altamente personalizáveis, oferecendo uma navegação suave e intuitiva para os usuários.</p>
        <pre><code>&lt;link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
&lt;script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js">&lt;/script></code></pre>
        <p>Exemplo de implementação do Swiper:</p>
        <pre><code>&lt;div class="swiper">
    &lt;div class="swiper-pagination">&lt;/div>
    &lt;div class="swiper-wrapper">
        &lt;div class="swiper-slide">&lt;img src="./images/Portugol.svg" alt="Portugol">&lt;/div>
        &lt;div class="swiper-slide">&lt;img src="./images/ApacheKafka.svg" alt="Apache Kafka">&lt;/div>
        &lt;!-- Mais slides -->
    &lt;/div>
    &lt;div class="swiper-button-prev">&lt;/div>
    &lt;div class="swiper-button-next">&lt;/div>
&lt;/div>
&lt;script>
    const swiper = new Swiper('.swiper', {
        loop: true,
        pagination: {
            el: '.swiper-pagination',
            clickable: true,
        },
        navigation: {
            nextEl: '.swiper-button-next',
            prevEl: '.swiper-button-prev',
        },
    });
&lt;/script></code></pre>
    </div>

<div class="section">
        <h2>🚀 Funcionalidades</h2>
        <ul>
            <li>Menu responsivo com navegação por categorias.</li>
            <li>Carrosséis interativos para exibição de lançamentos e mais vendidos.</li>
            <li>Seção de tópicos recentemente visitados.</li>
            <li>Formulário de contato para cadastro de e-mail e atualizações.</li>
            <li>Integração com ícones e imagens modernas para uma melhor experiência visual.</li>
        </ul>
    </div>

<div class="section">
        <h2>🛠 Tecnologias Utilizadas</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript (Vanilla)</li>
            <li>Biblioteca <a href="https://swiperjs.com/" target="_blank">Swiper.js</a> para carrosséis</li>
            <li>Google Fonts - Poppins</li>
            <li>Bootstrap Icons para ícones modernos</li>
        </ul>
    </div>

<div class="section">
        <h2>📁 Estrutura do Projeto</h2>
        <ul>
            <li><code>index.html</code> - Estrutura principal da aplicação.</li>
            <li><code>style.css</code> - Estilos personalizados divididos em módulos:</li>
            <ul>
                <li><code>header.css</code></li>
                <li><code>banner.css</code></li>
                <li><code>carrossel.css</code></li>
                <li><code>cards.css</code></li>
                <li><code>topicos.css</code></li>
                <li><code>footer.css</code></li>
            </ul>
            <li><code>images/</code> - Pasta com todas as imagens utilizadas no projeto.</li>
            <li><code>index.js</code> - Scripts JavaScript para funcionalidades interativas.</li>
        </ul>
    </div>

<div class="section">
        <h2>🔧 Como Usar</h2>
        <ol>
            <li>Clone o repositório:</li>
            <pre><code>git clone https://github.com/seu-usuario/alurabooks.git</code></pre>
            <li>Entre na pasta do projeto:</li>
            <pre><code>cd alurabooks</code></pre>
            <li>Abra o arquivo <code>index.html</code> no seu navegador preferido.</li>
        </ol>
    </div>
