<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel de Acesso</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Usando a fonte Inter para um visual mais limpo e moderno */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-900 text-white flex items-center justify-center min-h-screen p-4">

    <div class="w-full max-w-md bg-gray-800 rounded-2xl shadow-lg p-8 space-y-6">
        
        <header class="text-center">
            <img src="https://pm.ssp.ma.gov.br/wp-content/uploads/2023/05/BRASAO-SD-RAYOL-e1683655730963.png" alt="Brasão da Polícia Militar" class="mx-auto mb-4 h-28 w-auto">
            <h1 class="text-3xl font-bold text-cyan-400">10º BPM - 2ª CIA</h1>
            <p class="text-gray-400 mt-2">Selecione o módulo para prosseguir.</p>
        </header>
        
        <div class="space-y-4">
            
            <a href="boletimdeocorrencias.html" class="block bg-gray-700 hover:bg-gray-600 transition-all duration-300 p-6 rounded-lg shadow-md group">
                <div class="flex items-center space-x-4">
                    <div class="bg-cyan-500/20 text-cyan-400 p-3 rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                        </svg>
                    </div>
                    <div>
                        <h2 class="text-xl font-semibold text-white">Boletim de Ocorrências (BETA)</h2>
                        <p class="text-gray-400 text-sm group-hover:text-cyan-300">Acessar o portal de boletins.</p>
                    </div>
                </div>
            </a>

            <a href="permutas.html" class="block bg-gray-700 hover:bg-gray-600 transition-all duration-300 p-6 rounded-lg shadow-md group">
                 <div class="flex items-center space-x-4">
                    <div class="bg-purple-500/20 text-purple-400 p-3 rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M8 7h12m0 0l-4-4m4 4l-4 4m0 6H4m0 0l4 4m-4-4l4-4" />
                        </svg>
                    </div>
                    <div>
                        <h2 class="text-xl font-semibold text-white">Portal de Permutas</h2>
                        <p class="text-gray-400 text-sm group-hover:text-purple-300">Acessar o sistema de permutas.</p>
                    </div>
                </div>
            </a>
            
        </div>

        <footer class="text-center text-gray-500 text-xs pt-4">
            <p>&copy; 2025 - Todos os direitos reservados.</p>
            <p class="mt-2">Desenvolvido por Sales</p>
        </footer>
    </div>

</body>

</html>



