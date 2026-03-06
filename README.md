<!DOCTYPE html>
<html lang="pt-pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gabriel | Cloud & Infrastructure Specialist</title>
    <!-- Tailwind CSS para design moderno e responsivo -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome para ícones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #2563eb);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(226, 232, 240, 0.8);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 leading-relaxed scroll-smooth">

    <!-- Navegação -->
    <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-bold gradient-text uppercase tracking-tighter italic">Gab 2.0</span>
            <div class="space-x-6 text-sm font-medium">
                <a href="#about" class="hover:text-blue-600 transition">Sobre</a>
                <a href="#experience" class="hover:text-blue-600 transition">Experiência</a>
                <a href="#skills" class="hover:text-blue-600 transition">Skills</a>
                <a href="mailto:teu-email-real@gmail.com" class="bg-blue-600 text-white px-4 py-2 rounded-full hover:bg-blue-700 transition">Contacto</a>
            </div>
        </div>
    </nav>

    <!-- Cabeçalho / Seção Hero -->
    <header id="about" class="max-w-5xl mx-auto px-6 py-16 md:py-24 grid md:grid-cols-2 gap-12 items-center">
        <div class="order-2 md:order-1">
            <h1 class="text-5xl md:text-6xl font-extrabold mb-6 tracking-tight">
                Building <span class="gradient-text">Resilient</span> Infrastructure.
            </h1>
            <p class="text-lg text-slate-600 mb-8 max-w-lg">
                Especialista em Infraestrutura e Cloud focado em otimização de operações, cibersegurança e governação de dados. Atualmente a escalar conhecimentos em Microsoft Azure e Inteligência Artificial.
            </p>
            <div class="flex flex-wrap gap-4">
                <a href="#experience" class="bg-slate-900 text-white px-6 py-3 rounded-lg font-semibold hover:bg-slate-800 transition">Ver Projetos</a>
                <div class="flex items-center gap-4 px-4 text-slate-500 border-l border-slate-200">
                    <a href="https://linkedin.com/in/bladek1" target="_blank" class="hover:text-blue-600 transition"><i class="fab fa-linkedin text-2xl"></i></a>
                    <a href="https://github.com/bladek1" target="_blank" class="hover:text-slate-900 transition"><i class="fab fa-github text-2xl"></i></a>
                </div>
            </div>
        </div>
        <div class="order-1 md:order-2 relative">
            <div class="w-64 h-64 md:w-80 md:h-80 mx-auto rounded-3xl overflow-hidden shadow-2xl border-4 border-white rotate-3 hover:rotate-0 transition duration-500">
                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?fit=crop&w=800&q=80" alt="Gabriel" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-700" onerror="this.src='https://ui-avatars.com/api/?name=Gabriel&background=3b82f6&color=fff&size=512'">
            </div>
            <!-- Badge Flutuante -->
            <div class="absolute -bottom-4 -right-4 bg-white p-4 rounded-xl shadow-lg border border-slate-100 flex items-center gap-3 animate-bounce">
                <div class="w-10 h-10 bg-blue-100 rounded-full flex items-center justify-center text-blue-600">
                    <i class="fas fa-cloud"></i>
                </div>
                <div>
                    <p class="text-[10px] text-slate-400 uppercase font-bold leading-none">Status</p>
                    <p class="text-sm font-bold">Azure Focused</p>
                </div>
            </div>
        </div>
    </header>

    <!-- Experiência Profissional -->
    <section id="experience" class="bg-white py-20 border-y border-slate-200">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 flex items-center gap-3">
                <i class="fas fa-briefcase text-blue-600"></i> Experiência Profissional
            </h2>

            <div class="space-y-16">
                <!-- EDP / SU -->
                <div class="relative pl-8 border-l-2 border-blue-600">
                    <div class="absolute -left-2 top-0 w-4 h-4 bg-blue-600 rounded-full"></div>
                    <div class="mb-2">
                        <span class="text-xs font-bold text-blue-600 uppercase tracking-widest">Maio 2024 – Presente</span>
                        <h3 class="text-2xl font-bold">Technical Support & Operational Excellence</h3>
                        <p class="text-slate-500 font-medium">SU Eletricidade (Grupo EDP) | Portugal</p>
                    </div>
                    <ul class="mt-4 space-y-3 text-slate-600">
                        <li class="flex gap-2">
                            <span class="text-blue-500">●</span>
                            <span><strong>Otimização Operacional:</strong> Gestão de dados técnicos e verificação de faturação com 100% de acuidade.</span>
                        </li>
                        <li class="flex gap-2">
                            <span class="text-blue-500">●</span>
                            <span><strong>AI-Assisted Productivity:</strong> Implementação de fluxos de IA Generativa para acelerar relatórios internos.</span>
                        </li>
                        <li class="flex gap-2">
                            <span class="text-blue-500">●</span>
                            <span><strong>Gestão de Incidências:</strong> Resolução de conflitos técnicos complexos seguindo SLAs rigorosos.</span>
                        </li>
                    </ul>
                </div>

                <!-- IMT / FJ -->
                <div class="relative pl-8 border-l-2 border-slate-200">
                    <div class="absolute -left-2 top-0 w-4 h-4 bg-slate-200 rounded-full"></div>
                    <div class="mb-2">
                        <span class="text-xs font-bold text-slate-400 uppercase tracking-widest">2018 – 2021</span>
                        <h3 class="text-2xl font-bold">Analista de Infraestrutura e Redes</h3>
                        <p class="text-slate-500 font-medium">FJ Redempresa (Instituto Mauá de Tecnologia) | Brasil</p>
                    </div>
                    <ul class="mt-4 space-y-3 text-slate-600">
                        <li class="flex gap-2">
                            <span class="text-slate-400">●</span>
                            <span><strong>Gestão de Redes:</strong> Manutenção de infraestrutura de alta disponibilidade e governação de ativos.</span>
                        </li>
                        <li class="flex gap-2">
                            <span class="text-slate-400">●</span>
                            <span><strong>Cibersegurança:</strong> Implementação de firewalls (Blockbit/Fortinet) e auditoria de segurança.</span>
                        </li>
                        <li class="flex gap-2">
                            <span class="text-slate-400">●</span>
                            <span><strong>Suporte N3:</strong> Engenharia de suporte em ambientes críticos Windows, macOS e Linux.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills & Formação -->
    <section id="skills" class="max-w-5xl mx-auto px-6 py-20 grid md:grid-cols-2 gap-16">
        <div>
            <h2 class="text-3xl font-bold mb-8 flex items-center gap-3">
                <i class="fas fa-microchip text-blue-600"></i> Core Skills
            </h2>
            <div class="grid grid-cols-1 gap-4">
                <div class="glass-card p-4 rounded-xl flex items-center justify-between group hover:border-blue-300 transition shadow-sm">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-slate-900 text-white rounded-lg flex items-center justify-center">
                            <i class="fab fa-microsoft text-sm"></i>
                        </div>
                        <span class="font-semibold">Azure Fundamentals</span>
                    </div>
                    <i class="fas fa-check-circle text-blue-500 opacity-0 group-hover:opacity-100 transition"></i>
                </div>
                <div class="glass-card p-4 rounded-xl flex items-center justify-between group hover:border-blue-300 transition shadow-sm">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-slate-900 text-white rounded-lg flex items-center justify-center">
                            <i class="fas fa-shield-alt text-sm"></i>
                        </div>
                        <span class="font-semibold">Cibersegurança & Firewalls</span>
                    </div>
                    <i class="fas fa-check-circle text-blue-500 opacity-0 group-hover:opacity-100 transition"></i>
                </div>
                <div class="glass-card p-4 rounded-xl flex items-center justify-between group hover:border-blue-300 transition shadow-sm">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-slate-900 text-white rounded-lg flex items-center justify-center">
                            <i class="fas fa-robot text-sm"></i>
                        </div>
                        <span class="font-semibold">Prompt Engineering / IA</span>
                    </div>
                    <i class="fas fa-check-circle text-blue-500 opacity-0 group-hover:opacity-100 transition"></i>
                </div>
            </div>
        </div>
        <div>
            <h2 class="text-3xl font-bold mb-8 flex items-center gap-3">
                <i class="fas fa-graduation-cap text-blue-600"></i> Formação
            </h2>
            <div class="bg-blue-600 text-white p-8 rounded-2xl shadow-xl relative overflow-hidden">
                <i class="fas fa-university absolute -bottom-4 -right-4 text-7xl opacity-20"></i>
                <h3 class="text-xl font-bold mb-2">Ciência da Computação</h3>
                <p class="text-blue-100 mb-6">Bacharelado | USCS Brasil</p>
                <div class="inline-block bg-white/20 px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider">
                    Foco em Engenharia de Software
                </div>
            </div>
        </div>
    </section>

    <!-- Rodapé -->
    <footer class="bg-slate-900 text-white py-12">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <p class="text-slate-400 mb-6 font-mono text-sm">gabriel.peak_v2.0_init()</p>
            <div class="flex justify-center gap-8 mb-10">
                <a href="https://linkedin.com/in/bladek1" target="_blank" class="text-slate-400 hover:text-white transition">LinkedIn</a>
                <a href="https://github.com/bladek1" target="_blank" class="text-slate-400 hover:text-white transition">GitHub</a>
                <a href="mailto:teu-email-real@gmail.com" class="text-slate-400 hover:text-white transition">Email</a>
            </div>
            <p class="text-xs text-slate-600">© 2026 Gabriel - Desenvolvido com foco em Resiliência e Azure.</p>
        </div>
    </footer>

</body>
</html>
