[tatoooindex.html](https://github.com/user-attachments/files/21923575/tatoooindex.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tattoo Rio Flash - Revolucionando a Tatuagem Carioca</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .flash-modal {
            display: none;
            position: fixed;
            z-index: 100;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.8);
            backdrop-filter: blur(5px);
            -webkit-backdrop-filter: blur(5px);
        }
    </style>
</head>
<body class="bg-zinc-950 text-stone-100 font-sans leading-relaxed">

    <header class="bg-zinc-900 sticky top-0 z-50 shadow-md">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#hero" class="text-2xl font-bold text-stone-100">Tattoo Rio Flash</a>
            <nav>
                <a href="#problema" class="mx-2 hover:text-purple-300 transition-colors">O Problema</a>
                <a href="#solucao" class="mx-2 hover:text-purple-300 transition-colors">A Solução</a>
                <a href="#fluxo" class="mx-2 hover:text-purple-300 transition-colors">Como Funciona</a>
                <a href="#marketplace" class="mx-2 hover:text-purple-300 transition-colors">Marketplace</a>
                <a href="#contato" class="mx-2 hover:text-purple-300 transition-colors">Contato</a>
            </nav>
        </div>
    </header>

    <section id="hero" class="bg-gray-800 text-white min-h-screen flex items-center justify-center text-center p-6" style="background-image: url('https://placehold.co/1920x1080/2c3e50/ecf0f1?text=A+sua+arte+merece+mais+do+que+um+post.'); background-size: cover; background-position: center;">
        <div class="bg-black bg-opacity-50 p-8 rounded-lg">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">
                A sua arte merece mais do que um post.
            </h1>
            <h2 class="text-2xl md:text-4xl font-bold mb-6 tracking-wide">
                Tattoo Rio Flash
            </h2>
            <p class="text-xl md:text-2xl max-w-2xl mx-auto">
                Uma plataforma para conectar artistas e apaixonados por tatuagem no Rio de Janeiro.
            </p>
        </div>
    </section>

    <section id="problema" class="container mx-auto px-6 py-16">
        <h3 class="text-3xl font-bold text-center mb-10">O trabalho de um tatuador não é só tatuar.</h3>
        <p class="text-center text-lg max-w-3xl mx-auto mb-12">
            Nesta seção, identificamos as principais dores e desafios enfrentados diariamente por tatuadores. A Tattoo Rio Flash entende que a paixão pela arte muitas vezes é ofuscada por tarefas de gestão e marketing.
        </p>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
            <div class="bg-zinc-900 p-6 rounded-lg shadow-md">
                <span class="text-4xl">🗨️</span>
                <h4 class="font-bold mt-4 mb-2">Responder dezenas de DMs</h4>
                <p class="text-sm text-stone-400">Perder tempo gerenciando mensagens de curiosos e agendamentos.</p>
            </div>
            <div class="bg-zinc-900 p-6 rounded-lg shadow-md">
                <span class="text-4xl">🗓️</span>
                <h4 class="font-bold mt-4 mb-2">Agendar horários</h4>
                <p class="text-sm text-stone-400">Dificuldade em organizar a agenda de forma eficiente e sem conflitos.</p>
            </div>
            <div class="bg-zinc-900 p-6 rounded-lg shadow-md">
                <span class="text-4xl">📈</span>
                <h4 class="font-bold mt-4 mb-2">Se preocupar com o marketing digital</h4>
                <p class="text-sm text-stone-400">Lutar contra o algoritmo para ganhar visibilidade.</p>
            </div>
            <div class="bg-zinc-900 p-6 rounded-lg shadow-md">
                <span class="text-4xl">🚫</span>
                <h4 class="font-bold mt-4 mb-2">Lidar com "não-respostas"</h4>
                <p class="text-sm text-stone-400">Perder tempo com clientes que não fecham negócio.</p>
            </div>
        </div>
    </section>

    <section id="solucao" class="bg-purple-900 text-white py-16 px-6">
        <div class="container mx-auto text-center">
            <h3 class="text-3xl font-bold mb-4">E se o seu tempo fosse 100% focado na arte?</h3>
            <p class="text-lg max-w-2xl mx-auto">
                A Tattoo Rio Flash é a resposta para esses desafios. Nossa missão é desafogar sua agenda e te conectar com clientes que realmente valorizam seu trabalho, através de um marketplace de flashs com curadoria, exclusivo para o Rio de Janeiro.
            </p>
        </div>
    </section>

    <section id="fluxo" class="container mx-auto px-6 py-16">
        <h3 class="text-3xl font-bold text-center mb-10">Como Funciona?</h3>
        <p class="text-center text-lg max-w-3xl mx-auto mb-12">
            Aqui, você pode entender o fluxo simples e eficiente que usamos para conectar sua arte aos clientes certos. Nossa plataforma age como uma ponte, facilitando todo o processo de divulgação e agendamento.
        </p>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 items-center text-center">
            <div class="p-6">
                <div class="text-purple-500 text-6xl mb-4">1.</div>
                <h4 class="font-bold text-lg mb-2">Você cria e envia.</h4>
                <p class="text-sm text-stone-400">Você nos envia seus flashs com detalhes, preço e disponibilidade.</p>
            </div>
            <div class="hidden lg:block text-center text-5xl">➡️</div>
            <div class="p-6">
                <div class="text-purple-500 text-6xl mb-4">2.</div>
                <h4 class="font-bold text-lg mb-2">Nós vendemos.</h4>
                <p class="text-sm text-stone-400">Seus flashs são publicados e o cliente pode agendar e pagar diretamente na plataforma.</p>
            </div>
            <div class="hidden lg:block text-center text-5xl">➡️</div>
            <div class="p-6">
                <div class="text-purple-500 text-6xl mb-4">3.</div>
                <h4 class="font-bold text-lg mb-2">Nós confirmamos.</h4>
                <p class="text-sm text-stone-400">O cliente recebe a confirmação e uma lista de cuidados pré e pós-tatuagem.</p>
            </div>
            <div class="hidden lg:block text-center text-5xl">➡️</div>
            <div class="p-6">
                <div class="text-purple-500 text-6xl mb-4">4.</div>
                <h4 class="font-bold text-lg mb-2">Você tatua.</h4>
                <p class="text-sm text-stone-400">Você recebe o agendamento já confirmado e pago, com todos os detalhes prontos.</p>
            </div>
        </div>
    </section>
    
    <section id="marketplace" class="container mx-auto px-6 py-16">
        <h3 class="text-3xl font-bold text-center mb-10">Marketplace: Uma prévia do que está por vir</h3>
        <p class="text-center text-lg max-w-3xl mx-auto mb-12">
            Esta é uma simulação de como o seu trabalho será apresentado para clientes em nossa plataforma. Explore os flashs e veja como a experiência de usuário é simples e intuitiva, valorizando cada detalhe da sua arte.
        </p>
        <div id="flash-gallery" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            </div>
    </section>

    <div id="flash-modal" class="flash-modal flex items-center justify-center">
        <div class="bg-zinc-900 p-8 rounded-lg max-w-lg w-full">
            <h4 id="modal-title" class="text-2xl font-bold mb-2"></h4>
            <p id="modal-artist" class="text-sm text-stone-400 mb-4"></p>
            <div class="flex justify-center mb-6">
                <img id="modal-image" src="" alt="Flash Tattoo" class="rounded-lg max-h-80 w-auto">
            </div>
            <p id="modal-description" class="text-stone-300 mb-2"></p>
            <p id="modal-style" class="text-sm text-stone-300 mb-1"></p>
            <p id="modal-size" class="text-sm text-stone-300 mb-1"></p>
            <p id="modal-placement" class="text-sm text-stone-300 mb-4"></p>
            <p id="modal-price" class="text-lg font-bold text-purple-500 mb-4"></p>
            <button id="close-modal" class="w-full bg-purple-800 text-white py-2 rounded-md hover:bg-purple-700 transition-colors">Fechar</button>
        </div>
    </div>
    
    <section id="vantagens" class="bg-zinc-900 py-16 px-6">
        <div class="container mx-auto">
            <h3 class="text-3xl font-bold text-center mb-10">Vantagens de ser um parceiro</h3>
            <p class="text-center text-lg max-w-3xl mx-auto mb-12">
                Ao se juntar à Tattoo Rio Flash, você ganha acesso a uma série de benefícios que impulsionarão sua carreira, sem a preocupação com os custos iniciais.
            </p>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="p-6 rounded-lg bg-zinc-950 text-center">
                    <span class="text-3xl mb-2 block">⭐</span>
                    <h4 class="font-bold mb-2">Mais visibilidade</h4>
                    <p class="text-sm text-stone-400">Seus flashs em uma vitrine exclusiva para a audiência carioca.</p>
                </div>
                <div class="p-6 rounded-lg bg-zinc-950 text-center">
                    <span class="text-3xl mb-2 block">⏳</span>
                    <h4 class="font-bold mb-2">Tempo livre</h4>
                    <p class="text-sm text-stone-400">Foco total no que você faz de melhor: a arte.</p>
                </div>
                <div class="p-6 rounded-lg bg-zinc-950 text-center">
                    <span class="text-3xl mb-2 block">💎</span>
                    <h4 class="font-bold mb-2">Curadoria e Qualidade</h4>
                    <p class="text-sm text-stone-400">Você estará ao lado dos melhores artistas da cidade.</p>
                </div>
                <div class="p-6 rounded-lg bg-zinc-950 text-center">
                    <span class="text-3xl mb-2 block">🚀</span>
                    <h4 class="font-bold mb-2">Crescimento sem esforço</h4>
                    <p class="text-sm text-stone-400">Deixe a parte chata do marketing com a gente.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="contato" class="bg-zinc-800 text-white py-16 px-6 text-center">
        <h3 class="text-3xl font-bold mb-4">Vamos juntos revolucionar o mercado de flashs do RJ.</h3>
        <p class="text-lg max-w-2xl mx-auto mb-8">
            Nossa missão é criar uma comunidade de sucesso. Mande uma mensagem para nós e seja um dos primeiros parceiros.
        </p>
        <a href="https://instagram.com/[seu-perfil]" target="_blank" class="bg-purple-500 text-white font-bold py-3 px-8 rounded-full hover:bg-purple-400 transition-colors">Fale com a gente!</a>
    </section>

    <footer class="bg-zinc-900 text-stone-400 text-center py-6 px-6">
        <p>&copy; 2024 Tattoo Rio Flash. Todos os direitos reservados.</p>
    </footer>

    <script>
        const flashes = [
            {
                id: 1,
                title: "Onda de Ukiyo-e",
                artist: "Renata C.",
                description: "Uma delicada onda em estilo japonês, perfeita para braços ou tornozelos.",
                style: "Oriental",
                size: "10x15 cm",
                placement: "Antebraço ou panturrilha",
                price: "R$ 450,00",
                image: "https://placehold.co/400x400/1a1a1a/4a4a4a?text=Flash+1"
            },
            {
                id: 2,
                title: "Coração Old School",
                artist: "Tatuador do Beco",
                description: "Um clássico coração com adaga, vibrante e cheio de atitude.",
                style: "Old School",
