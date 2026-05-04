<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Clover | Transformación Digital</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .hero-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.75)), url('realistic_background.png');
            background-size: cover;
            background-position: center;
        }
        .clover-card:hover {
            transform: translateY(-5px);
            border-color: #10b981;
        }
        /* Estilo para que los logos de clientes se vean profesionales */
        .client-logo {
            filter: grayscale(100%);
            opacity: 0.7;
            transition: all 0.4s ease;
        }
        .client-logo:hover {
            filter: grayscale(0%);
            opacity: 1;
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans">

    <nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-md shadow-sm border-b border-slate-100">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="logo.png" alt="Digital Clover Logo" class="h-10 w-auto">
                <span class="text-2xl font-bold text-emerald-600 tracking-tight">Digital Clover</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#servicios" class="hover:text-emerald-600 transition">Servicios</a>
                <a href="#clientes" class="hover:text-emerald-600 transition">Clientes</a>
                <a href="#contacto" class="hover:text-emerald-600 transition">Contacto</a>
            </div>
            <button class="md:hidden text-2xl text-slate-600"><i class="fas fa-bars"></i></button>
        </div>
    </nav>

    <header class="hero-bg h-[85vh] flex items-center text-white text-center px-6">
        <div class="container mx-auto max-w-4xl">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">Impulsamos tu Éxito con Tecnología de Vanguardia</h1>
            <p class="text-lg md:text-xl mb-8 text-slate-200">Llevamos la Transformación Digital a cada rincón de tu empresa con soluciones inteligentes y procesos optimizados.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#servicios" class="bg-emerald-600 hover:bg-emerald-700 text-white px-8 py-3 rounded-full font-semibold transition text-lg shadow-lg shadow-emerald-900/20">Nuestros Servicios</a>
                <a href="https://wa.me/593979267019" class="bg-white/10 hover:bg-white/20 backdrop-blur-sm border border-white/30 px-8 py-3 rounded-full font-semibold transition text-lg">Contactar Ahora</a>
            </div>
        </div>
    </header>

    <section id="servicios" class="py-20 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Soluciones Integrales</h2>
            <div class="w-20 h-1 bg-emerald-500 mx-auto mb-12"></div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="p-8 border border-slate-100 rounded-2xl clover-card transition-all duration-300 shadow-sm">
                    <div class="text-emerald-500 text-4xl mb-4"><i class="fas fa-rocket"></i></div>
                    <h3 class="text-xl font-bold mb-2">Transformación Digital</h3>
                    <p class="text-slate-500 text-sm">Modernizamos tu modelo de negocio con las mejores herramientas del mercado.</p>
                </div>
                <div class="p-8 border border-slate-100 rounded-2xl clover-card transition-all duration-300 shadow-sm">
                    <div class="text-emerald-500 text-4xl mb-4"><i class="fas fa-project-diagram"></i></div>
                    <h3 class="text-xl font-bold mb-2">Gestión & Scrum</h3>
                    <p class="text-slate-500 text-sm">Optimización de procesos y agilidad organizacional para equipos de alto rendimiento.</p>
                </div>
                <div class="p-8 border border-slate-100 rounded-2xl clover-card transition-all duration-300 shadow-sm">
                    <div class="text-emerald-500 text-4xl mb-4"><i class="fas fa-cogs"></i></div>
                    <h3 class="text-xl font-bold mb-2">Software & ERP</h3>
                    <p class="text-slate-500 text-sm">Sistemas empresariales personalizados: Facturación, Inventario y Talento Humano.</p>
                </div>
                <div class="p-8 border border-slate-100 rounded-2xl clover-card transition-all duration-300 shadow-sm">
                    <div class="text-emerald-500 text-4xl mb-4"><i class="fas fa-signature"></i></div>
                    <h3 class="text-xl font-bold mb-2">Firmas Electrónicas</h3>
                    <p class="text-slate-500 text-sm">Seguridad y legalidad digital para todos tus documentos corporativos.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="clientes" class="py-20 bg-slate-50">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Empresas que confían en nosotros</h2>
            <p class="text-slate-500 mb-12">Aliados estratégicos en su camino hacia la digitalización</p>
            
            <div class="flex flex-wrap justify-center items-center gap-12 md:gap-24">
                <div class="flex flex-col items-center">
                    <div class="h-24 w-48 flex items-center justify-center mb-4">
                        <img src="logo_central_perk.png" alt="Cafetería Central Perk Cuenca" class="max-h-full max-w-full object-contain client-logo">
                    </div>
                    <span class="text-sm font-semibold text-slate-400 uppercase tracking-widest">Cafetería Central Perk Cuenca</span>
                </div>

                </div>
        </div>
    </section>

    <section class="py-10 bg-white">
        <div class="container mx-auto px-6">
            <div class="bg-slate-900 text-white rounded-3xl p-10 flex flex-col md:flex-row items-center justify-between shadow-2xl">
                <div class="text-left md:w-2/3">
                    <h3 class="text-2xl font-bold mb-4">Soluciones Verticales Especializadas</h3>
                    <p class="text-slate-400">Contamos con sistemas expertos para la gestión de **Restaurantes** y administración de **Citas Médicas**. Optimiza tu operación desde hoy.</p>
                </div>
                <div class="mt-8 md:mt-0">
                    <a href="https://wa.me/593979267019" class="bg-emerald-600 hover:bg-emerald-700 px-8 py-4 rounded-xl font-bold transition-all shadow-lg shadow-emerald-500/20 inline-block">Solicitar Demo</a>
                </div>
            </div>
        </div>
    </section>

    <footer id="contacto" class="bg-slate-900 text-slate-400 py-16">
        <div class="container mx-auto px-6 text-center">
            <div class="flex justify-center items-center space-x-2 mb-8">
                <img src="logo.png" alt="Logo" class="h-10">
                <span class="text-2xl font-bold text-white tracking-tight">Digital Clover</span>
            </div>
            <div class="flex justify-center space-x-6 mb-8 text-xl">
                <a href="#" class="hover:text-emerald-500 transition"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="hover:text-emerald-500 transition"><i class="fab fa-instagram"></i></a>
                <a href="https://wa.me/593979267019" class="hover:text-emerald-500 transition"><i class="fab fa-whatsapp"></i></a>
            </div>
            <p class="text-sm">© 2026 Digital Clover | Cuenca, Ecuador. Innovación que prospera.</p>
        </div>
    </footer>

    <a href="https://wa.me/593979267019" 
       target="_blank" 
       class="fixed bottom-6 right-6 bg-[#25d366] text-white w-16 h-16 rounded-full flex items-center justify-center text-3xl shadow-2xl hover:scale-110 transition-transform z-[100]"
       title="Chatea con nosotros">
        <i class="fab fa-whatsapp"></i>
    </a>

</body>
</html>
