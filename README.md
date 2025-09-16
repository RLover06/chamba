   <!-- Hero Section HMTL-->
 <!-- H===============================================================================================================================================================================L-->   

 </nav>

    <!-- Hero Section -->
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="text-center">
            <h1 class="text-4xl md:text-6xl font-bold text-secondary-900 mb-6">
                Conecta con <span class="text-primary-600">Proveedores</span><br>
                de Servicios Profesionales
            </h1>
            <p class="text-xl text-secondary-600 mb-8 max-w-3xl mx-auto">
                Encuentra el servicio perfecto para tus necesidades o ofrece tus habilidades 
                profesionales a clientes que las necesiten.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <button onclick="showRegister()" class="bg-primary-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-primary-700 w-full sm:w-auto">
                    Comenzar Ahora
                </button>
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
                ¿Por qué elegir nuestro marketplace?
            </h2>
            <p class="text-lg text-secondary-600">
                Ofrecemos una plataforma segura y fácil de usar para conectar clientes y proveedores
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center p-6">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Fácil de Encontrar</h3>
                <p class="text-secondary-600">
                    Busca servicios por categoría, ubicación y precio. Filtra resultados para encontrar exactamente lo que necesitas.
                </p>
            </div>

            <div class="text-center p-6">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Seguro y Confiable</h3>
                <p class="text-secondary-600">
                    Todos los proveedores son verificados y puedes comunicarte directamente con ellos antes de contratar.
                </p>
            </div>

            <div class="text-center p-6">
                <div class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4">
                    <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
                    </svg>
                </div>
                <h3 class="text-xl font-semibold text-secondary-900 mb-2">Comunicación Directa</h3>
                <p class="text-secondary-600">
                    Chatea directamente con los proveedores para discutir detalles del proyecto y hacer preguntas.
                </p>
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
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Desarrollo Web</h3>
                        <p class="text-sm text-secondary-600 mb-2">por Juan Pérez</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Tecnología</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">25€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Creo sitios web modernos y responsivos usando las últimas tecnologías.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Madrid, España
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Ver Detalles
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Contactar
                    </button>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-sm border border-secondary-200 p-6">
                <div class="flex items-start justify-between mb-4">
                    <div class="flex-1">
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Diseño Gráfico</h3>
                        <p class="text-sm text-secondary-600 mb-2">por María García</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Diseño</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">20€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Diseño logos, flyers, banners y material gráfico profesional.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Barcelona, España
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Ver Detalles
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Contactar
                    </button>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-sm border border-secondary-200 p-6">
                <div class="flex items-start justify-between mb-4">
                    <div class="flex-1">
                        <h3 class="text-lg font-semibold text-secondary-900 mb-2">Marketing Digital</h3>
                        <p class="text-sm text-secondary-600 mb-2">por Carlos López</p>
                        <span class="inline-block bg-primary-100 text-primary-800 text-xs px-2 py-1 rounded-full">Marketing</span>
                    </div>
                    <div class="text-right">
                        <p class="text-2xl font-bold text-primary-600">30€</p>
                        <p class="text-sm text-secondary-500">por hora</p>
                    </div>
                </div>
                <p class="text-secondary-700 mb-4">Estrategias de marketing digital para hacer crecer tu negocio online.</p>
                <div class="flex items-center justify-between text-sm text-secondary-500 mb-4">
                    <div class="flex items-center">
                        <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                        Valencia, España
                    </div>
                </div>
                <div class="flex space-x-2">
                    <button class="flex-1 bg-primary-600 text-white py-2 px-4 rounded-lg hover:bg-primary-700 transition-colors">
                        Ver Detalles
                    </button>
                    <button class="bg-secondary-100 text-secondary-700 py-2 px-4 rounded-lg hover:bg-secondary-200 transition-colors">
                        Contactar
                    </button>
                </div>
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
                    <span class="text-xl font-bold">Marketplace</span>
                </div>
                <p class="text-secondary-400">
                    © 2024 Marketplace. Todos los derechos reservados.
                    
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Funciones para mostrar/ocultar modales
        function showLogin() {
            document.getElementById('login-modal').classList.remove('hidden');
            document.getElementById('login-modal').classList.add('flex');
        }

        function hideLogin() {
            document.getElementById('login-modal').classList.add('hidden');
            document.getElementById('login-modal').classList.remove('flex');
        }

        function showRegister() {
            document.getElementById('register-modal').classList.remove('hidden');
            document.getElementById('register-modal').classList.add('flex');
        }

        function hideRegister() {
            document.getElementById('register-modal').classList.add('hidden');
            document.getElementById('register-modal').classList.remove('flex');
        }

        function showServices() {
            document.getElementById('services-section').style.display = 'block';
            document.getElementById('services-section').scrollIntoView({ behavior: 'smooth' });
        }

        // Funciones para manejar formularios
        function handleLogin(event) {
            event.preventDefault();
            alert('¡Inicio de sesión exitoso! (Demo)');
            hideLogin();
        }

        function handleRegister(event) {
            event.preventDefault();
            alert('¡Registro exitoso! (Demo)');
            hideRegister();
        }

        // Cerrar modales al hacer clic fuera
        document.addEventListener('click', function(event) {
            if (event.target.classList.contains('bg-black')) {
                hideLogin();
                hideRegister();
            }
        });
    </script>
</body>

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

