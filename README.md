<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESTEMER ABOGADOS | Velázquez 27 Madrid</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;600&display=swap');
        
        body { font-family: 'Inter', sans-serif; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        
        .hero-gradient {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1544654803-b69110bb81e4?auto=format&fit=crop&q=80&w=1920');
            background-size: cover;
            background-position: center;
        }

        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .vintage-filter {
            filter: sepia(0.08) contrast(1.02);
        }

        .juris-note {
            border-left: 4px solid #b45309;
            transition: all 0.3s ease;
        }
        .juris-note:hover {
            background-color: #f8fafc;
            border-left-width: 8px;
        }

        input:focus, select:focus, textarea:focus {
            border-color: #b45309 !important;
            box-shadow: 0 1px 0 0 #b45309;
        }
    </style>
</head>
<body class="bg-slate-50 text-gray-900 vintage-filter">

    <!-- Navegación -->
    <nav class="fixed w-full z-50 bg-white/95 backdrop-blur-md border-b border-gray-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-24 items-center">
                <div class="flex flex-col">
                    <span class="text-2xl font-bold tracking-[0.2em] text-slate-900 uppercase">ESTEMER</span>
                    <span class="text-[10px] text-amber-700 font-bold tracking-[0.3em] uppercase -mt-1">Abogados Senior</span>
                </div>
                <div class="hidden lg:flex space-x-6 text-[10px] font-semibold uppercase tracking-widest items-center">
                    <a href="#areas" class="hover:text-amber-700 transition-colors">Áreas</a>
                    <a href="#jurisprudencia" class="hover:text-amber-700 transition-colors">Jurisprudencia</a>
                    <a href="#firma" class="hover:text-amber-700 transition-colors">La Firma</a>
                    <div class="h-4 w-[1px] bg-gray-300"></div>
                    <a href="tel:914263800" class="hover:text-amber-700 transition-colors">91 426 38 00</a>
                    <a href="mailto:estemerabogados@gmail.com" class="hover:text-amber-700 transition-colors lowercase font-normal italic">estemerabogados@gmail.com</a>
                    <a href="#contacto" class="bg-slate-900 text-white px-5 py-3 rounded-sm hover:bg-amber-700 transition-all border border-slate-700">Consulta</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Sección Hero -->
    <header class="h-screen flex items-center justify-center text-center hero-gradient text-white px-4">
        <div class="max-w-5xl">
            <h1 class="text-6xl md:text-8xl mb-6 tracking-tight uppercase">ESTEMER ABOGADOS</h1>
            <div class="w-32 h-1 bg-amber-600 mx-auto mb-8"></div>
            <p class="text-lg md:text-xl mb-12 font-light text-gray-200 uppercase tracking-[0.4em]">Velázquez 27: La puerta abierta al éxito jurídico</p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#firma" class="bg-amber-700 px-10 py-5 hover:bg-amber-800 transition duration-300 font-bold uppercase text-xs tracking-widest">Entrar en la Firma</a>
                <a href="#contacto" class="border-2 border-white px-10 py-5 hover:bg-white hover:text-black transition duration-300 font-bold uppercase text-xs tracking-widest">Solicitar Cita</a>
            </div>
        </div>
    </header>

    <!-- Áreas de Práctica -->
    <section id="areas" class="py-32 bg-white border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-20">
                <h2 class="text-4xl md:text-5xl mb-6 uppercase">Compromiso con el Éxito</h2>
                <p class="text-amber-700 uppercase tracking-[0.3em] text-xs font-bold">Especialización Jurídica Integral</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Derecho Fiscal -->
                <div class="p-10 border border-gray-100 bg-slate-50 card-hover flex flex-col h-full">
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-landmark-dome text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-slate-900">Derecho Fiscal</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-4 flex-grow text-pretty">Inspecciones de Hacienda, planificación fiscal de grandes patrimonios y resolución de expedientes complejos.</p>
                    <ul class="text-[10px] uppercase font-bold text-amber-700 tracking-widest space-y-2 border-t border-gray-200 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Inspección Tributaria</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Recursos y Reclamaciones</li>
                    </ul>
                </div>

                <!-- Derecho Mercantil y Bancario -->
                <div class="p-10 border border-gray-100 bg-slate-50 card-hover flex flex-col h-full">
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-file-signature text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-slate-900">Mercantil y Bancario</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-4 flex-grow text-pretty">Litigación bancaria especializada (IRPH, Euribor, Gastos) y contratos de servicios generales.</p>
                    <ul class="text-[10px] uppercase font-bold text-amber-700 tracking-widest space-y-2 border-t border-gray-200 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Reclamación IRPH / Gastos</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Contratos de Servicios</li>
                    </ul>
                </div>

                <!-- Derecho Civil e Inmobiliario -->
                <div class="p-10 border border-gray-100 bg-slate-50 card-hover flex flex-col h-full">
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-house-chimney text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-slate-900">Civil e Inmobiliario</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-4 flex-grow text-pretty">Especialistas en Herencias, Donaciones, Obra Nueva y reclamación de Vicios Ocultos.</p>
                    <ul class="text-[10px] uppercase font-bold text-amber-700 tracking-widest space-y-2 border-t border-gray-200 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Herencias y Donaciones</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Vicios Ocultos / Obra Nueva</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Arrendamientos y Deudas</li>
                    </ul>
                </div>

                <!-- Cooperativas y Social -->
                <div class="p-10 border border-gray-100 bg-slate-50 card-hover flex flex-col h-full">
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-users-gear text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-slate-900">Cooperativas</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-4 flex-grow text-pretty">Asesoramiento integral en el régimen jurídico de cooperativas y defensa de socios o entidad.</p>
                    <ul class="text-[10px] uppercase font-bold text-amber-700 tracking-widest space-y-2 border-t border-gray-200 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Gestión Estatutaria</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Conflictos Internos</li>
                    </ul>
                </div>

                <!-- Derecho Laboral -->
                <div class="p-10 border border-gray-100 bg-slate-50 card-hover flex flex-col h-full">
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-briefcase text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-slate-900">Derecho Laboral</h3>
                    <p class="text-gray-600 text-sm leading-relaxed mb-4 flex-grow text-pretty">Defensa de alta dirección y empresas en despidos, sanciones y reestructuraciones.</p>
                    <ul class="text-[10px] uppercase font-bold text-amber-700 tracking-widest space-y-2 border-t border-gray-200 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Despidos Alta Dirección</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Reclamaciones de Cantidad</li>
                    </ul>
                </div>

                <!-- Querellas y Penal Económico -->
                <div class="p-10 bg-slate-900 text-white card-hover border-b-4 border-amber-600 flex flex-col h-full">
                    <div class="w-12 h-12 bg-amber-600 text-white flex items-center justify-center mb-6">
                        <i class="fa-solid fa-scale-balanced text-xl"></i>
                    </div>
                    <h3 class="text-2xl mb-4 uppercase tracking-tighter text-amber-500">Querellas Económicas</h3>
                    <p class="text-gray-300 text-sm leading-relaxed mb-4 flex-grow text-pretty">Defensa penal ante delitos societarios, estafas y alzamiento de bienes.</p>
                    <ul class="text-[10px] uppercase font-bold text-white tracking-widest space-y-2 border-t border-slate-700 pt-4">
                        <li><i class="fa-solid fa-check mr-2"></i> Delitos Societarios</li>
                        <li><i class="fa-solid fa-check mr-2"></i> Defensa Penal Senior</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Jurisprudencia -->
    <section id="jurisprudencia" class="py-32 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-left mb-16">
                <h2 class="text-4xl md:text-5xl mb-4 uppercase">Jurisprudencia</h2>
                <p class="text-amber-700 uppercase tracking-[0.3em] text-xs font-bold">Análisis Técnico ESTEMER</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <article class="juris-note bg-white p-8 shadow-sm">
                    <span class="text-[10px] text-amber-700 font-bold uppercase tracking-widest block mb-2">Vicios Ocultos</span>
                    <h3 class="text-2xl mb-4 leading-tight text-slate-900">Prescripción en Compraventa Inmobiliaria.</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Doctrina reciente sobre el cómputo de plazos y responsabilidad del vendedor.</p>
                    <a href="#" class="text-[10px] font-bold uppercase tracking-tighter text-slate-900">Leer más <i class="fa-solid fa-chevron-right ml-1"></i></a>
                </article>
                <article class="juris-note bg-white p-8 shadow-sm">
                    <span class="text-[10px] text-amber-700 font-bold uppercase tracking-widest block mb-2">Bancario</span>
                    <h3 class="text-2xl mb-4 leading-tight text-slate-900">Transparencia en el IRPH.</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Nuevos escenarios procesales tras las últimas sentencias europeas.</p>
                    <a href="#" class="text-[10px] font-bold uppercase tracking-tighter text-slate-900">Leer más <i class="fa-solid fa-chevron-right ml-1"></i></a>
                </article>
            </div>
        </div>
    </section>

    <!-- La Firma -->
    <section id="firma" class="py-32 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4 flex flex-col md:flex-row items-center gap-20">
            <div class="md:w-1/2">
                <img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&q=80&w=1200" alt="[Despacho jurídico Velázquez 27]" class="rounded-sm shadow-2xl w-full h-[500px] object-cover">
            </div>
            <div class="md:w-1/2">
                <h2 class="text-4xl md:text-5xl mb-8 leading-tight text-slate-900 uppercase">Tradición Jurídica</h2>
                <p class="text-gray-700 mb-8 leading-relaxed text-lg italic">"En Velázquez 27, la abogacía se ejerce sobre madera noble."</p>
                <p class="text-gray-700 mb-8 leading-relaxed text-lg">Nuestro despacho, presidido por una mesa maciza de los años 60, simboliza la solidez de la experiencia y la agudeza del análisis contemporáneo.</p>
                <div class="space-y-4">
                    <div class="flex items-center space-x-4">
                        <i class="fa-solid fa-location-dot text-amber-700 w-6"></i>
                        <span class="text-xl font-bold text-slate-900 tracking-tighter">Velázquez 27, 1º Ext.</span>
                    </div>
                    <div class="flex items-center space-x-4">
                        <i class="fa-solid fa-phone text-amber-700 w-6"></i>
                        <span class="text-xl font-bold text-slate-900 tracking-tighter">91 426 38 00</span>
                    </div>
                    <div class="flex items-center space-x-4">
                        <i class="fa-solid fa-mobile-screen-button text-amber-700 w-6"></i>
                        <span class="text-xl font-bold text-slate-900 tracking-tighter">619 276 925</span>
                    </div>
                    <div class="flex items-center space-x-4">
                        <i class="fa-solid fa-envelope text-amber-700 w-6"></i>
                        <span class="text-xl text-slate-900 lowercase italic">estemerabogados@gmail.com</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="py-32 bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl mb-4 text-slate-900 uppercase tracking-tight">Solicitar Consulta Senior</h2>
                <p class="text-amber-700 uppercase tracking-[0.2em] text-[10px] font-bold">Velázquez 27, 1º Ext. | 28001 Madrid</p>
            </div>
            
            <div class="bg-slate-50 border border-gray-100 shadow-2xl p-8 md:p-12">
                <form onsubmit="event.preventDefault(); alert('Solicitud enviada. Contactaremos con usted a la brevedad bajo secreto profesional.');" class="space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <input type="text" placeholder="Nombre completo" class="p-4 bg-white border border-gray-200 outline-none" required>
                        <input type="email" placeholder="Email de contacto" class="p-4 bg-white border border-gray-200 outline-none" required>
                    </div>
                    <select class="w-full p-4 bg-white border border-gray-200 outline-none">
                        <option>Inmobiliario (Vicios Ocultos, Cooperativas)</option>
                        <option>Fiscal e Inspecciones</option>
                        <option>Bancario (IRPH, Gastos, Euribor)</option>
                        <option>Civil (Herencias, Donaciones, Obra Nueva)</option>
                        <option>Laboral y Alta Dirección</option>
                        <option>Penal Económico</option>
                    </select>
                    <textarea rows="4" placeholder="Detalle su consulta confidencial..." class="w-full p-4 bg-white border border-gray-200 outline-none"></textarea>
                    <button type="submit" class="w-full bg-slate-900 text-white py-6 font-bold uppercase tracking-[0.3em] text-xs hover:bg-amber-700 transition-all shadow-lg">
                        Enviar Solicitud Confidencial
                    </button>
                </form>
                <div class="mt-10 pt-8 border-t border-gray-200 text-center text-xs text-gray-500 space-y-2">
                    <p class="font-bold text-slate-800">Urgencias y Citas Directas:</p>
                    <p>Fijo: <a href="tel:914263800" class="hover:text-amber-700 font-bold">91 426 38 00</a> | Móvil: <a href="tel:619276925" class="hover:text-amber-700 font-bold">619 276 925</a></p>
                    <p>Email: <a href="mailto:estemerabogados@gmail.com" class="hover:text-amber-700 underline italic">estemerabogados@gmail.com</a></p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-white py-20 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <span class="text-3xl font-bold tracking-[0.3em] block mb-2 uppercase text-white">ESTEMER</span>
            <span class="text-[10px] text-amber-600 font-bold tracking-[0.3em] uppercase mb-8 block text-pretty">Velázquez 27, 1º Ext. | 28001 Madrid</span>
            
            <div class="flex flex-col md:flex-row justify-center items-center gap-8 mb-12 text-sm font-medium text-gray-400">
                <a href="tel:914263800" class="hover:text-white transition-colors">
                    <i class="fa-solid fa-phone mr-2 text-amber-700"></i>91 426 38 00
                </a>
                <a href="tel:619276925" class="hover:text-white transition-colors">
                    <i class="fa-solid fa-mobile-button mr-2 text-amber-700"></i>619 276 925
                </a>
                <a href="mailto:estemerabogados@gmail.com" class="hover:text-white transition-colors lowercase italic underline">
                    <i class="fa-solid fa-envelope mr-2 text-amber-700"></i>estemerabogados@gmail.com
                </a>
            </div>

            <p class="text-[9px] text-gray-700 uppercase tracking-[0.4em] max-w-lg mx-auto leading-loose text-pretty">
                © 1960-2026 ESTEMER ABOGADOS | Abogacía de Solera y Rigor Jurisprudencial <br>
                Fiscal · Inmobiliario · Bancario · Civil · Laboral · Penal
            </p>
        </div>
    </footer>

</body>
</html>
