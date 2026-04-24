<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>W. H. S. Construcciones Imaginarias</title>
    <!-- Tailwind CSS para diseño moderno -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome para iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;900&display=swap');
        
        :root {
            --brand-orange: #ff6b00;
            --brand-dark: #0a0a0a;
        }

        body {
            font-family: 'Outfit', sans-serif;
            scroll-behavior: smooth;
            background-color: #ffffff;
        }

        /* Hero con tipografía gigante */
        .hero-title {
            font-size: clamp(4rem, 18vw, 12rem);
            line-height: 0.8;
            letter-spacing: -0.05em;
            font-weight: 900;
            text-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .hero-pattern {
            background-color: var(--brand-dark);
            background-image: 
                linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.8)),
                url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .orange-gradient {
            background: linear-gradient(135deg, #ff6b00 0%, #ff9e00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Tarjetas de servicios ultra-llamativas */
        .service-card {
            transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(0,0,0,0.05);
            background: white;
        }

        .service-card:hover {
            transform: translateY(-15px) scale(1.02);
            box-shadow: 0 40px 80px -15px rgba(0,0,0,0.1);
        }

        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: opacity 0.5s ease;
            z-index: 0;
        }

        .card-herreria:hover::before { background: linear-gradient(180deg, transparent 0%, rgba(255, 107, 0, 0.08) 100%); opacity: 1; }
        .card-durlock:hover::before { background: linear-gradient(180deg, transparent 0%, rgba(31, 41, 55, 0.08) 100%); opacity: 1; }
        .card-electricidad:hover::before { background: linear-gradient(180deg, transparent 0%, rgba(234, 179, 8, 0.08) 100%); opacity: 1; }
        .card-plomeria:hover::before { background: linear-gradient(180deg, transparent 0%, rgba(37, 99, 235, 0.08) 100%); opacity: 1; }

        .glass-effect {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        @keyframes reveal {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .animate-reveal {
            animation: reveal 1s cubic-bezier(0.23, 1, 0.32, 1) forwards;
        }

        .services-bg {
            background-color: #fafafa;
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ff6b00' fill-opacity='0.03'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2v-4h4v-2h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2v-4h4v-2H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }

        .btn-glow:hover {
            box-shadow: 0 0 20px rgba(255, 107, 0, 0.6);
        }
    </style>
</head>
<body class="text-gray-900">

    <!-- Navegación -->
    <nav class="fixed w-full z-50 bg-white/95 backdrop-blur-xl border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-24 items-center">
                <div class="flex items-center">
                    <div class="bg-black text-white px-4 py-1 rounded-lg font-black text-4xl tracking-tighter mr-3 shadow-xl">WHS</div>
                    <div class="hidden sm:block border-l-2 border-gray-100 pl-4">
                        <span class="text-xs uppercase font-black tracking-[0.4em] text-[#ff6b00] block leading-none">Construcciones</span>
                        <span class="text-xs uppercase font-bold tracking-[0.4em] text-gray-400 block mt-1">Imaginarias</span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-12">
                    <a href="#inicio" class="text-xs font-black uppercase tracking-widest text-gray-900 hover:text-[#ff6b00] transition-colors">Inicio</a>
                    <a href="#servicios" class="text-xs font-black uppercase tracking-widest text-gray-900 hover:text-[#ff6b00] transition-colors">Servicios</a>
                    <a href="#contacto" class="bg-[#ff6b00] text-white px-10 py-4 rounded-full font-black text-xs uppercase tracking-widest hover:bg-black transition-all shadow-xl hover:shadow-orange-500/30">Presupuesto Ya</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="hero-pattern h-screen flex items-center justify-center relative pt-20 overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 text-center z-10 animate-reveal">
            <h2 class="text-[#ff6b00] font-black uppercase tracking-[0.6em] text-sm mb-6 bg-black/40 inline-block px-4 py-2 rounded-full backdrop-blur-md">Ushuaia, Tierra del Fuego</h2>
            <h1 class="hero-title text-white mb-2">W.H.S.</h1>
            <p class="text-3xl md:text-6xl font-black text-white uppercase tracking-tighter mb-10 drop-shadow-2xl">
                CONSTRUCCIÓN <span class="orange-gradient underline decoration-orange-500/30">TOTAL</span>
            </p>
            <p class="text-lg md:text-2xl text-gray-200 mb-14 max-w-3xl mx-auto font-medium leading-relaxed drop-shadow-md">
                Estructuras de acero, acabados en seco e instalaciones de alta complejidad. Llevamos la ingeniería al siguiente nivel.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-8">
                <a href="#contacto" class="px-14 py-6 bg-[#ff6b00] text-white font-black rounded-2xl hover:bg-white hover:text-black transition-all text-sm uppercase tracking-widest shadow-[0_20px_50px_rgba(255,107,0,0.3)] hover:-translate-y-1">Empezar Obra</a>
                <a href="#servicios" class="px-14 py-6 glass-effect text-white font-black rounded-2xl hover:bg-white/20 transition-all text-sm uppercase tracking-widest border border-white/40 hover:-translate-y-1">Nuestra Experiencia</a>
            </div>
        </div>

        <!-- Decoración de construcción -->
        <div class="absolute bottom-0 right-0 p-10 opacity-20 hidden lg:block">
            <i class="fas fa-drafting-compass text-[20rem] text-white rotate-12"></i>
        </div>
    </section>

    <!-- Servicios Mejorados -->
    <section id="servicios" class="py-32 services-bg">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-24">
                <span class="text-[#ff6b00] font-black uppercase tracking-[0.4em] text-sm block mb-6">Expertos en Ushuaia</span>
                <h2 class="text-6xl font-black text-gray-900 leading-tight">NUESTROS <span class="orange-gradient italic">SERVICIOS</span></h2>
                <p class="text-gray-500 mt-6 max-w-2xl mx-auto text-lg font-medium italic underline decoration-[#ff6b00]/20">Soluciones integrales con la máxima calidad y seguridad.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <!-- Herrería - VIBRANT ORANGE -->
                <div class="service-card card-herreria p-12 rounded-[4rem] group border-l-[12px] border-[#ff6b00]">
                    <div class="flex flex-col lg:flex-row gap-8 items-center lg:items-start">
                        <div class="w-24 h-24 bg-[#ff6b00] text-white rounded-[2rem] flex items-center justify-center flex-shrink-0 shadow-[0_15px_35px_rgba(255,107,0,0.4)] group-hover:scale-110 transition-all duration-500">
                            <i class="fas fa-fire-burner text-4xl"></i>
                        </div>
                        <div class="relative z-10 text-center lg:text-left">
                            <h3 class="text-3xl font-black mb-4 uppercase tracking-tight text-gray-900">Herrería <span class="text-[#ff6b00]">Estructural</span></h3>
                            <p class="text-gray-600 leading-relaxed text-lg mb-6">
                                Diseñamos y fabricamos todo tipo de estructuras metálicas a medida, como rejas, portones, escaleras, parrillas y cerramientos. Priorizamos la resistencia, la seguridad y una terminación estética acorde a cada espacio.
                            </p>
                            <div class="flex flex-wrap gap-2 justify-center lg:justify-start">
                                <span class="px-4 py-2 bg-orange-600 text-white rounded-xl text-xs font-black uppercase tracking-widest shadow-lg shadow-orange-500/20">A Medida</span>
                                <span class="px-4 py-2 bg-gray-900 text-white rounded-xl text-xs font-black uppercase tracking-widest">Resistente</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Durlock - SOPHISTICATED DARK -->
                <div class="service-card card-durlock p-12 rounded-[4rem] group border-l-[12px] border-gray-900">
                    <div class="flex flex-col lg:flex-row gap-8 items-center lg:items-start">
                        <div class="w-24 h-24 bg-gray-900 text-white rounded-[2rem] flex items-center justify-center flex-shrink-0 shadow-[0_15px_35px_rgba(0,0,0,0.3)] group-hover:scale-110 transition-all duration-500">
                            <i class="fas fa-border-all text-4xl"></i>
                        </div>
                        <div class="relative z-10 text-center lg:text-left">
                            <h3 class="text-3xl font-black mb-4 uppercase tracking-tight text-gray-900">Sistema <span class="text-gray-500">Durlock</span></h3>
                            <p class="text-gray-600 leading-relaxed text-lg mb-6">
                                Realizamos instalaciones de paredes, cielorrasos y divisiones interiores con sistema Durlock, ideal para optimizar tiempos de obra y lograr ambientes modernos, funcionales y prolijos.
                            </p>
                            <div class="flex flex-wrap gap-2 justify-center lg:justify-start">
                                <span class="px-4 py-2 bg-gray-900 text-white rounded-xl text-xs font-black uppercase tracking-widest shadow-lg shadow-black/20">Seco & Rápido</span>
                                <span class="px-4 py-2 bg-gray-200 text-gray-800 rounded-xl text-xs font-black uppercase tracking-widest">Moderno</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Electricidad - ELECTRIC YELLOW -->
                <div class="service-card card-electricidad p-12 rounded-[4rem] group border-l-[12px] border-yellow-500">
                    <div class="flex flex-col lg:flex-row gap-8 items-center lg:items-start">
                        <div class="w-24 h-24 bg-yellow-500 text-white rounded-[2rem] flex items-center justify-center flex-shrink-0 shadow-[0_15px_35px_rgba(234,179,8,0.4)] group-hover:scale-110 transition-all duration-500">
                            <i class="fas fa-bolt-lightning text-4xl"></i>
                        </div>
                        <div class="relative z-10 text-center lg:text-left">
                            <h3 class="text-3xl font-black mb-4 uppercase tracking-tight text-gray-900">Electricidad <span class="text-yellow-600">Integral</span></h3>
                            <p class="text-gray-600 leading-relaxed text-lg mb-6">
                                Ofrecemos servicios eléctricos domiciliarios y comerciales, incluyendo instalaciones completas, mantenimiento, ampliaciones y reparación de fallas, siempre cumpliendo con normas de seguridad.
                            </p>
                            <div class="flex flex-wrap gap-2 justify-center lg:justify-start">
                                <span class="px-4 py-2 bg-yellow-500 text-white rounded-xl text-xs font-black uppercase tracking-widest shadow-lg shadow-yellow-500/20">Seguridad</span>
                                <span class="px-4 py-2 bg-gray-900 text-white rounded-xl text-xs font-black uppercase tracking-widest">Normas</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Plomería - DEEP BLUE -->
                <div class="service-card card-plomeria p-12 rounded-[4rem] group border-l-[12px] border-blue-600">
                    <div class="flex flex-col lg:flex-row gap-8 items-center lg:items-start">
                        <div class="w-24 h-24 bg-blue-600 text-white rounded-[2rem] flex items-center justify-center flex-shrink-0 shadow-[0_15px_35px_rgba(37,99,235,0.4)] group-hover:scale-110 transition-all duration-500">
                            <i class="fas fa-droplet text-4xl"></i>
                        </div>
                        <div class="relative z-10 text-center lg:text-left">
                            <h3 class="text-3xl font-black mb-4 uppercase tracking-tight text-gray-900">Plomería <span class="text-blue-600">Especializada</span></h3>
                            <p class="text-gray-600 leading-relaxed text-lg mb-6">
                                Brindamos soluciones en instalaciones sanitarias, reparación de cañerías, desagües y mantenimiento general, asegurando eficiencia y durabilidad en cada trabajo.
                            </p>
                            <div class="flex flex-wrap gap-2 justify-center lg:justify-start">
                                <span class="px-4 py-2 bg-blue-600 text-white rounded-xl text-xs font-black uppercase tracking-widest shadow-lg shadow-blue-500/20">Eficiencia</span>
                                <span class="px-4 py-2 bg-gray-900 text-white rounded-xl text-xs font-black uppercase tracking-widest">Termofusión</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Franja de Imágenes de Construcción Real -->
    <section class="grid grid-cols-2 md:grid-cols-4 h-[300px] overflow-hidden">
        <div class="relative group overflow-hidden">
            <img src="https://images.unsplash.com/photo-1513467535987-fd81bc7d62f8?auto=format&fit=crop&w=600&q=80" alt="Estructura metálica" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 filter brightness-50 group-hover:brightness-100">
            <div class="absolute inset-0 flex items-center justify-center text-white opacity-0 group-hover:opacity-100 transition-opacity">
                <span class="font-black uppercase tracking-widest text-sm">Herrería</span>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src="https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=600&q=80" alt="Construcción en seco" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 filter brightness-50 group-hover:brightness-100">
            <div class="absolute inset-0 flex items-center justify-center text-white opacity-0 group-hover:opacity-100 transition-opacity">
                <span class="font-black uppercase tracking-widest text-sm">Durlock</span>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=600&q=80" alt="Instalación eléctrica" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 filter brightness-50 group-hover:brightness-100">
            <div class="absolute inset-0 flex items-center justify-center text-white opacity-0 group-hover:opacity-100 transition-opacity">
                <span class="font-black uppercase tracking-widest text-sm">Electricidad</span>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src="https://images.unsplash.com/photo-1607472586893-edb57bdc0e39?auto=format&fit=crop&w=600&q=80" alt="Plomería cañerías" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 filter brightness-50 group-hover:brightness-100">
            <div class="absolute inset-0 flex items-center justify-center text-white opacity-0 group-hover:opacity-100 transition-opacity">
                <span class="font-black uppercase tracking-widest text-sm">Plomería</span>
            </div>
        </div>
    </section>

    <!-- Sección de Contacto -->
    <section id="contacto" class="py-32 bg-white relative">
        <div class="max-w-7xl mx-auto px-6">
            <div class="bg-[#0a0a0a] rounded-[5rem] overflow-hidden shadow-[0_50px_100px_-20px_rgba(0,0,0,0.5)] flex flex-col lg:flex-row border border-white/5">
                <!-- Info Lateral -->
                <div class="lg:w-2/5 p-16 lg:p-20 bg-[#ff6b00] text-white relative overflow-hidden">
                    <!-- Background sutil de planos -->
                    <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80" class="absolute inset-0 opacity-10 object-cover scale-150 rotate-12">
                    
                    <h2 class="text-5xl lg:text-7xl font-black mb-10 leading-none tracking-tighter relative z-10">PLANIFICÁ <br>EL ÉXITO.</h2>
                    <p class="text-orange-100 mb-16 text-xl font-semibold opacity-90 relative z-10">No dejes tu inversión al azar. En W.H.S. construimos con la seguridad de los expertos.</p>
                    
                    <div class="space-y-10 relative z-10">
                        <div class="flex items-center gap-8 group">
                            <div class="w-16 h-16 bg-white/20 rounded-2xl flex items-center justify-center group-hover:scale-110 transition-transform">
                                <i class="fab fa-whatsapp text-3xl"></i>
                            </div>
                            <div>
                                <p class="text-xs font-black uppercase tracking-widest opacity-70">Línea Directa</p>
                                <span class="text-2xl font-black">2901 626035</span>
                            </div>
                        </div>
                        <div class="flex items-center gap-8 group">
                            <div class="w-16 h-16 bg-white/20 rounded-2xl flex items-center justify-center group-hover:scale-110 transition-transform">
                                <i class="fas fa-compass text-3xl"></i>
                            </div>
                            <div>
                                <p class="text-xs font-black uppercase tracking-widest opacity-70">Sede Central</p>
                                <span class="text-2xl font-black uppercase">Ushuaia, TDF</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Formulario -->
                <div class="lg:w-3/5 p-12 md:p-20 bg-white">
                    <form id="formWS" class="grid grid-cols-1 gap-10">
                        <div class="relative group">
                            <input type="text" id="nombre" required 
                                class="w-full px-0 py-4 bg-transparent border-b-2 border-gray-100 focus:border-[#ff6b00] transition-all font-black text-2xl outline-none peer"
                                placeholder=" ">
                            <label class="absolute left-0 top-4 text-gray-400 font-bold uppercase tracking-widest text-xs pointer-events-none transition-all peer-focus:-top-4 peer-focus:text-[#ff6b00] peer-[:not(:placeholder-shown)]:-top-4">Nombre Completo</label>
                        </div>
                        
                        <div class="relative">
                            <label class="block text-xs font-black uppercase tracking-widest text-gray-400 mb-4">Seleccione Servicio</label>
                            <div class="grid grid-cols-2 gap-4">
                                <button type="button" onclick="setServicio('Herrería')" class="serv-btn px-6 py-4 border-2 border-gray-100 rounded-2xl font-black text-xs uppercase tracking-widest hover:border-[#ff6b00] transition-all">Herrería</button>
                                <button type="button" onclick="setServicio('Durlock')" class="serv-btn px-6 py-4 border-2 border-gray-100 rounded-2xl font-black text-xs uppercase tracking-widest hover:border-[#ff6b00] transition-all">Durlock</button>
                                <button type="button" onclick="setServicio('Electricidad')" class="serv-btn px-6 py-4 border-2 border-gray-100 rounded-2xl font-black text-xs uppercase tracking-widest hover:border-[#ff6b00] transition-all">Electricidad</button>
                                <button type="button" onclick="setServicio('Plomería')" class="serv-btn px-6 py-4 border-2 border-gray-100 rounded-2xl font-black text-xs uppercase tracking-widest hover:border-[#ff6b00] transition-all">Plomería</button>
                            </div>
                            <input type="hidden" id="servicio_val" required>
                        </div>

                        <div class="relative group">
                            <textarea id="descripcion" rows="3" 
                                class="w-full px-0 py-4 bg-transparent border-b-2 border-gray-100 focus:border-[#ff6b00] transition-all font-bold text-lg outline-none peer"
                                placeholder=" "></textarea>
                            <label class="absolute left-0 top-4 text-gray-400 font-bold uppercase tracking-widest text-xs pointer-events-none transition-all peer-focus:-top-4 peer-focus:text-[#ff6b00] peer-[:not(:placeholder-shown)]:-top-4">Resumen de la Obra</label>
                        </div>

                        <button type="submit" 
                            class="w-full bg-[#25D366] hover:bg-black text-white font-black py-8 rounded-[2rem] shadow-2xl flex items-center justify-center gap-6 transition-all text-sm uppercase tracking-[0.4em] transform hover:-translate-y-2 btn-glow">
                            <i class="fab fa-whatsapp text-3xl"></i>
                            INICIAR CONSULTA TÉCNICA
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-24 bg-[#0a0a0a]">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center mb-16 gap-10">
                <div class="bg-white text-black px-6 py-2 rounded-xl font-black text-5xl tracking-tighter">WHS</div>
                <div class="flex gap-10">
                    <a href="#inicio" class="text-white font-black uppercase tracking-widest text-xs hover:text-[#ff6b00] transition-colors">Inicio</a>
                    <a href="#servicios" class="text-white font-black uppercase tracking-widest text-xs hover:text-[#ff6b00] transition-colors">Servicios</a>
                    <a href="#contacto" class="text-white font-black uppercase tracking-widest text-xs hover:text-[#ff6b00] transition-colors">Contacto</a>
                </div>
            </div>
            <div class="border-t border-white/5 pt-12 text-center md:text-left flex flex-col md:flex-row justify-between items-center gap-6">
                <p class="text-gray-500 text-xs font-bold tracking-[0.5em] uppercase">W. H. S. Construcciones Imaginarias &copy; 2024</p>
                <div class="flex gap-6 text-gray-400">
                    <i class="fab fa-instagram text-2xl hover:text-white transition-colors cursor-pointer"></i>
                    <i class="fab fa-facebook text-2xl hover:text-white transition-colors cursor-pointer"></i>
                </div>
            </div>
        </div>
    </footer>

    <script>
        let selectedServ = "";

        function setServicio(nombre) {
            selectedServ = nombre;
            document.getElementById('servicio_val').value = nombre;
            
            // Estilizar botones
            document.querySelectorAll('.serv-btn').forEach(btn => {
                btn.classList.remove('bg-[#ff6b00]', 'text-white', 'border-[#ff6b00]', 'shadow-lg');
                if(btn.innerText.toLowerCase() === nombre.toLowerCase()) {
                    btn.classList.add('bg-[#ff6b00]', 'text-white', 'border-[#ff6b00]', 'shadow-lg');
                }
            });
        }

        document.getElementById('formWS').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const nombre = document.getElementById('nombre').value;
            const servicio = selectedServ || "Consulta General";
            const desc = document.getElementById('descripcion').value;
            const tel = "2901626035";

            let msj = `*W.H.S. CONSTRUCCIONES* 🏗️%0A`;
            msj += `--------------------------%0A`;
            msj += `*Cliente:* ${nombre}%0A`;
            msj += `*Servicio:* ${servicio}%0A`;
            
            if(desc.trim() !== "") {
                msj += `*Detalles:* ${desc}%0A`;
            }
            
            msj += `--------------------------%0A`;
            msj += `_Solicitud desde Sitio Web Oficial_`;

            const url = `https://wa.me/${tel}?text=${msj}`;
            window.open(url, '_blank');
        });
    </script>
</body>
</html>
