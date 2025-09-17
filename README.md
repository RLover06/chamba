   <!-- Hero Section HMTL-->
 <!-- H===============================================================================================================================================================================L-->   

 <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MI CHAMBA - Marketplace de Servicios Profesionales</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            200: '#bfdbfe',
                            300: '#93c5fd',
                            400: '#60a5fa',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            800: '#1e40af',
                            900: '#1e3a8a',
                        },
                        secondary: {
                            50: '#f8fafc',
                            100: '#f1f5f9',
                            200: '#e2e8f0',
                            300: '#cbd5e1',
                            400: '#94a3b8',
                            500: '#64748b',
                            600: '#475569',
                            700: '#334155',
                            800: '#1e293b',
                            900: '#0f172a',
                        },
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gradient-to-br from-primary-50 to-secondary-50 min-h-screen">
    <!-- Navbar -->
    <nav class="bg-white shadow-sm border-b">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex items-center space-x-2">
                        <div class="w-8 h-8 bg-primary-600 rounded-lg flex items-center justify-center">
                            <span class="text-white font-bold text-lg">M</span>
                        </div>
                        <span class="text-xl font-bold text-secondary-900">MI CHAMBA</span>
                    </div>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="/auth/login" class="text-secondary-600 hover:text-secondary-900 px-3 py-2 rounded-md text-sm font-medium">
                        Iniciar Sesión
                    </a>
                    <a href="/auth/register" class="bg-primary-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-primary-700">
                        Registrarse
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="text-center">
            <h1 class="text-4xl md:text-6xl font-bold text-secondary-900 mb-6">
                Encuentra tu <span class="text-primary-600">Próxima Chamba</span><br>
                o Ofrece tus Servicios Profesionales
            </h1>
            <p class="text-xl text-secondary-600 mb-8 max-w-3xl mx-auto">
                Conecta con profesionales talentosos o encuentra clientes para tus servicios. 
                Una plataforma segura y fácil de usar para freelancers y empresas.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="/auth/register" class="bg-primary-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-700 w-full sm:w-auto text-center">
                    Comenzar Ahora
                </a>
                <button onclick="showServices()" class="border border-primary-600 text-primary-600 px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-50 w-full sm:w-auto">
                    Ver Servicios
                </button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
        <div class="text-center mb-16">
            <h2 class="text-3xl font-bold text-secondary-900 mb-4">
                ¿Por qué elegir MI CHAMBA?
            </h2>
            <p class="text-lg text-secondary-600">
                La plataforma líder para conectar freelancers con empresas. Segura, confiable y diseñada para el éxito profesional.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <!-- Geolocalización -->
            <div class="text-center p-6 bg-white rounded-lg shadow-sm border border-secondary-200">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Servicios Cercanos</h3>
                <p class="text-secondary-600">
                    Encuentra profesionales cerca de ti con nuestra tecnología de geolocalización. Filtra por distancia y encuentra servicios locales.
                </p>
            </div>

            <!-- Sistema de Reservas -->
            <div class="text-center p-6 bg-white rounded-lg shadow-sm border border-secondary-200">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Sistema de Reservas</h3>
                <p class="text-secondary-600">
                    Agenda citas fácilmente con nuestro sistema de reservas integrado. Gestiona tu calendario y coordina servicios sin complicaciones.
                </p>
            </div>

            <!-- Reseñas y Calificaciones -->
            <div class="text-center p-6 bg-white rounded-lg shadow-sm border border-secondary-200">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Reseñas y Calificaciones</h3>
                <p class="text-secondary-600">
                    Sistema completo de calificaciones y reseñas. Lee experiencias reales y construye tu reputación profesional.
                </p>
            </div>

            <!-- Chat en Tiempo Real -->
            <div class="text-center p-6 bg-white rounded-lg shadow-sm border border-secondary-200">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Chat en Tiempo Real</h3>
                <p class="text-secondary-600">
                    Comunícate directamente con profesionales a través de nuestro sistema de mensajería integrado. Negocia términos y coordina proyectos fácilmente.
                </p>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-primary-600 text-white py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Números que Hablan</h2>
                <p class="text-primary-100">La plataforma líder en servicios profesionales</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
                <div>
                    <div class="text-4xl font-bold mb-2">500+</div>
                    <div class="text-primary-100">Profesionales Activos</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">1,200+</div>
                    <div class="text-primary-100">Reservas Completadas</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">850+</div>
                    <div class="text-primary-100">Reseñas Positivas</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">4.8★</div>
                    <div class="text-primary-100">Calificación Promedio</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services-section" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16" style="display: none;">
        <div class="mb-8">
            <h1 class="text-3xl font-bold text-secondary-900 mb-4">Servicios Disponibles</h1>
            <p class="text-secondary-600 mb-6">Encuentra el servicio perfecto para tus necesidades</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-white rounded-lg shadow-sm border border-secondary-200 p-6">
                <div class="flex items-start justify-between mb-4">
                    <div class="flex-1">
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Desarrollo Web Full Stack</h3>
                        <p class="text-sm text-secondary-600 mb-2">por Ana Rodríguez</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Tecnología</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">35€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Desarrollo de aplicaciones web completas con React, Node.js y bases de datos. Especialista en e-commerce y aplicaciones empresariales.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Barcelona, España
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                        <span>2.5 km</span>
                    </div>
                </div>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1 text-yellow-400" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z" />
                        </svg>
                        <span>4.8 (24 reseñas)</span>
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                        </svg>
                        <span>Disponible</span>
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Reservar Ahora
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Ver Detalles
                    </button>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-sm border border-secondary-200 p-6">
                <div class="flex items-start justify-between mb-4">
                    <div class="flex-1">
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Diseño UX/UI</h3>
                        <p class="text-sm text-secondary-600 mb-2">por Carlos Mendoza</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Diseño</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">28€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Diseño de interfaces de usuario intuitivas y experiencias digitales excepcionales. Especialista en Figma y prototipado.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Madrid, España
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                        <span>1.8 km</span>
                    </div>
                </div>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1 text-yellow-400" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z" />
                        </svg>
                        <span>4.9 (18 reseñas)</span>
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                        </svg>
                        <span>Disponible</span>
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Reservar Ahora
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Ver Detalles
                    </button>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-sm border border-secondary-200 p-6">
                <div class="flex items-start justify-between mb-4">
                    <div class="flex-1">
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Marketing Digital & SEO</h3>
                        <p class="text-sm text-secondary-600 mb-2">por Laura Fernández</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Marketing</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">32€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Estrategias completas de marketing digital, SEO, SEM y redes sociales. Aumenta tu visibilidad online y genera más leads.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Valencia, España
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                        <span>3.2 km</span>
                    </div>
                </div>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1 text-yellow-400" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z" />
                        </svg>
                        <span>4.7 (31 reseñas)</span>
                    </div>
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                        </svg>
                        <span>Disponible</span>
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Reservar Ahora
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Ver Detalles
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- New Features Section -->
    <section class="bg-gradient-to-r from-primary-50 to-secondary-50 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-secondary-900 mb-4">
                    🚀 Nuevas Funcionalidades
                </h2>
                <p class="text-lg text-secondary-600">
                    Descubre las últimas características que hacen de MI CHAMBA la plataforma más completa
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Geolocalización -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl transition-shadow">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-10 h-10 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-bold text-secondary-900 mb-2">Servicios Cercanos</h3>
                        <p class="text-secondary-600 mb-4">
                            Encuentra profesionales cerca de ti con nuestra tecnología de geolocalización avanzada
                        </p>
                    </div>
                    <ul class="space-y-3 text-sm text-secondary-600">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Búsqueda por proximidad geográfica
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Filtros por distancia (5km - 50km)
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Ubicación automática del usuario
                        </li>
                    </ul>
                    <div class="mt-6 text-center">
                        <button onclick="showGeolocationInfo()" class="bg-blue-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-blue-700 transition-colors">
                            Más Información
                        </button>
                    </div>
                </div>

                <!-- Sistema de Reservas -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl transition-shadow">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-10 h-10 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-bold text-secondary-900 mb-2">Sistema de Reservas</h3>
                        <p class="text-secondary-600 mb-4">
                            Agenda citas fácilmente con nuestro sistema de reservas integrado y gestión de calendario
                        </p>
                    </div>
                    <ul class="space-y-3 text-sm text-secondary-600">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Reservas con fecha y hora específicas
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Gestión de estados (Pendiente, Confirmada, etc.)
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Cálculo automático de precios
                        </li>
                    </ul>
                    <div class="mt-6 text-center">
                        <button onclick="showBookingInfo()" class="bg-green-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-green-700 transition-colors">
                            Más Información
                        </button>
                    </div>
                </div>

                <!-- Reseñas y Calificaciones -->
                <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl transition-shadow">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-yellow-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-10 h-10 text-yellow-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
                            </svg>
                        </div>
                        <h3 class="text-2xl font-bold text-secondary-900 mb-2">Reseñas y Calificaciones</h3>
                        <p class="text-secondary-600 mb-4">
                            Sistema completo de calificaciones y reseñas para construir confianza y reputación
                        </p>
                    </div>
                    <ul class="space-y-3 text-sm text-secondary-600">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Calificaciones de 1 a 5 estrellas
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Comentarios detallados
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            Estadísticas de calificaciones promedio
                        </li>
                    </ul>
                    <div class="mt-6 text-center">
                        <button onclick="showReviewsInfo()" class="bg-yellow-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-yellow-700 transition-colors">
                            Más Información
                        </button>
                    </div>
                </div>
            </div>

            <div class="text-center mt-12">
                <a href="/auth/register" class="bg-primary-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-700 transition-colors inline-block">
                    ¡Prueba las Nuevas Funcionalidades!
                </a>
            </div>
        </div>
    </section>

    <!-- Login Modal -->
    <div id="login-modal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="bg-white rounded-lg p-8 max-w-md w-full mx-4">
            <div class="text-center mb-6">
                <div class="mx-auto h-12 w-12 bg-primary-600 rounded-lg flex items-center justify-center mb-4">
                    <span class="text-white font-bold text-xl">M</span>
                </div>
                <h2 class="text-2xl font-bold text-secondary-900">Iniciar Sesión</h2>
            </div>
            <form onsubmit="handleLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Email</label>
                    <input type="email" required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500" placeholder="tu@email.com">
                </div>
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Contraseña</label>
                    <input type="password" required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500" placeholder="••••••••">
                </div>
                <button type="submit" class="w-full bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                    Iniciar Sesión
                </button>
            </form>
            <div class="text-center mt-4">
                <button onclick="hideLogin(); showRegister()" class="text-primary-600 hover:text-primary-500 text-sm">
                    ¿No tienes cuenta? Regístrate aquí
                </button>
            </div>
            <button onclick="hideLogin()" class="absolute top-4 right-4 text-secondary-400 hover:text-secondary-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
            </button>
        </div>
    </div>

    <!-- Register Modal -->
    <div id="register-modal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="bg-white rounded-lg p-8 max-w-md w-full mx-4">
            <div class="text-center mb-6">
                <div class="mx-auto h-12 w-12 bg-primary-600 rounded-lg flex items-center justify-center mb-4">
                    <span class="text-white font-bold text-xl">M</span>
                </div>
                <h2 class="text-2xl font-bold text-secondary-900">Crear Cuenta</h2>
            </div>
            <form onsubmit="handleRegister(event)" class="space-y-4">
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Nombre completo</label>
                    <input type="text" required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500" placeholder="Tu nombre completo">
                </div>
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Email</label>
                    <input type="email" required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500" placeholder="tu@email.com">
                </div>
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Contraseña</label>
                    <input type="password" required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500" placeholder="••••••••">
                </div>
                <div>
                    <label class="block text-sm font-medium text-secondary-700 mb-1">Tipo de usuario</label>
                    <select required class="w-full px-3 py-2 border border-secondary-300 rounded-lg focus:border-primary-500 focus:outline-none focus:ring-2 focus:ring-primary-500">
                        <option value="">Selecciona...</option>
                        <option value="CLIENT">Cliente</option>
                        <option value="PROVIDER">Proveedor</option>
                    </select>
                </div>
                <button type="submit" class="w-full bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                    Registrarse
                </button>
            </form>
            <div class="text-center mt-4">
                <button onclick="hideRegister(); showLogin()" class="text-primary-600 hover:text-primary-500 text-sm">
                    ¿Ya tienes cuenta? Inicia sesión aquí
                </button>
            </div>
            <button onclick="hideRegister()" class="absolute top-4 right-4 text-secondary-400 hover:text-secondary-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
            </button>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-secondary-900 text-white mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="text-center">
                <div class="flex items-center justify-center space-x-2 mb-4">
                    <div class="w-8 h-8 bg-primary-600 rounded-lg flex items-center justify-center">
                        <span class="text-white font-bold text-lg">M</span>
                    </div>
                    <span class="text-xl font-bold">MI CHAMBA</span>
                </div>
                <p class="text-secondary-400">
                    © 2024 MI CHAMBA. Conectando talento con oportunidades. Todos los derechos reservados.
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Verificar si el usuario está autenticado
        function checkAuthStatus() {
            // Verificar si hay token de Supabase en localStorage
            const supabaseToken = localStorage.getItem('sb-' + window.location.hostname + '-auth-token');
            const isAuthenticated = supabaseToken && JSON.parse(supabaseToken).access_token;
            
            if (isAuthenticated) {
                // Usuario autenticado - mostrar opciones del dashboard
                updateNavForAuthenticatedUser();
            } else {
                // Usuario no autenticado - mantener botones de login/registro
                updateNavForGuestUser();
            }
        }

        function updateNavForAuthenticatedUser() {
            const navButtons = document.querySelector('.flex.items-center.space-x-4');
            if (navButtons) {
                navButtons.innerHTML = `
                    <div class="flex items-center space-x-2 mr-4">
                        <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                        <span class="text-sm text-green-600 font-medium">Conectado</span>
                    </div>
                    <a href="/dashboard" class="text-secondary-600 hover:text-secondary-900 px-3 py-2 rounded-md text-sm font-medium">
                        Dashboard
                    </a>
                    <a href="/dashboard/services" class="text-secondary-600 hover:text-secondary-900 px-3 py-2 rounded-md text-sm font-medium">
                        Mis Servicios
                    </a>
                    <button onclick="logout()" class="bg-red-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-red-700">
                        Cerrar Sesión
                    </button>
                `;
            }
            
            // Actualizar botones del hero para usuarios autenticados
            updateHeroForAuthenticatedUser();
        }

        function updateHeroForAuthenticatedUser() {
            // Actualizar título del hero
            const heroTitle = document.querySelector('h1');
            if (heroTitle) {
                heroTitle.innerHTML = `
                    ¡Bienvenido de vuelta a <span class="text-primary-600">MI CHAMBA</span>!<br>
                    Continúa gestionando tus servicios profesionales
                `;
            }
            
            // Actualizar descripción del hero
            const heroDescription = document.querySelector('.text-xl.text-secondary-600.mb-8.max-w-3xl.mx-auto');
            if (heroDescription) {
                heroDescription.textContent = 'Accede a tu dashboard para gestionar tus servicios, reservas y mensajes.';
            }
            
            // Actualizar botones del hero
            const heroButtons = document.querySelector('.flex.flex-col.sm\\:flex-row.gap-4.justify-center');
            if (heroButtons) {
                heroButtons.innerHTML = `
                    <a href="/dashboard" class="bg-primary-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-700 w-full sm:w-auto text-center">
                        Ir al Dashboard
                    </a>
                    <a href="/dashboard/services/create" class="border border-primary-600 text-primary-600 px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-50 w-full sm:w-auto text-center">
                        Crear Servicio
                    </a>
                `;
            }
        }

        function updateNavForGuestUser() {
            const navButtons = document.querySelector('.flex.items-center.space-x-4');
            if (navButtons) {
                navButtons.innerHTML = `
                    <a href="/auth/login" class="text-secondary-600 hover:text-secondary-900 px-3 py-2 rounded-md text-sm font-medium">
                        Iniciar Sesión
                    </a>
                    <a href="/auth/register" class="bg-primary-600 text-white px-4 py-2 rounded-lg text-sm font-medium hover:bg-primary-700">
                        Registrarse
                    </a>
                `;
            }
            
            // Restaurar botones del hero para usuarios no autenticados
            restoreHeroForGuestUser();
        }

        function restoreHeroForGuestUser() {
            // Restaurar título original del hero
            const heroTitle = document.querySelector('h1');
            if (heroTitle) {
                heroTitle.innerHTML = `
                    Encuentra tu <span class="text-primary-600">Próxima Chamba</span><br>
                    o Ofrece tus Servicios Profesionales
                `;
            }
            
            // Restaurar descripción original del hero
            const heroDescription = document.querySelector('.text-xl.text-secondary-600.mb-8.max-w-3xl.mx-auto');
            if (heroDescription) {
                heroDescription.textContent = 'Conecta con profesionales talentosos o encuentra clientes para tus servicios. Una plataforma segura y fácil de usar para freelancers y empresas.';
            }
            
            // Restaurar botones originales del hero
            const heroButtons = document.querySelector('.flex.flex-col.sm\\:flex-row.gap-4.justify-center');
            if (heroButtons) {
                heroButtons.innerHTML = `
                    <a href="/auth/register" class="bg-primary-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-700 w-full sm:w-auto text-center">
                        Comenzar Ahora
                    </a>
                    <button onclick="showServices()" class="border border-primary-600 text-primary-600 px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-50 w-full sm:w-auto">
                        Ver Servicios
                    </button>
                `;
            }
        }

        function logout() {
            // Limpiar token de Supabase
            localStorage.removeItem('sb-' + window.location.hostname + '-auth-token');
            // Redirigir a la página principal
            window.location.href = '/';
        }

        // Funciones para mostrar/ocultar modales (mantener para compatibilidad)
        function showLogin() {
            window.location.href = '/auth/login';
        }

        function hideLogin() {
            // Ya no se usa
        }

        function showRegister() {
            window.location.href = '/auth/register';
        }

        function hideRegister() {
            // Ya no se usa
        }

        function showServices() {
            document.getElementById('services-section').style.display = 'block';
            document.getElementById('services-section').scrollIntoView({ behavior: 'smooth' });
        }

        // Funciones para manejar formularios
        function handleLogin(event) {
            event.preventDefault();
            alert('¡Inicio de sesión exitoso! (Demo)\n\nAhora puedes acceder a:\n• Servicios cercanos con geolocalización\n• Sistema de reservas\n• Reseñas y calificaciones');
            hideLogin();
        }

        function handleRegister(event) {
            event.preventDefault();
            alert('¡Registro exitoso! (Demo)\n\n¡Bienvenido a MI CHAMBA!\n\nNuevas funcionalidades disponibles:\n• Geolocalización de servicios\n• Sistema de reservas\n• Reseñas y calificaciones');
            hideRegister();
        }

        // Función para mostrar información sobre geolocalización
        function showGeolocationInfo() {
            alert('🌍 Geolocalización\n\n• Encuentra servicios cerca de ti\n• Filtra por distancia (5km - 50km)\n• Ubicación automática del usuario\n• Búsqueda por dirección específica');
        }

        // Función para mostrar información sobre reservas
        function showBookingInfo() {
            alert('📅 Sistema de Reservas\n\n• Agenda citas fácilmente\n• Gestión de estados\n• Cálculo automático de precios\n• Notas adicionales\n• Confirmación por parte del proveedor');
        }

        // Función para mostrar información sobre reseñas
        function showReviewsInfo() {
            alert('⭐ Reseñas y Calificaciones\n\n• Calificaciones de 1 a 5 estrellas\n• Comentarios detallados\n• Estadísticas de calificaciones\n• Una reseña por servicio\n• Solo usuarios que completaron reservas');
        }

        // Cerrar modales al hacer clic fuera
        document.addEventListener('click', function(event) {
            if (event.target.classList.contains('bg-black')) {
                hideLogin();
                hideRegister();
            }
        });

        // Verificar estado de autenticación al cargar la página
        document.addEventListener('DOMContentLoaded', function() {
            checkAuthStatus();
        });

        // Escuchar cambios en el localStorage para actualizar la navegación
        window.addEventListener('storage', function(e) {
            if (e.key && e.key.includes('auth-token')) {
                checkAuthStatus();
            }
        });
    </script>
