# victor.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayres Móvil | Movilidad Vecinal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #000; color: #fff; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.1); }
        .hero-gradient { background: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(0,0,0,1) 100%); }
    </style>
</head>
<body class="antialiased">

    <nav class="fixed w-full z-50 p-6 flex justify-between items-center mix-blend-difference">
        <div class="text-sm font-bold tracking-widest uppercase">Ayres Móvil</div>
        <div class="text-xs text-gray-400 uppercase tracking-widest">Río Gallegos, Sta Cruz</div>
    </nav>

    <section class="relative h-screen flex flex-col justify-end p-8 md:p-20 overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="auto.jpg" alt="Corsa Negro" class="w-full h-full object-cover opacity-60">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>

        <div class="relative z-10 max-w-5xl">
            <h1 class="text-6xl md:text-[120px] font-black leading-none tracking-tighter mb-8">
                MOVAMOS EL BARRIO.
            </h1>
            <div class="flex flex-col md:flex-row justify-between items-start md:items-end gap-8">
                <p class="text-xl md:text-2xl text-gray-400 max-w-md">
                    Servicio de transporte exclusivo para vecinos de Ayres Argentinos. Seguridad, discreción y tarifas fijas.
                </p>
                <a href="https://wa.me/549296640001" class="bg-white text-black px-10 py-5 rounded-full font-bold text-lg hover:scale-105 transition-transform">
                    Pedir Viaje
                </a>
            </div>
        </div>
    </section>

    <section class="py-32 px-8 md:px-20 border-t border-zinc-900">
        <p class="text-xs uppercase tracking-[0.3em] text-zinc-500 mb-12 italic">Nuestras Tarifas</p>
        <div class="grid md:grid-cols-3 gap-1">
            <div class="glass p-12 hover:bg-zinc-900 transition-colors">
                <span class="text-zinc-600 text-sm">01</span>
                <h3 class="text-3xl font-bold mt-4 mb-2">Barrial</h3>
                <p class="text-zinc-400 mb-6 italic">Dentro de Ayres Argentinos</p>
                <p class="text-4xl font-light tracking-tighter">$1.300</p>
            </div>
            <div class="glass p-12 hover:bg-zinc-900 transition-colors border-x-0 md:border-x">
                <span class="text-zinc-600 text-sm">02</span>
                <h3 class="text-3xl font-bold mt-4 mb-2">Programados</h3>
                <p class="text-zinc-400 mb-6 italic">Centro, Hospital o Madrugada</p>
                <p class="text-4xl font-light tracking-tighter">$2.500</p>
            </div>
            <div class="glass p-12 hover:bg-zinc-900 transition-colors">
                <span class="text-zinc-600 text-sm">03</span>
                <h3 class="text-3xl font-bold mt-4 mb-2">Escolar</h3>
                <p class="text-zinc-400 mb-6 italic">Llegadas puntuales todos los días</p>
                <p class="text-4xl font-light tracking-tighter">Abonos</p>
            </div>
        </div>
    </section>

    <section class="py-32 px-8 md:px-20 bg-zinc-950">
        <div class="max-w-4xl">
            <h2 class="text-4xl md:text-6xl font-bold leading-tight mb-12">
                Conducido por vecinos,<br> para vecinos.
            </h2>
            <div class="grid md:grid-cols-2 gap-12 text-zinc-500 text-lg">
                <p>Operamos con un Chevrolet Corsa negro modelo 2006. Contamos con VTV al día, Seguro contra terceros y Licencia C1, garantizando un traslado bajo todas las normas de seguridad.</p>
                <p>Entendemos la necesidad del barrio. Por eso somos Pet Friendly 🐾 y ofrecemos horarios estratégicos para que nadie se quede a pie en las zonas sin cobertura.</p>
            </div>
        </div>
    </section>

    <footer class="p-8 border-t border-zinc-900 text-[10px] uppercase tracking-widest text-zinc-700 flex justify-between">
        <span>Ayres Móvil © 2026</span>
        <span>Diseñado por Víctor Álvarez</span>
    </footer>

</body>
</html>
