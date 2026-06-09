<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JotaPe Marketing | Estratégia e Resultados</title>
    <meta name="description" content="Agência de marketing digital especializada em crescimento de marcas, gestão de redes sociais, criação de vídeos e identidade visual. Transforme presença em vendas!">
    <meta name="keywords" content="marketing digital, gestão de redes sociais, criação de vídeos, identidade visual, Igarassu, Pernambuco">
    <link rel="canonical" href="https://html.house/4e7k9c">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        jp: {
                            azul: '#165DFF',
                            preto: '#050505',
                            branco: '#FFFFFF',
                            cinza: '#121212',
                            cinzaClaro: '#1E1E1E',
                        },
                        fontFamily: {
                            sans: ['Inter', 'sans-serif'],
                        },
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 0 30px rgba(22, 93, 255, 0.5);
            }
            .card-gradient {
                background: linear-gradient(145deg, #121212, #050505);
            }
            .circle-pattern {
                background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg stroke='%23165DFF' stroke-width='1' stroke-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='25'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
            }
            .btn-action {
                @apply w-full mt-6 py-3 rounded-lg transition-all duration-300 ease-in-out font-semibold hover:shadow-lg hover:shadow-jp-azul/30 hover:-translate-y-1;
            }
            .card-hover {
                @apply transition-all duration-300 ease-in-out hover:border-jp-azul/70 hover:shadow-[0_8px_32px_rgba(22,93,255,0.15)] hover:-translate-y-2;
            }
            .fade-in {
                opacity: 0;
                transform: translateY(20px);
                transition: all 0.6s ease-out;
            }
            .fade-in.visible {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body class="bg-jp-preto text-jp-branco circle-pattern min-h-screen">

    <!-- Header -->
    <header class="container mx-auto px-4 py-12 text-center">
        <div class="flex justify-center items-center gap-4 mb-6">
            <div class="w-14 h-14 rounded-full border-2 border-jp-azul flex items-center justify-center shadow-[0_0_20px_rgba(22,93,255,0.2)]">
                <div class="w-9 h-9 rounded-full border border-jp-branco/60"></div>
            </div>
            <h1 class="text-5xl md:text-6xl font-bold text-jp-azul text-shadow">JotaPe Marketing</h1>
        </div>
        <p class="text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto leading-relaxed">
            Transformamos presença digital em resultados reais<br>
            <span class="text-jp-azul font-medium">Igarassu - PE</span>
        </p>
        <p class="text-base text-gray-400 mt-3">Instagram: <a href="https://instagram.com/jp.marketing.oficial" target="_blank" rel="noopener noreferrer" class="text-jp-azul hover:underline">@jp.marketing.oficial</a></p>
    </header>

    <!-- Sobre Nós -->
    <section class="container mx-auto px-4 py-10 fade-in">
        <div class="bg-jp-cinza/80 backdrop-blur-sm p-8 md:p-10 rounded-2xl border border-jp-azul/20 shadow-2xl">
            <h2 class="text-3xl font-bold mb-6 text-center text-jp-azul">Sobre a JotaPe Marketing</h2>
            <p class="text-gray-300 text-center max-w-4xl mx-auto leading-relaxed text-lg mb-4">
                Somos uma agência especializada em fazer o seu negócio se destacar no meio digital. Sabemos que não basta apenas estar presente — é preciso comunicar bem, atrair o público certo e transformar seguidores em clientes fiéis.
            </p>
            <p class="text-gray-300 text-center max-w-4xl mx-auto leading-relaxed text-lg">
                Nosso trabalho é baseado em estratégia, criatividade e dados. Estudamos o seu mercado, entendemos as necessidades do seu público e criamos soluções personalizadas para gerar crescimento sustentável, aumentar as vendas e fortalecer a reputação da sua marca. O nosso compromisso é entregar retorno sobre o seu investimento.
            </p>
        </div>
    </section>

    <!-- Planos Mensais -->
    <section class="container mx-auto px-4 py-12" id="planos">
        <h2 class="text-4xl font-bold text-center mb-16 text-jp-azul fade-in">Nossos Planos de Gestão</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            
            <!-- Plano Iniciante -->
            <div class="card-gradient rounded-2xl p-7 border border-gray-800 card-hover fade-in">
                <div class="text-center">
                    <span class="bg-gray-700 text-sm px-4 py-1.5 rounded-full mb-5 inline-block font-medium">Presença Digital</span>
                    <h3 class="text-2xl font-bold mb-4">Para quem está começando</h3>
                    <p class="text-gray-300 text-sm mb-5">Ideal para estruturar a sua marca e começar a se conectar com o público de forma profissional.</p>
                </div>
                <ul class="space-y-4 my-7 text-left">
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Gestão de 1 Rede Social</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Postagens regulares e organizadas</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Criação de artes alinhadas à sua identidade</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Legendas que engajam e vendem</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Relatório de desempenho mensal</li>
                </ul>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Gostaria%20de%20saber%20mais%20sobre%20o%20Plano%20Presen%C3%A7a%20Digital%20da%20JotaPe%20Marketing." target="_blank" rel="noopener noreferrer">
                    <button class="btn-action bg-jp-azul hover:bg-jp-azul/90 text-white">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Informações
                    </button>
                </a>
            </div>

            <!-- Plano Crescimento -->
            <div class="card-gradient rounded-2xl p-7 border-2 border-jp-azul shadow-2xl relative card-hover fade-in">
                <div class="absolute -top-4 left-1/2 -translate-x-1/2 bg-jp-azul px-5 py-1.5 rounded-full text-sm font-semibold shadow-lg">Mais Procurado</div>
                <div class="text-center">
                    <span class="bg-jp-azul/20 text-sm px-4 py-1.5 rounded-full mb-5 inline-block font-medium">Engajamento Total</span>
                    <h3 class="text-2xl font-bold mb-4">Para expandir sua marca</h3>
                    <p class="text-gray-300 text-sm mb-5">Focado em aumentar o alcance, interagir mais com o público e preparar o terreno para o aumento das vendas.</p>
                </div>
                <ul class="space-y-4 my-7 text-left">
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Gestão de 2 Redes Sociais</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Conteúdo frequente e Stories diários</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Planejamento estratégico mensal</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Análise de mercado e concorrência</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Atendimento ágil e prioritário</li>
                </ul>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Tenho%20interesse%20no%20Plano%20Engajamento%20Total.%20Podem%20me%20passar%20os%20detalhes?" target="_blank" rel="noopener noreferrer">
                    <button class="btn-action bg-jp-azul hover:bg-jp-azul/90 text-white">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Informações
                    </button>
                </a>
            </div>

            <!-- Plano Avançado -->
            <div class="card-gradient rounded-2xl p-7 border border-gray-800 card-hover fade-in">
                <div class="text-center">
                    <span class="bg-gray-700 text-sm px-4 py-1.5 rounded-full mb-5 inline-block font-medium">Domínio de Mercado</span>
                    <h3 class="text-2xl font-bold mb-4">Para quem quer liderar</h3>
                    <p class="text-gray-300 text-sm mb-5">Solução completa para marcas que desejam se tornar referência, atrair mais clientes e maximizar os resultados.</p>
                </div>
                <ul class="space-y-4 my-7 text-left">
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Gestão de até 3 Redes Sociais</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Produção de vídeos profissionais</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Gestão de tráfego pago qualificado</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Reunião estratégica mensal</li>
                    <li class="flex items-center gap-3"><i class="fa fa-check text-jp-azul text-lg"></i> Relatórios completos de retorno</li>
                </ul>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Quero%20conhecer%20melhor%20o%20Plano%20Dom%C3%ADnio%20de%20Mercado%20da%20JotaPe%20Marketing." target="_blank" rel="noopener noreferrer">
                    <button class="btn-action bg-jp-azul hover:bg-jp-azul/90 text-white">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Informações
                    </button>
                </a>
            </div>
        </div>
    </section>

    <!-- Serviços Específicos -->
    <section class="container mx-auto px-4 py-12">
        <h2 class="text-4xl font-bold text-center mb-16 text-jp-azul fade-in">Serviços Específicos</h2>
        <p class="text-gray-300 text-center max-w-2xl mx-auto mb-10">Além dos planos completos, oferecemos soluções avulsas para atender necessidades específicas da sua marca.</p>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7">
            
            <div class="bg-jp-cinza/70 p-7 rounded-xl border border-gray-800 card-hover fade-in text-center">
                <i class="fa fa-pencil text-jp-azul text-4xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Identidade Visual</h3>
                <p class="text-gray-400 text-sm mb-5 leading-relaxed">Criação de logotipo, paleta de cores e manual de marca para que a sua empresa tenha uma imagem forte e reconhecida no mercado.</p>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Gostaria%20de%20um%20or%C3%A7amento%20para%20Identidade%20Visual." target="_blank" rel="noopener noreferrer">
                    <button class="mt-5 px-7 py-2.5 rounded-lg bg-jp-azul/20 hover:bg-jp-azul/70 transition-all duration-300 text-sm font-semibold w-full">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Orçamento
                    </button>
                </a>
            </div>

            <div class="bg-jp-cinza/70 p-7 rounded-xl border border-gray-800 card-hover fade-in text-center">
                <i class="fa fa-video-camera text-jp-azul text-4xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Criação de Vídeos</h3>
                <p class="text-gray-400 text-sm mb-5 leading-relaxed">Produção e edição de vídeos curtos e envolventes para Reels, TikTok e Shorts, que prendem a atenção e geram interesse pelo seu produto ou serviço.</p>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Quero%20saber%20sobre%20a%20cria%C3%A7%C3%A3o%20de%20v%C3%ADdeos%20para%20redes%20sociais." target="_blank" rel="noopener noreferrer">
                    <button class="mt-5 px-7 py-2.5 rounded-lg bg-jp-azul/20 hover:bg-jp-azul/70 transition-all duration-300 text-sm font-semibold w-full">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Orçamento
                    </button>
                </a>
            </div>

            <div class="bg-jp-cinza/70 p-7 rounded-xl border border-gray-800 card-hover fade-in text-center">
                <i class="fa fa-file-image-o text-jp-azul text-4xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Pacote de Artes</h3>
                <p class="text-gray-400 text-sm mb-5 leading-relaxed">Conjunto de peças gráficas personalizadas e prontas para uso, mantendo a identidade visual e ajudando a manter a frequência de postagem nas redes.</p>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Podem%20me%20informar%20sobre%20o%20Pacote%20de%20Artes%20Gr%C3%A1ficas?" target="_blank" rel="noopener noreferrer">
                    <button class="mt-5 px-7 py-2.5 rounded-lg bg-jp-azul/20 hover:bg-jp-azul/70 transition-all duration-300 text-sm font-semibold w-full">
                        <i class="fa fa-whatsapp mr-2"></i> Solicitar Orçamento
                    </button>
                </a>
            </div>

            <div class="bg-jp-cinza/70 p-7 rounded-xl border border-gray-800 card-hover fade-in text-center">
                <i class="fa fa-comments text-jp-azul text-4xl mb-4"></i>
                <h3 class="text-xl font-semibold mb-2">Consultoria Estratégica</h3>
                <p class="text-gray-400 text-sm mb-5 leading-relaxed">Análise completa do seu negócio e orientação prática para você mesmo aplicar as melhores estratégias de marketing digital e alavancar as vendas.</p>
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Tenho%20interesse%20em%20agendar%20uma%20Consultoria%20Estrat%C3%A9gica." target="_blank" rel="noopener noreferrer">
                    <button class="mt-5 px-7 py-2.5 rounded-lg bg-jp-azul/20 hover:bg-jp-azul/70 transition-all duration-300 text-sm font-semibold w-full">
                        <i class="fa fa-whatsapp mr-2"></i> Agendar Atendimento
                    </button>
                </a>
            </div>
        </div>
    </section>

    <!-- Diferencial -->
    <section class="container mx-auto px-4 py-12 fade-in">
        <div class="bg-jp-cinza/80 backdrop-blur-sm p-8 md:p-10 rounded-2xl border border-jp-azul/20 shadow-2xl">
            <h2 class="text-3xl font-bold mb-6 text-center text-jp-azul">Por que escolher a JotaPe Marketing?</h2>
            <div class="text-gray-300 text-center max-w-4xl mx-auto leading-relaxed text-lg space-y-4">
                <p>Não vendemos apenas serviços — vendemos <strong>resultados e crescimento</strong>. Entendemos que cada negócio é único, por isso criamos estratégias sob medida, pensadas para o seu público e para os seus objetivos.</p>
                <p>Trabalhamos com transparência total, compartilhando o que fazemos e por quê. O nosso foco é fazer com que o seu investimento se transforme em mais visibilidade, mais confiança e, principalmente, mais vendas.</p>
                <p>Entre em contato conosco e vamos juntos traçar o caminho para o sucesso da sua marca!</p>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <footer class="bg-jp-cinza mt-20 py-12 border-t border-jp-azul/10">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-3xl font-bold mb-4 text-jp-azul">Fale Conosco e Solicite seu Orçamento</h3>
            <p class="mb-8 text-gray-300 max-w-2xl mx-auto text-lg">Estamos prontos para entender as suas necessidades e apresentar a melhor solução para o crescimento do seu negócio. Entre em contato e converse com a nossa equipe!</p>
            <div class="flex justify-center gap-5 flex-wrap">
                <a href="https://wa.me/5581996572994?text=Ol%C3%A1!%20Cheguei%20pelo%20site%20e%20gostaria%20de%20conversar%20sobre%20como%20podemos%20crescer%20juntos." target="_blank" rel="noopener noreferrer" class="bg-jp-azul px-9 py-4 rounded-lg hover:bg-jp-azul/90 transition-all duration-300 font-semibold text-lg shadow-lg hover:shadow-jp-azul/30 flex items-center gap-2">
                    <i class="fa fa-whatsapp"></i> Chamar no WhatsApp
                </a>
                <a href="https://instagram.com/jp.marketing.oficial" target="_blank" rel="noopener noreferrer" class="border border-jp-azul px-7 py-4 rounded-lg hover:bg-jp-azul/10 transition-all duration-300 flex items-center gap-2">
                    <i class="fa fa-instagram"></i> Seguir no Instagram
                </a>
            </div>
            <p class="mt-10 text-gray-500 text-sm">© 2026 JotaPe Marketing - Todos os direitos reservados.<br>Atendimento: (81) 99657-2994 | Instagram: @jp.marketing.oficial</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const fadeElements = document.querySelectorAll('.fade-in');
            
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, observerOptions);

            fadeElements.forEach(el => observer.observe(el));

            const cards = document.querySelectorAll('.card-gradient, .bg-jp-cinza\\/70');
            cards.forEach(card => {
                card.addEventListener('mouseenter', () => {
                    card.classList.add('shadow-[0_0_30px_rgba(22,93,255,0.2)]');
                });
                card.addEventListener('mouseleave', () => {
                    card.classList.remove('shadow-[0_0_30px_rgba(22,93,255,0.2)]');
                });
            });
        });
    </script>

</body>
</html>
