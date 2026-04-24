<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>W. H. S. Construcciones Imaginarias | Ushuaia</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;900&display=swap');
        
        :root {
            --brand-orange: #ff6b00;
            --brand-dark: #0a0a0a;
        }

        body {
            font-family: 'Outfit', sans-serif;
            overflow-x: hidden;
        }

        /* Hero Responsive */
        .hero-title {
            font-size: clamp(3rem, 15vw, 10rem);
            line-height: 0.85;
            letter-spacing: -0.05em;
            font-weight: 900;
        }

        .hero-pattern {
            background-color: var(--brand-dark);
            background-image: 
                linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.9)),
                url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: scroll;
        }

        @media (min-width: 1024px) {
            .hero-pattern { background-attachment: fixed; }
        }

        .orange-gradient {
            background: linear-gradient(135deg, #ff6b00 0%, #ff9e00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Tarjetas de servicios */
        .service-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border: 1px solid rgba(0,0,0,0.05);
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 30px 60px -12px rgba(0,0,0,0.1);
        }

        /* Utilidades de Diseño */
        .glass-effect {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        /* Animación de entrada */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease-out;
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* Botones de selección de servicio */
        .serv-btn {
            transition: all 0.3s ease;
            cursor: pointer;
            border-width: 2px;
        }

        .serv-btn.active {
            background-color: #ff6b00;
            color: white;
            border-color: #ff6b00;
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(255, 107, 0, 0.3);
        }
    </style>
</head>
<body class="bg-white text-gray-900">

    <!-- Navegación -->
    <nav class="fixed w-full z-[100] bg-white/95 backdrop-blur-md border-b border-gray-100 transition-all duration-300 h-20" id="mainNav">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center">
                    <div class="bg-black text-white px-3 py-1 rounded-lg font-black text-2xl tracking-tighter mr-3">WHS</div>
                    <div class="hidden xs:block border-l-2 border-gray-100 pl-3">
                        <span class="text-[10px] uppercase font-black tracking-widest text-[#ff6b00] block">Construcción</span>
                        <span class="text-[10px] uppercase font-bold tracking-widest text-gray-400 block">Ushuaia</span>
                    </div>
                </div>
                
                <!-- Links Desktop -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#inicio" class="text-xs font-black uppercase tracking-widest hover:text-[#ff6b00] transition-colors">Inicio</a>
                    <a href="#servicios" class="text-xs font-black uppercase tracking-widest hover:text-[#ff6b00] transition-colors">Servicios</a>
                    <a href="#contacto" class="bg-[#ff6b00] text-white px-8 py-3 rounded-full font-black text-xs uppercase tracking-widest hover:bg-black transition-all shadow-lg">Presupuesto</a>
                </div>

                <!-- Botón WhatsApp (Mobile) -->
                <a href="https://wa.me/2901626035" class="md:hidden bg-[#25D366] text-white p-3 rounded-full shadow-lg">
                    <i class="fab fa-whatsapp text-2xl"></i>
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="hero-pattern min-h-screen flex items-center justify-center relative px-4 py-20 overflow-hidden">
        <div class="max-w-7xl mx-auto text-center z-10">
            <div class="reveal active">
                <h2 class="text-[#ff6b00] font-black uppercase tracking-[0.4em] text-[10px] md:text-sm mb-4 md:mb-6 bg-black/40 inline-block px-4 py-2 rounded-full backdrop-blur-md">Ushuaia • Tierra del Fuego</h2>
                <h1 class="hero-title text-white">W.H.S.</h1>
                <p class="text-2xl md:text-5xl lg:text-6xl font-black text-white uppercase tracking-tighter mb-8">
                    CONSTRUCCIÓN <span class="orange-gradient italic">PROFESIONAL</span>
                </p>
                <p class="text-base md:text-xl text-gray-300 mb-10 max-w-2xl mx-auto font-medium leading-relaxed px-4">
                    Expertos en herrería estructural, sistemas Durlock e instalaciones integrales. Soluciones sólidas para climas extremos.
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4 px-6">
                    <a href="#contacto" class="w-full sm:w-auto px-10 py-5 bg-[#ff6b00] text-white font-black rounded-2xl hover:bg-white hover:text-black transition-all text-xs uppercase tracking-widest shadow-xl text-center">Contactar Ahora</a>
                    <a href="#servicios" class="w-full sm:w-auto px-10 py-5 glass-effect text-white font-black rounded-2xl hover:bg-white/20 transition-all text-xs uppercase tracking-widest border border-white/30 text-center">Nuestros Servicios</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Servicios -->
    <section id="servicios" class="py-24 bg-gray-50 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-20 reveal">
                <span class="text-[#ff6b00] font-black uppercase tracking-widest text-xs block mb-4">Especialidades</span>
                <h2 class="text-4xl md:text-6xl font-black text-gray-900 leading-tight">QUÉ <span class="text-orange-500 italic">OFRECEMOS</span></h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:gap-10">
                <!-- Herrería -->
                <div class="service-card bg-white p-8 md:p-12 rounded-[2.5rem] border-l-8 border-orange-500 reveal">
                    <div class="w-16 h-16 bg-orange-500/10 text-orange-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-hammer text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase">Herrería</h3>
                    <p class="text-gray-600 leading-relaxed">Diseñamos y fabricamos todo tipo de estructuras metálicas a medida, como rejas, portones, escaleras, parrillas y cerramientos. Priorizamos la resistencia, la seguridad y una terminación estética acorde a cada espacio.</p>
                </div>

                <!-- Durlock -->
                <div class="service-card bg-white p-8 md:p-12 rounded-[2.5rem] border-l-8 border-gray-800 reveal">
                    <div class="w-16 h-16 bg-gray-800/10 text-gray-800 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-layer-group text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase">Durlock</h3>
                    <p class="text-gray-600 leading-relaxed">Realizamos instalaciones de paredes, cielorrasos y divisiones interiores con sistema Durlock, ideal para optimizar tiempos de obra y lograr ambientes modernos, funcionales y prolijos.</p>
                </div>

                <!-- Electricidad -->
                <div class="service-card bg-white p-8 md:p-12 rounded-[2.5rem] border-l-8 border-yellow-500 reveal">
                    <div class="w-16 h-16 bg-yellow-500/10 text-yellow-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-bolt text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase">Electricidad</h3>
                    <p class="text-gray-600 leading-relaxed">Ofrecemos servicios eléctricos domiciliarios y comerciales, incluyendo instalaciones completas, mantenimiento, ampliaciones y reparación de fallas, siempre cumpliendo con normas de seguridad.</p>
                </div>

                <!-- Plomería -->
                <div class="service-card bg-white p-8 md:p-12 rounded-[2.5rem] border-l-8 border-blue-600 reveal">
                    <div class="w-16 h-16 bg-blue-600/10 text-blue-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-faucet text-2xl"></i>
                    </div>
                    <h3 class="text-2xl font-black mb-4 uppercase">Plomería</h3>
                    <p class="text-gray-600 leading-relaxed">Brindamos soluciones en instalaciones sanitarias, reparación de cañerías, desagües y mantenimiento general, asegurando eficiencia y durabilidad en cada trabajo.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="py-24 px-4 bg-white">
        <div class="max-w-5xl mx-auto">
            <div class="bg-gray-900 rounded-[3rem] overflow-hidden shadow-2xl flex flex-col md:flex-row reveal">
                <!-- Info -->
                <div class="md:w-1/3 bg-[#ff6b00] p-10 text-white flex flex-col justify-center">
                    <h3 class="text-4xl font-black mb-6 uppercase tracking-tighter">HABLEMOS</h3>
                    <p class="font-bold opacity-90 mb-10 text-sm uppercase tracking-widest">Presupuestos sin cargo en toda la ciudad de Ushuaia.</p>
                    
                    <div class="space-y-6">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 bg-white/20 rounded-lg flex items-center justify-center">
                                <i class="fab fa-whatsapp text-xl"></i>
                            </div>
                            <span class="font-black">2901 626035</span>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 bg-white/20 rounded-lg flex items-center justify-center">
                                <i class="fas fa-map-marker-alt text-xl"></i>
                            </div>
                            <span class="font-black uppercase text-xs tracking-widest">Ushuaia, TDF</span>
                        </div>
                    </div>
                </div>

                <!-- Formulario -->
                <div class="md:w-2/3 p-8 md:p-12 bg-white">
                    <form id="wsForm" class="space-y-6">
                        <div>
                            <label class="block text-[10px] font-black uppercase tracking-widest text-gray-400 mb-2">Tu Nombre</label>
                            <input type="text" id="nombre" required 
                                class="w-full bg-gray-50 border-2 border-gray-100 rounded-2xl p-4 outline-none focus:border-[#ff6b00] transition-all font-bold"
                                placeholder="Escribe tu nombre completo">
                        </div>

                        <div>
                            <label class="block text-[10px] font-black uppercase tracking-widest text-gray-400 mb-3">¿Qué servicio necesitas? (Selecciona uno)</label>
                            <div class="grid grid-cols-2 gap-3" id="serviciosGrid">
                                <div onclick="selectService(this, 'Herrería')" class="serv-btn border-gray-100 bg-gray-50 rounded-2xl p-4 text-center">
                                    <i class="fas fa-hammer block mb-2 text-xl"></i>
                                    <span class="text-[10px] font-black uppercase tracking-tighter">Herrería</span>
                                </div>
                                <div onclick="selectService(this, 'Durlock')" class="serv-btn border-gray-100 bg-gray-50 rounded-2xl p-4 text-center">
                                    <i class="fas fa-layer-group block mb-2 text-xl"></i>
                                    <span class="text-[10px] font-black uppercase tracking-tighter">Durlock</span>
                                </div>
                                <div onclick="selectService(this, 'Electricidad')" class="serv-btn border-gray-100 bg-gray-50 rounded-2xl p-4 text-center">
                                    <i class="fas fa-bolt block mb-2 text-xl"></i>
                                    <span class="text-[10px] font-black uppercase tracking-tighter">Electricidad</span>
                                </div>
                                <div onclick="selectService(this, 'Plomería')" class="serv-btn border-gray-100 bg-gray-50 rounded-2xl p-4 text-center">
                                    <i class="fas fa-faucet block mb-2 text-xl"></i>
                                    <span class="text-[10px] font-black uppercase tracking-tighter">Plomería</span>
                                </div>
                            </div>
                            <!-- Input oculto para validación de formulario -->
                            <input type="hidden" id="servicio_input" required>
                        </div>

                        <div>
                            <label class="block text-[10px] font-black uppercase tracking-widest text-gray-400 mb-2">Descripción del trabajo</label>
                            <textarea id="mensaje" rows="3" 
                                class="w-full bg-gray-50 border-2 border-gray-100 rounded-2xl p-4 outline-none focus:border-[#ff6b00] transition-all font-bold" 
                                placeholder="Cuéntanos brevemente qué necesitas hacer..."></textarea>
                        </div>

                        <button type="submit" class="w-full bg-[#25D366] text-white py-6 rounded-[2rem] font-black uppercase tracking-widest text-xs hover:bg-black transition-all shadow-xl flex items-center justify-center gap-3 transform hover:scale-[1.02]">
                            <i class="fab fa-whatsapp text-2xl"></i>
                            Solicitar Presupuesto
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-950 py-12 px-4 text-center">
        <div class="max-w-7xl mx-auto">
            <div class="inline-block bg-white text-black px-4 py-1 rounded-lg font-black text-2xl mb-6">WHS</div>
            <p class="text-gray-500 text-[10px] font-bold uppercase tracking-[0.5em]">Construcciones Imaginarias • Ushuaia 2024</p>
        </div>
    </footer>

    <script>
        // Scroll Reveal
        function reveal() {
            var reveals = document.querySelectorAll(".reveal");
            for (var i = 0; i < reveals.length; i++) {
                var windowHeight = window.innerHeight;
                var elementTop = reveals[i].getBoundingClientRect().top;
                var elementVisible = 100;
                if (elementTop < windowHeight - elementVisible) {
                    reveals[i].classList.add("active");
                }
            }
        }
        window.addEventListener("scroll", reveal);

        // Selección de Servicio
        let currentSelected = null;
        function selectService(element, name) {
            // Quitar clase activa de todos los botones en el grid
            document.querySelectorAll('.serv-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            
            // Añadir clase activa al seleccionado
            element.classList.add('active');
            
            // Guardar valor
            document.getElementById('servicio_input').value = name;
            currentSelected = name;
        }

        // Envío WhatsApp
        document.getElementById('wsForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const nombre = document.getElementById('nombre').value;
            const msg = document.getElementById('mensaje').value;
            const serv = document.getElementById('servicio_input').value;
            const tel = "5492901626035";

            if(!serv) {
                alert("Por favor, selecciona un servicio de la lista.");
                return;
            }

            let text = `*W.H.S. CONSTRUCCIONES*%0A`;
            text += `---------------------------%0A`;
            text += `*Cliente:* ${nombre}%0A`;
            text += `*Servicio:* ${serv}%0A`;
            if(msg.trim() !== "") {
                text += `*Detalles:* ${msg}%0A`;
            }
            text += `---------------------------%0A`;
            text += `_Consulta enviada desde la web_`;

            window.open(`https://wa.me/${tel}?text=${text}`, '_blank');
        });

        // Cambio de estilo Nav al scrollear
        window.addEventListener('scroll', () => {
            const nav = document.getElementById('mainNav');
            if (window.scrollY > 50) {
                nav.classList.add('shadow-md', 'h-16');
                nav.classList.remove('h-20');
            } else {
                nav.classList.remove('shadow-md', 'h-16');
                nav.classList.add('h-20');
            }
        });
    </script>
</body>
</html>