</body>
</html>


   <!-- Hero Section JS AUTH-->
 <!-- H===============================================================================================================================================================================L-->   

import { NextAuthOptions } from 'next-auth'
import CredentialsProvider from 'next-auth/providers/credentials'
import { PrismaAdapter } from '@next-auth/prisma-adapter'
import { prisma } from './prisma'
import bcrypt from 'bcryptjs'
import { UserRole } from '@prisma/client'

export const authOptions: NextAuthOptions = {
  adapter: PrismaAdapter(prisma),
  providers: [
    CredentialsProvider({
      name: 'credentials',
      credentials: {
        email: { label: 'Email', type: 'email' },
        password: { label: 'Password', type: 'password' }
      },
      async authorize(credentials) {
        if (!credentials?.email || !credentials?.password) {
          return null
        }

        const user = await prisma.user.findUnique({
          where: {
            email: credentials.email
          }
        })

        if (!user || !user.password) {
          return null
        }

        const isPasswordValid = await bcrypt.compare(
          credentials.password,
          user.password
        )

        if (!isPasswordValid) {
          return null
        }

        return {
          id: user.id,
          email: user.email,
          name: user.name,
          image: user.image,
          role: user.role,
        }
      }
    })
  ],
  session: {
    strategy: 'jwt',
  },
  callbacks: {
    async jwt({ token, user }) {
      if (user) {
        token.role = user.role
      }
      return token
    },
    async session({ session, token }) {
      if (token) {
        session.user.id = token.sub!
        session.user.role = token.role as UserRole
      }
      return session
    },
  },
  pages: {
    signIn: '/auth/login',
    signUp: '/auth/register',
  },
}



</html>

