<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Propuesta de Marketing Digital | Bolso Mobile Detailing</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap" rel="stylesheet">
    <!-- 
    Plan de la Infografía:
    1.  Narrativa: Guiar al cliente desde el potencial actual (Diagnóstico) hacia una solución completa (Servicios y Packs), demostrando valor y un proceso claro.
    2.  Estructura:
        -   Sección 1 (Hook): Título y Diagnóstico Inicial.
        -   Sección 2 (Objetivos): Metas claras del plan.
        -   Sección 3 (Servicios): Presentación detallada de servicios mensuales y puntuales (todo en texto, sin gráficos). Cada servicio está ahora en un bloque más separado.
        -   Sección 4 (Packs): Presentación de los paquetes y sus ahorros (en texto, sin gráficos). Se han añadido los packs faltantes y se ha eliminado la sección "Ahorros por Pack" con la lista de ahorros.
        -   Sección 5 (Proceso): Diagrama de flujo del método de trabajo, ahora con descripciones detalladas para cada paso.
        -   Sección 6 (Conclusión): Cierre y llamado a la acción.
    3.  Selección de Visualizaciones (Confirmación NO SVG / NO Mermaid JS):
        -   Diagnóstico/Objetivos: Tarjetas estilizadas con HTML/Tailwind y unicode.
        -   Servicios Mensuales: Lista HTML detallada con viñetas.
        -   Servicios Puntuales: Lista HTML detallada.
        -   Packs: Cards HTML con información de ahorro.
        -   Método de Trabajo: Diagrama de Flujo con HTML/Tailwind. Meta: Organizar. Justificación: Representa un proceso secuencial de forma clara sin usar SVG o Mermaid.
    4.  Paleta de Colores: Basada en el logo de Bolso Mobile Detailing.
        - Azul Principal: #2E4E8A
        - Rojo de Acento: #E53935
        - Azul Medio: #4A6DA1
        - Azul Claro (Fondo): #D9E3F2
        - Blanco: #FFFFFF
    5.  Confirmación: Ni Mermaid JS ni SVG han sido utilizados en este documento. No se usa Chart.js ni Plotly.js ya que no hay gráficas.
    -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .flowchart-step {
            position: relative;
            z-index: 1;
        }
        .flowchart-connector {
            position: absolute;
            top: 50%;
            left: 100%;
            width: 4rem; 
            height: 2px;
            background-color: #4A6DA1; /* Azul Medio */
            z-index: 0;
        }
        .flowchart-connector::after {
            content: '▶';
            position: absolute;
            right: -0.5rem;
            top: 50%;
            transform: translateY(-50%);
            color: #4A6DA1; /* Azul Medio */
        }
    </style>
