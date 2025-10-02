[Untitled-1.html](https://github.com/user-attachments/files/22652341/Untitled-1.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NextStep English</title>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
<script>
function toggleLanguage() {
const esContent = document.getElementById('es');
const enContent = document.getElementById('en');
if (esContent.style.display === 'none') {
esContent.style.display = 'block';
enContent.style.display = 'none';
} else {
esContent.style.display = 'none';
enContent.style.display = 'block';
}
}
</script>
</head>
<body class="font-sans bg-gray-50 text-gray-800">
<!-- Language Toggle -->
<div class="text-right p-4">
<button onclick="toggleLanguage()" class="bg-blue-600 text-white px-4 py-2 rounded">ES / EN</button>
</div>


<!-- Spanish Content -->
<div id="es">
<!-- Hero Section -->
<section class="bg-blue-600 text-white text-center py-20">
<h1 class="text-4xl md:text-5xl font-bold">NextStep English</h1>
<p class="mt-4 text-xl">Lleva tu inglés — y tu futuro — al siguiente nivel.</p>
<a href="#contacto" class="mt-6 inline-block bg-white text-blue-600 font-semibold px-6 py-3 rounded-lg shadow hover:bg-gray-100">Reserva tu primera clase hoy</a>
</section>


<!-- Why Choose Us -->
<section class="py-16 px-6 md:px-16 text-center">
<h2 class="text-3xl font-bold mb-8">¿Por qué elegir NextStep English?</h2>
<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
<div class="p-6 bg-white shadow rounded-xl">✅ Apoyo bilingüe (inglés + español)</div>
<div class="p-6 bg-white shadow rounded-xl">✅ Horarios flexibles — noches y fines de semana</div>
<div class="p-6 bg-white shadow rounded-xl">✅ Clases privadas y grupales a precios accesibles</div>
<div class="p-6 bg-white shadow rounded-xl">✅ Aprende en aulas, bibliotecas o en línea</div>
</div>
</section>


<!-- Pricing -->
<section class="bg-gray-100 py-16 px-6 md:px-16">
<h2 class="text-3xl font-bold text-center mb-8">Precios</h2>
<div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
<div class="bg-white p-6 rounded-xl shadow">
<h3 class="text-xl font-bold mb-4">Clases Privadas</h3>
<ul class="space-y-2">
<li>• Inglés conversacional – $30/hr</li>
<li>• Inglés estructurado – $40/hr</li>
<li>• Inglés profesional/negocios – $50/hr</li>
</ul>
</div>
<div class="bg-white p-6 rounded-xl shadow">
<h3 class="text-xl font-bold mb-4">Clases Grupales</h3>
<ul class="space-y-2">
<li>• Conversacional – $25/estudiante/hr</li>
<li>• Estructurado – $30/estudiante/hr</li>
</ul>
</div>
