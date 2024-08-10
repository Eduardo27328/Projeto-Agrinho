<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #121212;
            color: #FFFFFF;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        h1 {
            margin: 0;
            font-size: 2.5em;
            color: #76c7c0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #76c7c0;
            text-decoration: none;
            font-weight: 700;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #b2dfdb;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 40px;
        }

        .carousel {
            position: relative;
            overflow: hidden;
            max-width: 100%;
            height: 400px; /* Ajuste a altura conforme necessário */
        }

        .carousel img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ajusta a imagem para cobrir todo o espaço */
            transition: opacity 1s ease-in-out;
        }

        .carousel img.active {
            opacity: 1;
        }

        .carousel img:not(.active) {
            opacity: 0;
        }

        h2 {
            font-size: 2em;
            color: #76c7c0;
            margin-bottom: 15px;
        }

        p {
            margin: 15px 0;
        }

        footer {
            background-color: #1f1f1f;
            color: #b2dfdb;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Agricultura e Equipamentos Modernos</h1>
        <nav>
            <ul>
                <li><a href="#agricultura">Agricultura</a></li>
                <li><a href="#tratores">Tratores</a></li>
                <li><a href="#colheitadeiras">Colheitadeiras</a></li>
                <li><a href="#caminhoes">Caminhões</a></li>
                <li><a href="#plantadeiras">Plantadeiras</a></li>
                <li><a href="#venenos">Venenos</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="agricultura">
            <h2>Agricultura</h2>
            <div class="carousel">
                <img src="https://agriq.com.br/wp-content/uploads/2020/08/Blog-AgriQ_Fatores-que-afetam-desenvolvimento-milho_Creditos-Freepik.jpg" alt="Agricultura 1" class="active">
                <img src="https://s2-g1.glbimg.com/H8_RJhyS4xTOm13V3dpXzzXVBJ8=/0x0:1000x562/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2022/K/I/iasL0xQsmbLh7qYwgA5Q/shutterstock-1726609156.jpg" alt="Agricultura 2">
                <img src="https://blog.verde.ag/pt/wp-content/uploads/2023/01/O-uso-da-agricultura-4.0-e-o-aumento-da-produtividade-no-campo.webp" alt="Agricultura 3">
                <img src="https://agropos.com.br/wp-content/uploads/2023/10/Imagem-2023-11-16T144713.510.png" alt="Agricultura 4">
            </div>
            A agricultura é uma prática ancestral que sustenta a civilização humana, fornecendo alimentos, fibras, produtos medicinais e matérias-primas essenciais para a vida cotidiana. Desde os primeiros dias da domesticação de plantas e animais, há cerca de 10.000 anos, a agricultura tem evoluído significativamente. Nos tempos antigos, a produção agrícola era baseada em técnicas rudimentares e dependia muito do clima e da fertilidade natural do solo. As primeiras sociedades agrícolas desenvolveram ferramentas básicas e técnicas de irrigação para melhorar a produtividade, mas o trabalho era intensivo em mão de obra e frequentemente limitado pela falta de conhecimento científico.
            </p>
            <p>
                Com o avanço da ciência e da tecnologia, a agricultura passou por uma transformação radical. O desenvolvimento de fertilizantes sintéticos, pesticidas e a mecanização no século XX aumentaram drasticamente a produtividade agrícola, permitindo que pequenas áreas de terra produzissem maiores rendimentos. A revolução verde, nas décadas de 1950 e 1960, introduziu variedades de cultivos de alto rendimento e técnicas de cultivo intensivo, o que ajudou a aumentar a produção de alimentos e reduzir a fome em muitas partes do mundo.
            </p>
            <p>
                Hoje, a agricultura moderna é caracterizada pelo uso de tecnologias avançadas, como agricultura de precisão, biotecnologia, e sistemas de gerenciamento agrícola baseados em dados. Sensores, drones, e imagens de satélite são usados para monitorar a saúde das culturas, otimizar o uso de água e fertilizantes, e tomar decisões informadas sobre a colheita. Essas inovações não só aumentam a eficiência e a produtividade, mas também ajudam a mitigar os impactos ambientais da agricultura, como a erosão do solo e a poluição dos cursos de água. Práticas sustentáveis, como a rotação de culturas, a agricultura orgânica e o manejo integrado de pragas, estão sendo cada vez mais adotadas para preservar os recursos naturais e garantir a viabilidade da produção agrícola a longo prazo.
        </section>
        <section id="tratores">
            <h2>Tratores</h2>
            <div class="carousel">
                <img src="https://cdn.spiritshop.com.br/jmalucelli/image/cache/data/up_system/product-55409/puma170-1000x1000.png" alt="Tratores 1" class="active">
                <img src="https://cnhi-p-001-delivery.sitecorecontenthub.cloud/api/public/content/2eab40a91d534b6e903b6e0aec2ff50e?v=7317f5bc" alt="Tratores 2">
                <img src="https://brasil.agrofystatic.com/media/catalog/product/cache/850x600/T/r/Trator-Farmall-80-Case-Ih-Tra-_o-4X4-Plataformado-agrofy-1-20231212123728.jpg" alt="Tratores 3">
                <img src="https://brasil.agrofystatic.com/media/catalog/product/cache/850x600/t/r/trator-agr-cola-case-farmall-1-Mega-Pesados-agrofy-0-20240626163452.jpg" alt="Tratores 4">
            </div>
            <p> Tratores são a espinha dorsal da mecanização agrícola, desempenhando um papel crucial na transformação da agricultura de uma prática intensiva em mão de obra para uma indústria altamente mecanizada e eficiente. Desde sua invenção no início do século XX, os tratores substituíram animais de tração, como cavalos e bois, tornando as operações agrícolas muito mais eficientes. Com motores potentes e versatilidade excepcional, os tratores permitem que os agricultores realizem uma ampla gama de tarefas, desde arar e cultivar o solo até semear, pulverizar, e transportar colheitas.
            </p>
            <p>
                O desenvolvimento tecnológico dos tratores não parou por aí. Com o tempo, esses veículos agrícolas evoluíram para incorporar inovações como a tração nas quatro rodas, que aumenta a eficiência em terrenos difíceis, e a hidráulica, que permite aos agricultores acoplar e operar uma variedade de implementos, como arados, semeadeiras e colhedoras. Hoje, muitos tratores estão equipados com sistemas de GPS de alta precisão, que permitem o mapeamento exato dos campos e a execução de tarefas agrícolas com precisão centimétrica. Isso reduz o desperdício de sementes e fertilizantes, diminui o consumo de combustível, e minimiza o impacto ambiental.
            </p>
            <p>
                Além disso, a automação está se tornando uma característica comum nos tratores modernos, com sistemas de direção autônoma e controle automático de implementos. Isso não só aumenta a eficiência, mas também melhora a segurança do operador, reduzindo a fadiga e o risco de erros humanos. A conectividade de dados também está desempenhando um papel crescente, permitindo que os tratores se integrem a sistemas de gerenciamento de fazendas baseados em nuvem, onde os dados de campo podem ser analisados em tempo real para melhorar a tomada de decisões. Em suma, os tratores modernos são máquinas complexas e altamente especializadas que continuam a ser uma força motriz na agricultura mundial.
        </section>
        <section id="colheitadeiras">
            <h2>Colheitadeiras</h2>
            <div class="carousel">
                <img src="https://www.farmfor.com.br/wp-content/uploads/2019/10/colhedeira-colheitadeira-case-ih-9250-1024x768.jpg" alt="Colheitadeiras 1" class="active">
                <img src="https://cnhi-p-001-delivery.sitecorecontenthub.cloud/api/public/content/646f22eb8b4a470fbc16920399bfbb72?v=a812bb33" alt="Colheitadeiras 2">
                <img src="https://www.deere.com.br/assets/images/region-3/products/harvesters/s-series/s550/colheitadeira_s550_campo_4_large_7455583b2f1eda920b4c801c753015effcff6f22.jpg" alt="Colheitadeiras 3">
                <img src="https://www.comprerural.com/wp-content/uploads/2019/12/New_Holland_CR-1090_maior_colheitadeira_do_mundo.jpg" alt="Colheitadeiras 4">
            </div>
            As colheitadeiras são máquinas essenciais no ciclo de produção agrícola, projetadas para colher grãos e outras culturas de forma rápida e eficiente. Antes de sua invenção, a colheita era uma das atividades agrícolas mais trabalhosas e demoradas, realizada manualmente com foices e outros instrumentos simples. A primeira colheitadeira mecânica, desenvolvida no início do século XIX, revolucionou a agricultura ao combinar várias operações — cortar, debulhar e separar os grãos da palha — em uma única máquina, reduzindo drasticamente o tempo e o esforço necessários para colher as safras.
        </p>
        <p>
            Com o passar do tempo, as colheitadeiras evoluíram para máquinas extremamente sofisticadas, capazes de colher grandes áreas de terra com alta eficiência. As colheitadeiras modernas estão equipadas com uma variedade de sensores e tecnologias avançadas que permitem monitorar a umidade dos grãos, o rendimento das culturas, e outros parâmetros críticos em tempo real. Essas informações são essenciais para os agricultores, ajudando-os a tomar decisões informadas sobre quando colher, como armazenar e como comercializar suas safras.
        </p>
        <p>
            Além disso, as colheitadeiras de última geração são projetadas com a ergonomia e a segurança dos operadores em mente. Cabines confortáveis, controles intuitivos, e sistemas automatizados de direção e operação reduzem a fadiga do operador e aumentam a produtividade. As colheitadeiras também são equipadas com motores potentes e eficientes, que cumprem os rigorosos padrões de emissões, contribuindo para uma agricultura mais sustentável. Em suma, as colheitadeiras são máquinas indispensáveis que continuam a impulsionar a eficiência e a produtividade da agricultura moderna.
        </section>
        <section id="caminhoes">
            <h2>Caminhões</h2>
            <div class="carousel">
                <img src="https://blogdocaminhoneiro.com/wp-content/uploads/2024/03/edicao-especial-Scania-500K-1.jpg" alt="Caminhões 1" class="active">
                <img src="https://quatrorodas.abril.com.br/wp-content/uploads/2021/09/VOLVO-SEMI.jpg?quality=70&strip=info&w=720&crop=1" alt="Caminhões 2">
                <img src="https://fotos-estradao-estadao.nyc3.cdn.digitaloceanspaces.com/wp-content/uploads/2023/09/04084104/Volkswagen-Meteor-1160x653.jpg" alt="Caminhões 3">
                <img src="https://www.autoindustria.com.br/wp-content/uploads/2023/05/Scania-R450-Plus-1200x640.jpeg" alt="Caminhões 4">
            </div>
            Caminhões desempenham um papel vital na logística agrícola, conectando fazendas a mercados e centros de distribuição. Eles são responsáveis pelo transporte de uma vasta gama de produtos agrícolas, desde grãos e cereais até frutas, vegetais e produtos lácteos. A diversidade de caminhões, que varia de pequenas picapes a grandes caminhões de carga, permite que eles atendam a diferentes necessidades de transporte, garantindo que os produtos agrícolas sejam entregues de forma eficiente e em boas condições.
        </p>
        <p>
            A evolução dos caminhões agrícolas ao longo dos anos tem sido notável. Os motores modernos são projetados para ser mais eficientes em termos de consumo de combustível, reduzindo os custos operacionais para os agricultores e diminuindo o impacto ambiental do transporte de longa distância. Além disso, os caminhões agrícolas estão agora equipados com tecnologia de ponta, como sistemas de navegação GPS, que permitem o planejamento de rotas mais eficientes, e sistemas de telemetria, que monitoram o desempenho do veículo em tempo real.
        </p>
        <p>
            A segurança também é uma prioridade nos caminhões agrícolas modernos. Recursos como freios ABS, controle eletrônico de estabilidade, e sistemas de alerta de colisão ajudam a prevenir acidentes e a garantir a segurança tanto dos motoristas quanto das cargas. Além disso, muitos caminhões agora vêm com cabines confortáveis e ergonômicas, que proporcionam um ambiente de trabalho mais seguro e agradável para os motoristas, especialmente durante longas jornadas. Em resumo, os caminhões são um componente essencial da cadeia de suprimentos agrícola, garantindo que os produtos cheguem aos consumidores de forma eficiente e segura.
        </section>
        <section id="plantadeiras">
            <h2>Plantadeiras</h2>
            <div class="carousel">
                <img src="https://www.cotramaq.com.br/app/fotos/68ac24171f3e9e11cd6d87aded326a60.jpg" alt="Plantadeiras 1" class="active">
                <img src="https://rciararaquara.com.br/wp-content/uploads/2023/10/Tatu-22-640x434.jpg" alt="Plantadeiras 2">
                <img src="https://www.coasul.com.br/extranet/thumbnail/fill/900/gallery/37.jpg" alt="Plantadeiras 3">
                <img src="https://imagens.mfrural.com.br/mfrural-produtos-us/263123-713121-74777708-plantadeira-tatu-cop-10-linhas.jpg" alt="Plantadeiras 4">
            </div>
            As plantadeiras são máquinas agrícolas fundamentais que desempenham um papel crítico na semeadura, garantindo que as sementes sejam plantadas na profundidade e espaçamento corretos para maximizar a germinação e o crescimento das plantas. Antes do advento das plantadeiras mecânicas, a semeadura era um processo manual e intensivo em mão de obra, com os agricultores lançando sementes à mão e esperando que a natureza seguisse seu curso. Esse método não só era ineficiente, como também resultava em colheitas desiguais e desperdício de sementes.
        </p>
        <p>
            A introdução de plantadeiras mecânicas revolucionou a agricultura, permitindo uma semeadura muito mais precisa e eficiente. As plantadeiras modernas são equipadas com uma variedade de recursos avançados, como sistemas de monitoramento de sementes, que detectam e corrigem problemas em tempo real, e controle de taxa variável, que ajusta a densidade de semeadura com base nas condições específicas do solo e do clima. Esses avanços não só aumentam a produtividade das culturas, mas também reduzem o desperdício e melhoram a sustentabilidade geral da operação agrícola.
        </p>
        <p>
            Além disso, muitas plantadeiras estão agora integradas com tecnologia de agricultura de precisão, como sistemas de GPS e sensores de solo, que permitem aos agricultores plantar com uma precisão incrível. Isso garante uma distribuição uniforme das sementes, o que é essencial para a maximização do rendimento das colheitas. Em suma, as plantadeiras são ferramentas indispensáveis na agricultura moderna, ajudando os agricultores a melhorar a eficiência, reduzir custos e aumentar a produtividade de forma sustentável.
        <section id="venenos">
            <h2>Venenos</h2>
            <div class="carousel">
                <img src="https://imagens-cdn.canalrural.com.br/2018/06/1416221124150.jpg" alt="Venenos 1" class="active">
                <img src="https://www.ecodebate.com.br/wp-content/uploads/2016/02/agrotoxicos.jpg" alt="Venenos 2">
                <img src="https://s2-g1.glbimg.com/98bVfr3frKsJxA-swz6e0fVeBzw=/0x0:1700x1065/984x0/smart/filters:strip_icc()/s.glbimg.com/jo/g1/f/original/2017/01/22/pma.jpg" alt="Venenos 3">
                <img src="https://www.marketplacerural.com.br/img/anuncios/202402280030542471/800/00305428022024.jpg" alt="Venenos 4">
            </div>
            Agrotóxicos, também conhecidos como pesticidas, são substâncias químicas utilizadas para controlar pragas, ervas daninhas e doenças que podem afetar negativamente as culturas agrícolas. Eles são essenciais para a proteção das plantações e para garantir que os agricultores possam alcançar rendimentos elevados e consistentes. No entanto, o uso de agrotóxicos é um tema controverso, devido aos potenciais impactos negativos sobre o meio ambiente e a saúde humana.
        </p>
        <p>
            Existem vários tipos de agrotóxicos, incluindo inseticidas, herbicidas e fungicidas, cada um projetado para combater diferentes ameaças às plantas. Os inseticidas são usados para controlar pragas de insetos que podem danificar ou destruir as culturas, enquanto os herbicidas são aplicados para eliminar ervas daninhas que competem com as plantas por nutrientes e água. Os fungicidas, por sua vez, são utilizados para prevenir ou controlar doenças fúngicas que podem devastar colheitas inteiras.
        </p>
        <p>
            O manejo adequado dos agrotóxicos é crucial para minimizar os riscos associados ao seu uso. Isso inclui seguir as diretrizes de aplicação recomendadas, usar equipamentos de proteção individual, e adotar práticas de manejo integrado de pragas (MIP). O MIP combina o uso de agrotóxicos com outras estratégias, como controle biológico e rotação de culturas, para reduzir a dependência de produtos químicos e promover uma agricultura mais sustentável. Além disso, o desenvolvimento de agrotóxicos de última geração, que são mais específicos e menos tóxicos para o meio ambiente, está ajudando a mitigar os impactos negativos da agricultura intensiva.
        </p>
        <p>
            Em resumo, os agrotóxicos são ferramentas poderosas que, quando usadas corretamente, podem proteger as culturas e garantir a segurança alimentar global. No entanto, é fundamental que seu uso seja gerenciado com cuidado e responsabilidade, para garantir que os benefícios superem os riscos e para promover uma agricultura que seja sustentável a longo prazo.        </section>
    </main>
    <footer>
        <p>&copy; Criado por Eduardo Henrique Sousa Aguiar </p>
    </footer>
    <script>
        // JavaScript para o carrossel automático de imagens
        document.addEventListener('DOMContentLoaded', function() {
            const carousels = document.querySelectorAll('.carousel');
            carousels.forEach(carousel => {
                const images = carousel.querySelectorAll('img');
                let currentIndex = 0;
                setInterval(() => {
                    images[currentIndex].classList.remove('active');
                    currentIndex = (currentIndex + 1) % images.length;
                    images[currentIndex].classList.add('active');
                }, 3000); // Troca de imagem a cada 3 segundos
            });
        });
    </script>
</body>
</html>