</head>
<body class="bg-[#D9E3F2]"> <!-- Azul Claro (Fondo) -->

    <div class="container mx-auto p-4 sm:p-8">

        <header class="text-center my-12">
            <h1 class="text-2xl md:text-4xl font-black text-[#2E4E8A]">Propuesta de Servicios – Marketing Digital para Bolso Mobile Detailing</h1> <!-- Azul Principal -->
            <h2 class="text-lg md:text-2xl font-bold text-[#E53935]">Florencia Vera – Especialista en Marketing Digital</h2> <!-- Rojo de Acento -->
        </header>

        <main>
            <section id="diagnostico" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-8">🔍 Diagnóstico Inicial</h3> <!-- Azul Principal -->
                <p class="text-center text-lg text-[#4A6DA1] mb-8">Luego de revisar tu punto de vista y canales digitales, identifico un negocio sólido con excelente potencial de crecimiento y diferenciación. Destaco:</p> <!-- Azul Medio -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="bg-white rounded-xl shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <p class="text-5xl mb-3">📱</p>
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Servicio 100% Móvil</h4> <!-- Azul Principal -->
                        <p class="text-[#4A6DA1]">Máxima comodidad y un gran diferenciador para el cliente final.</p> <!-- Azul Medio -->
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <p class="text-5xl mb-3">🏆</p>
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Poca Competencia</h4> <!-- Azul Principal -->
                        <p class="text-[#4A6DA1]">Oportunidad única para posicionarse como líder indiscutible en la zona.</p> <!-- Azul Medio -->
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <p class="text-5xl mb-3">💡</p>
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Canales Activos</h4> <!-- Azul Principal -->
                        <p class="text-[#4A6DA1]">Una base sólida con claras oportunidades de mejora en estrategia y estética.</p> <!-- Azul Medio -->
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <p class="text-5xl mb-3">📈</p>
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Operativa Funcional</h4> <!-- Azul Principal -->
                        <p class="text-[#4A6DA1]">Permite usar testimonios y resultados reales para generar confianza.</p> <!-- Azul Medio -->
                    </div>
                </div>
            </section>

            <section id="objetivos" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-8">🎯 Objetivos de la Propuesta</h3> <!-- Azul Principal -->
                <div class="max-w-4xl mx-auto bg-white/80 backdrop-blur-sm rounded-xl shadow-lg p-8">
                    <ul class="space-y-4">
                        <li class="flex items-start"><span class="text-2xl text-[#E53935] mr-3">✓</span><span class="text-[#2E4E8A]"><strong class="font-semibold">Profesionalizar la Identidad Digital:</strong> para reflejar la calidad y confiabilidad del servicio.</span></li> <!-- Rojo de Acento, Azul Principal -->
                        <li class="flex items-start"><span class="text-2xl text-[#E53935] mr-3">✓</span><span class="text-[#2E4E8A]"><strong class="font-semibold">Generar Más Conversiones:</strong> Aumentar reservas y consultas desde redes sociales.</span></li> <!-- Rojo de Acento, Azul Principal -->
                        <li class="flex items-start"><span class="text-2xl text-[#E53935] mr-3">✓</span><span class="text-[#2E4E8A]"><strong class="font-semibold">Automatizar y Simplificar:</strong> Liberarte tiempo para que te concentres en operar.</span></li> <!-- Rojo de Acento, Azul Principal -->
                        <li class="flex items-start"><span class="text-2xl text-[#E53935] mr-3">✓</span><span class="text-[#2E4E8A]"><strong class="font-semibold">Diversificar Contenido:</strong> Mostrar la propuesta de valor completa, más allá del "antes y después".</span></li> <!-- Rojo de Acento, Azul Principal -->
                        <li class="flex items-start"><span class="text-2xl text-[#E53935] mr-3">✓</span><span class="text-[#2E4E8A]"><strong class="font-semibold">Mejorar la Web:</strong> Proyectar una imagen de empresa moderna, establecida y confiable.</span></li> <!-- Rojo de Acento, Azul Principal -->
                    </ul>
                </div>
            </section>

            <section id="servicios" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-2">🧰 Servicios que puedo ofrecerte</h3> <!-- Azul Principal -->
                <p class="text-center text-lg text-[#4A6DA1] mb-8">Soluciones mensuales y puntuales para construir tu presencia digital.</p> <!-- Azul Medio -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <div class="bg-white rounded-xl shadow-lg p-6">
                        <h4 class="text-xl font-bold text-[#2E4E8A] mb-4 text-center">Servicios Mensuales</h4> <!-- Azul Principal -->
                        <div class="space-y-8 mt-6"> <!-- Increased space-y to separate service blocks -->
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">➡ Meta (Instagram y Facebook)</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 150 / mes</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Una solución integral para mantener tus redes activas, alineadas con tu identidad visual y orientadas a resultados. Este servicio combina estrategia, creatividad y ejecución para que no tengas que preocuparte por nada más que validar los contenidos mensuales.</p> <!-- Azul Medio -->
                                <p class="text-sm text-[#4A6DA1] mt-2">Se trabajarán diferentes tipos de contenido: antes/después, promociones, consejos, tips, testimonios, beneficios del servicio, presentación de equipo, servicios diferenciadores, y cómo solicitar el servicio (formas de contacto, pasos, métodos de pago, etc.), entre otros.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Optimización inicial gratuita de perfiles: imagen de perfil, biografía, enlaces, botón de contacto, linktree.</li>
                                    <li>8 contenidos mensuales.</li>
                                    <li>Creación del cronograma mensual de contenidos.</li>
                                    <li>Desarrollo de ideas, referencias visuales y temáticas.</li>
                                    <li>Diseño gráfico de los contenidos.</li>
                                    <li>Redacción de copys y hashtags alineados a la identidad.</li>
                                    <li>Programación automatizada del contenido.</li>
                                    <li>Seguimiento mensual de resultados (alcance, interacciones, clics, reservas, etc.).</li>
                                    <li>Ajustes estratégicos en base a rendimiento.</li>
                                    <li>Informe de evolución y mejoras sugeridas.</li>
                                </ul>
                            </div>
                            
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">➡ TikTok</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 100 / mes</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Una propuesta enfocada en videos breves, dinámicos y con estética actual, pensados exclusivamente para conectar con el público de TikTok sin perder coherencia con tu identidad de marca.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Optimización inicial gratuita de perfil: imagen de perfil, biografía, enlaces, botón de contacto, linktree.</li>
                                    <li>Hasta 4 videos mensuales, basados en material audiovisual que envíes.</li>
                                    <li>Pensados desde cero para TikTok (no adaptaciones).</li>
                                    <li>Edición dinámica con referencias visuales y tendencias adaptadas al rubro.</li>
                                    <li>Línea estética coherente con la identidad general de tu marca.</li>
                                </ul>
                            </div>

                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">🔹 Asesoramiento</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">GRATUITO</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Incluye asesoramiento específico sobre el contenido que vos enviás: sugerencias para mejorar las fotos (ángulos, luz, encuadre), recomendaciones sobre qué mostrar o resaltar según tus servicios, y propuesta de promociones o ideas mensuales para aprovechar momentos clave. El objetivo es potenciar el material con el que contamos para que el contenido sea atractivo, profesional y alineado a tus objetivos comerciales.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Sugerencias detalladas para mejorar tus fotos y videos (ángulos, luz, encuadre).</li>
                                    <li>Recomendaciones sobre qué mostrar o resaltar según tus servicios.</li>
                                    <li>Propuesta de promociones o ideas mensuales para aprovechar momentos clave.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6">
                        <h4 class="text-xl font-bold text-[#2E4E8A] mb-4 text-center">Servicios Puntuales (Una Vez)</h4> <!-- Azul Principal -->
                        <p class="text-center text-[#4A6DA1] mb-4">Estos servicios de pago único establecen una base sólida y profesional para tu marca.</p> <!-- Azul Medio -->
                        <div class="space-y-8 mt-6"> <!-- Increased space-y for punctual services too -->
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">🔹 Rebranding (Identidad Visual)</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 190</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Rediseño profesional de tu marca visual para reflejar mejor quién sos y cómo querés que te vean. Ideal para renovar o reforzar tu presencia digital y física.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Rediseño de logo, paleta de colores, tipografía y estilo gráfico.</li>
                                    <li>Entrega de archivos listos para formatos digitales (redes, web, etc.) y piezas físicas (indumentaria, vinilos, etc.).</li>
                                    <li>Manual de marca con lineamientos de uso.</li>
                                </ul>
                            </div>
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">🔹 Rediseño Web Básico</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 240</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Una web clara, moderna y funcional que transmita seriedad y profesionalismo para reforzar la confianza en tu marca y mejorar la conversión de visitantes en clientes.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Sitio responsive, optimizado para móvil, algo fundamental considerando que la mayoría de tus potenciales clientes interactúan con tu negocio desde el celular.</li>
                                    <li>Reestructuración de secciones clave (servicios, contacto, testimonios), para explicar mejor los servicios y facilitar la contratación.</li>
                                    <li>Carga de imágenes y contenido.</li>
                                    <li>Inclusión de redes sociales y llamados a la acción.</li>
                                </ul>
                            </div>
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">🔹 Automatización para Solicitudes y Consultas</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 120</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Automatizaciones para facilitar la toma de reservas o pedidos. Se configura un sistema ágil y profesional para que los clientes puedan contactarte sin complicaciones desde cualquier canal.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Creación de enlaces con mensajes predefinidos que simplifican el contacto.</li>
                                    <li>Botones de acceso directo desde redes y sitio web.</li>
                                    <li>Respuestas automáticas con WhatsApp Business para una atención más rápida.</li>
                                    <li>Opción de catálogo de servicios dentro de WhatsApp.</li>
                                    <li>Posibilidad de integrar un formulario externo simple (tipo Google Form o Typeform) que, una vez completado, envíe automáticamente los datos al negocio para registrar la reserva o consulta.</li>
                                </ul>
                            </div>
                            <div class="border-b pb-8 border-gray-200 last:border-b-0"> <!-- Added border for separation -->
                                <div class="flex flex-col sm:flex-row sm:justify-between sm:items-baseline">
                                    <h5 class="font-bold text-[#2E4E8A]">🔹 Alta y Configuración de Ficha en Google (Google Business Profile)</h5> <!-- Azul Principal -->
                                    <p class="text-left sm:text-right text-lg font-semibold text-[#2E4E8A] sm:ml-4">USD 60</p> <!-- Azul Principal -->
                                </div>
                                <p class="text-sm text-[#4A6DA1] mt-2">Una ficha profesional en Google mejora tu visibilidad local, permite que más personas encuentren tu servicio al buscar "lavado de autos" en tu zona, y transmite mayor confianza al cliente.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Creación y configuración de la ficha comercial en Google.</li>
                                    <li>Carga inicial de datos clave: nombre, contacto, horarios, zonas de cobertura, enlaces a redes y web.</li>
                                    <li>Optimización SEO básica (palabras clave y categorías).</li>
                                    <li>Carga inicial de fotos, descripción del servicio y métodos de contacto.</li>
                                    <li>Revisión y ajustes si ya tenés una ficha creada, para mejorarla y aprovecharla al máximo.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="packs" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-2">🚀 Descuentos por Packs: Tu Mejor Inversión</h3> <!-- Azul Principal -->
                 <p class="text-center text-lg text-[#4A6DA1] mb-8">Combina servicios y maximiza tu ahorro. Los packs están diseñados para ofrecerte una solución integral a un precio preferencial.</p> <!-- Azul Medio -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mb-12">
                    <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col">
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Pack Redes Sociales</h4> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] flex-grow">Gestión de contenido para Instagram (8 piezas) + TikTok (4 piezas) + Asesoramiento.</p> <!-- Azul Medio -->
                        <p class="text-3xl font-black text-[#2E4E8A] my-3">USD 230 <span class="text-lg font-semibold">/ mes</span></p> <!-- Azul Principal -->
                        <p class="text-green-600 font-bold bg-green-100 rounded-full px-3 py-1 self-start">Ahorro: USD 20 / mes</p>
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col">
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Pack Imagen Profesional</h4> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] flex-grow">Rebranding + Rediseño Web.</p> <!-- Azul Medio -->
                        <p class="text-3xl font-black text-[#2E4E8A] my-3">USD 360 <span class="text-lg font-semibold">/ único</span></p> <!-- Azul Principal -->
                        <p class="text-green-600 font-bold bg-green-100 rounded-full px-3 py-1 self-start">Ahorro: USD 70</p>
                    </div>
                     <div class="bg-gradient-to-br from-[#2E4E8A] to-[#4A6DA1] rounded-xl shadow-2xl p-6 flex flex-col text-white ring-4 ring-[#E53935]"> <!-- Azul Principal, Azul Medio, Rojo de Acento -->
                        <h4 class="font-bold text-lg text-[#D9E3F2]">🔝 Pack Presencia Digital Full</h4> <!-- Azul Claro -->
                        <p class="text-sm text-white/90 flex-grow">Redes (Meta+TikTok) + Google Business + Automatización + Rebranding + Web.</p>
                        <p class="text-3xl font-black my-3">USD 220/mes + 550/único</p>
                        <p class="text-[#D9E3F2] font-bold bg-[#E53935]/50 rounded-full px-3 py-1 self-start">Ahorro: USD 30/mes + USD 60</p> <!-- Azul Claro, Rojo de Acento -->
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col">
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Pack Presencia Digital Avanzada</h4> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] flex-grow">Redes (Meta + TikTok) + Google Business + Automatización + Rebranding.</p> <!-- Azul Medio -->
                        <p class="text-3xl font-black text-[#2E4E8A] my-3">USD 220 <span class="text-lg font-semibold">/ mes</span> + 340 <span class="text-lg font-semibold">/ único</span></p> <!-- Azul Principal -->
                        <p class="text-green-600 font-bold bg-green-100 rounded-full px-3 py-1 self-start">Ahorro: USD 30 / mes + USD 30 / único</p>
                    </div>
                     <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col">
                        <h4 class="font-bold text-lg text-[#2E4E8A]">Pack Optimización Local</h4> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] flex-grow">Redes (Meta + TikTok) + Google Business + Automatización.</p> <!-- Azul Medio -->
                        <p class="text-3xl font-black text-[#2E4E8A] my-3">USD 220 <span class="text-lg font-semibold">/ mes</span> + 165 <span class="text-lg font-semibold">/ único</span></p> <!-- Azul Principal -->
                        <p class="text-green-600 font-bold bg-green-100 rounded-full px-3 py-1 self-start">Ahorro: USD 30 / mes + USD 15 / único</p>
                    </div>
                </div>
            </section>

            <section id="servicios-a-evaluar" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-2">🧩 Posibles servicios a evaluar (con descuento para clientes activos)</h3> <!-- Azul Principal -->
                <p class="text-center text-lg text-[#4A6DA1] mb-8">Estos servicios se cotizan por separado, pero tienen precio preferencial si ya estás trabajando alguno de los servicios mensuales o packs.</p> <!-- Azul Medio -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <div class="bg-white rounded-xl shadow-lg p-6">
                        <div class="space-y-8 mt-6">
                            <div class="border-b pb-8 border-gray-200 last:border-b-0">
                                <h5 class="font-bold text-[#2E4E8A]">🔹 Publicidad en redes sociales (Meta Ads / Google Ads)</h5> <!-- Azul Principal -->
                                <p class="text-sm text-[#4A6DA1] mt-2">Campañas estratégicas con segmentación por zona y perfil de cliente. Redacción de textos persuasivos, diseño de piezas publicitarias.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Campañas estratégicas con segmentación por zona y perfil de cliente.</li>
                                    <li>Redacción de textos persuasivos, diseño de piezas publicitarias.</li>
                                    <li>Configuración y optimización de anuncios.</li>
                                    <li>Recomendaciones de inversión mínima mensual y asesoría en lectura de resultados.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-xl shadow-lg p-6">
                        <div class="space-y-8 mt-6">
                            <div class="border-b pb-8 border-gray-200 last:border-b-0">
                                <h5 class="font-bold text-[#2E4E8A]">🔹 Diseño de materiales gráficos para impresión</h5> <!-- Azul Principal -->
                                <p class="text-sm text-[#4A6DA1] mt-2">Tarjetas de presentación. Stickers para vehículos o clientes. Flyers o folletos promocionales.</p> <!-- Azul Medio -->
                                <p class="font-bold text-[#2E4E8A] mt-3">¿Qué incluye?</p> <!-- Azul Principal -->
                                <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1">
                                    <li>Tarjetas de presentación.</li>
                                    <li>Stickers para vehículos o clientes.</li>
                                    <li>Flyers o folletos promocionales.</li>
                                    <li>Todo alineado al branding diseñado previamente.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="proceso" class="mb-16">
                <h3 class="text-3xl font-bold text-[#2E4E8A] text-center mb-2">🤝 ¿Cómo trabajamos?</h3> <!-- Azul Principal -->
                <p class="text-center text-lg text-[#4A6DA1] mb-12">Un proceso transparente, flexible y colaborativo en 5 simples pasos.</p> <!-- Azul Medio -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-5 gap-6">
                    <div class="flowchart-step text-center bg-white rounded-xl shadow-lg p-4">
                        <div class="mx-auto bg-[#2E4E8A] text-white rounded-full w-16 h-16 flex items-center justify-center text-2xl font-bold mb-2">1</div> <!-- Azul Principal -->
                        <h5 class="font-bold text-[#2E4E8A] mb-2">Reunión Inicial / Brief</h5> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] text-left">Coordinamos una charla corta (puede ser por WhatsApp o videollamada) donde me contás tu visión, necesidades y dudas. También aprovecho para hacerte preguntas puntuales que me ayuden a personalizar el servicio.</p> <!-- Azul Medio -->
                    </div>
                    <div class="flowchart-step text-center bg-white rounded-xl shadow-lg p-4">
                        <div class="mx-auto bg-[#2E4E8A] text-white rounded-full w-16 h-16 flex items-center justify-center text-2xl font-bold mb-2">2</div> <!-- Azul Principal -->
                        <h5 class="font-bold text-[#2E4E8A] mb-2">Organización mensual</h5> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] text-left">Una vez iniciamos, trabajamos por bloques mensuales de planificación. Acordamos entregas, revisiones y validaciones de forma clara y calendarizada.</p> <!-- Azul Medio -->
                    </div>
                    <div class="flowchart-step text-center bg-white rounded-xl shadow-lg p-4">
                        <div class="mx-auto bg-[#2E4E8A] text-white rounded-full w-16 h-16 flex items-center justify-center text-2xl font-bold mb-2">3</div> <!-- Azul Principal -->
                        <h5 class="font-bold text-[#2E4E8A] mb-2">Validación simple</h5> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] text-left">Todo lo que produzco lo comparto para que lo revises, ajustes o valides. Solo necesitás estar disponible para dar el OK o indicar cambios menores.</p> <!-- Azul Medio -->
                    </div>
                    <div class="flowchart-step text-center bg-white rounded-xl shadow-lg p-4">
                        <div class="mx-auto bg-[#2E4E8A] text-white rounded-full w-16 h-16 flex items-center justify-center text-2xl font-bold mb-2">4</div> <!-- Azul Principal -->
                        <h5 class="font-bold text-[#2E4E8A] mb-2">Comunicación ágil</h5> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] text-left">Podés contactarme siempre por WhatsApp. Las entregas y contenidos se comparten en carpetas Drive organizadas por mes.</p> <!-- Azul Medio -->
                    </div>
                    <div class="flowchart-step text-center bg-white rounded-xl shadow-lg p-4">
                        <div class="mx-auto bg-[#2E4E8A] text-white rounded-full w-16 h-16 flex items-center justify-center text-2xl font-bold mb-2">5</div> <!-- Azul Principal -->
                        <h5 class="font-bold text-[#2E4E8A] mb-2">Flexibilidad y mejora continua</h5> <!-- Azul Principal -->
                        <p class="text-sm text-[#4A6DA1] text-left">Siempre estoy atenta al rendimiento, resultados o cambios del negocio, y propongo mejoras cuando sea necesario.</p> <!-- Azul Medio -->
                    </div>
                </div>
            </section>
             <section id="needs" class="text-center mb-16"> <!-- Separated section for needs -->
                <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg p-8">
                    <h4 class="text-xl font-semibold text-[#2E4E8A] mb-3">📩 ¿Qué necesito de vos?</h4> <!-- Azul Principal -->
                    <p class="text-sm text-[#4A6DA1]">Para que todo funcione de forma fluida y profesional, voy a necesitar:</p> <!-- Azul Medio -->
                    <ul class="list-disc list-inside text-[#4A6DA1] text-sm ml-4 space-y-1 mt-4 text-left">
                        <li>Accesos a redes sociales y sitio web (en caso de contratar esos servicios).</li>
                        <li>Logos, fotos actuales, paleta de colores (si ya tenés).</li>
                        <li>Testimonios, promociones o datos relevantes que quieras comunicar.</li>
                        <li>Videos o fotos de lavados si querés que los editemos para redes.</li>
                        <li>Validación de los contenidos que se entregan mensualmente.</li>
                    </ul>
                    <p class="text-sm text-[#4A6DA1] mt-4 text-left">Si no tenés algunos de estos elementos, ¡no hay problema! Te voy a guiar para generarlos o armarlos desde cero.</p> <!-- Azul Medio -->
                </div>
            </section>
            <section id="conclusion" class="text-center"> <!-- Separate section for conclusion -->
                <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg p-8">
                    <h3 class="text-2xl font-bold text-[#2E4E8A] mb-4">¡Gracias por considerar esta propuesta!</h3> <!-- Azul Principal -->
                    <p class="text-[#4A6DA1] mb-6">Quedo a tu disposición para responder cualquier duda, adaptar el plan a tus necesidades específicas o comenzar a trabajar juntos cuando lo desees. Será un gusto ayudarte a potenciar la presencia digital de Bolso Mobile Detailing.</p> <!-- Azul Medio -->
                </div>
            </section>
        </main>
        
        <footer class="text-center py-8 mt-8 text-[#4A6DA1]"> <!-- Azul Medio -->
            <p>&copy; 2025 Florencia Vera - Especialista en Marketing Digital</p>
        </footer>

    </div>
</body>
</html>
