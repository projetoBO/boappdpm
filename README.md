<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Boletim de Ocorrência</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #483D8B; /* Fundo principal */
        }
        .shadow-3d {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.07), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        /* Estilos para caixas de seleção para se alinharem ao design */
        .form-checkbox-item {
            display: flex;
            align-items: center;
            margin-bottom: 0.5rem;
        }
        .form-checkbox-item label {
            margin-left: 0.5rem;
            font-size: 0.875rem;
            color: #4b5563;
            cursor: pointer;
        }
        .form-checkbox {
            height: 1rem;
            width: 1rem;
            border-radius: 0.25rem;
            border-color: #d1d5db;
            color: #3b82f6;
            transition: all 0.2s;
        }
        .form-checkbox:focus {
            --tw-ring-color: #3b82f6;
            border-color: #3b82f6;
        }
    </style>
</head>
<body class="p-4 sm:p-6 md:p-8">

    <div class="bg-white rounded-2xl shadow-3d p-6 md:p-10 max-w-5xl mx-auto">
        
        <header class="text-center mb-10">
            <img src="https://pm.ssp.ma.gov.br/wp-content/uploads/2023/05/BRASAO-SD-RAYOL-e1683655730963.png" alt="Brasão da Polícia Militar do Maranhão" class="w-20 h-auto mx-auto mb-4">
            <div class="border-b-2 border-gray-200 py-4">
                <h1 class="text-lg font-bold tracking-wide text-gray-700">ESTADO DO MARANHÃO</h1>
                <p class="text-sm text-gray-500">SECRETARIA DE SEGURANÇA PÚBLICA</p>
                <p class="text-sm text-gray-500">10º BATALHÃO DA POLÍCIA MILITAR - 2ª CIA</p>
            </div>
            <h2 class="text-2xl sm:text-3xl font-extrabold text-gray-800 mt-8">Formulário de Boletim de Ocorrência</h2>
            <p class="text-center text-lg font-semibold text-gray-600 -mt-1 mb-8">TURIAÇU</p>
        </header>

        <form class="jotform-form" action="https://submit.jotform.com/submit/252474593439064" method="post" name="form_252474593439064" id="252474593439064" accept-charset="utf-8" autocomplete="on">
            <input type="hidden" name="formID" value="252474593439064" />
            
            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">1. Dados da Ocorrência</h3>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-4">
                    <div>
                        <label for="input_3" class="text-sm font-medium text-gray-600 block mb-1">BO N°:</label>
                        <input type="text" id="input_3" name="q3_boN" class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg">
                    </div>
                    <div>
                        <label for="input_55_timeInput" class="text-sm font-medium text-gray-600 block mb-1">Hora do Fato:</label>
                        <input class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg" id="input_55_timeInput" name="q55_time[timeInput]" type="text" placeholder="HH:MM">
                    </div>
                    <div>
                        <label for="lite_mode_67" class="text-sm font-medium text-gray-600 block mb-1">Data da Ocorrência:</label>
                        <input class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg" id="lite_mode_67" name="q67_dataDa[litemode]" type="text" placeholder="DD-MM-YYYY">
                    </div>
                     <div class="lg:col-span-2">
                        <label for="input_5" class="text-sm font-medium text-gray-600 block mb-1">Local da Ocorrência:</label>
                        <input type="text" id="input_5" name="q5_localDa" class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg">
                    </div>
                     <div>
                        <label class="text-sm font-medium text-gray-600 block mb-1">Autoria:</label>
                        <div id="cid_54" class="flex items-center space-x-4 pt-3">
                            <span class="form-checkbox-item"><input type="checkbox" class="form-checkbox" id="input_54_0" name="q54_autoria[]" value="Conhecida"><label for="input_54_0">Conhecida</label></span>
                            <span class="form-checkbox-item"><input type="checkbox" class="form-checkbox" id="input_54_1" name="q54_autoria[]" value="Desconhecida"><label for="input_54_1">Desconhecida</label></span>
                        </div>
                    </div>
                     <div>
                        <label for="input_8" class="text-sm font-medium text-gray-600 block mb-1">Bairro:</label>
                        <input type="text" id="input_8" name="q8_bairro" class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg">
                    </div>
                    <div class="lg:col-span-2">
                        <label for="input_9" class="text-sm font-medium text-gray-600 block mb-1">Ponto de Referência:</label>
                        <input type="text" id="input_9" name="q9_pontoDe" class="w-full p-3 border border-gray-300 bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors duration-200 rounded-lg">
                    </div>
                </div>
            </div>

            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">2. Envolvido 1</h3>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-4">
                    <div class="lg:col-span-3">
                        <label class="text-sm font-medium text-gray-600 block mb-2">Envolvimento:</label>
                         <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2">
                            <span class="form-checkbox-item"><input id="q81_0" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Condutor"><label for="q81_0">Condutor</label></span>
                            <span class="form-checkbox-item"><input id="q81_1" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Testemunha"><label for="q81_1">Testemunha</label></span>
                            <span class="form-checkbox-item"><input id="q81_2" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Vítima"><label for="q81_2">Vítima</label></span>
                            <span class="form-checkbox-item"><input id="q81_3" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Conduzido"><label for="q81_3">Conduzido</label></span>
                            <span class="form-checkbox-item"><input id="q81_4" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Proprietário"><label for="q81_4">Proprietário</label></span>
                            <span class="form-checkbox-item"><input id="q81_5" type="checkbox" class="form-checkbox" name="q81_typeA[]" value="Outros"><label for="q81_5">Outros</label></span>
                        </div>
                    </div>
                    <div class="lg:col-span-2"><label for="input_11" class="text-sm font-medium text-gray-600 block mb-1">Nome:</label><input type="text" id="input_11" name="q11_nome" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="lite_mode_71" class="text-sm font-medium text-gray-600 block mb-1">Data de Nascimento:</label><input type="text" id="lite_mode_71" name="q71_dataDe71[litemode]" placeholder="DD-MM-YYYY" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-2"><label for="input_13" class="text-sm font-medium text-gray-600 block mb-1">Residência:</label><input type="text" id="input_13" name="q13_residencia" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_16" class="text-sm font-medium text-gray-600 block mb-1">N° da Casa:</label><input type="text" id="input_16" name="q16_nDa" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_15" class="text-sm font-medium text-gray-600 block mb-1">Bairro:</label><input type="text" id="input_15" name="q15_bairro15" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_14" class="text-sm font-medium text-gray-600 block mb-1">Cidade:</label><input type="text" id="input_14" name="q14_cidade" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_18" class="text-sm font-medium text-gray-600 block mb-1">Profissão:</label><input type="text" id="input_18" name="q18_profissao" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-1"><label class="text-sm font-medium text-gray-600 block mb-2">Tipo de Documento:</label><div class="flex items-center space-x-4 pt-1"><span class="form-checkbox-item"><input id="q86_0" type="checkbox" class="form-checkbox" name="q86_tipoDe[]" value="CPF"><label for="q86_0">CPF</label></span><span class="form-checkbox-item"><input id="q86_1" type="checkbox" class="form-checkbox" name="q86_tipoDe[]" value="CI"><label for="q86_1">CI</label></span><span class="form-checkbox-item"><input id="q86_2" type="checkbox" class="form-checkbox" name="q86_tipoDe[]" value="CNH"><label for="q86_2">CNH</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_17" class="text-sm font-medium text-gray-600 block mb-1">Nº do Documento:</label><input type="text" id="input_17" name="q17_nDo" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                </div>
            </div>
            
            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">3. Envolvido 2 (Opcional)</h3>
                 <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-4">
                    <div class="lg:col-span-3"><label class="text-sm font-medium text-gray-600 block mb-2">Envolvimento:</label><div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2"><span class="form-checkbox-item"><input id="q83_0" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Condutor"><label for="q83_0">Condutor</label></span><span class="form-checkbox-item"><input id="q83_1" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Testemunha"><label for="q83_1">Testemunha</label></span><span class="form-checkbox-item"><input id="q83_2" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Vítima"><label for="q83_2">Vítima</label></span><span class="form-checkbox-item"><input id="q83_3" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Conduzido"><label for="q83_3">Conduzido</label></span><span class="form-checkbox-item"><input id="q83_4" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Proprietário"><label for="q83_4">Proprietário</label></span><span class="form-checkbox-item"><input id="q83_5" type="checkbox" class="form-checkbox" name="q83_envolvimento83[]" value="Outros"><label for="q83_5">Outros</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_20" class="text-sm font-medium text-gray-600 block mb-1">Nome:</label><input type="text" id="input_20" name="q20_nome20" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="lite_mode_73" class="text-sm font-medium text-gray-600 block mb-1">Data de Nascimento:</label><input type="text" id="lite_mode_73" name="q73_dataDe[litemode]" placeholder="DD-MM-YYYY" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-2"><label for="input_22" class="text-sm font-medium text-gray-600 block mb-1">Residência:</label><input type="text" id="input_22" name="q22_residencia22" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_25" class="text-sm font-medium text-gray-600 block mb-1">N° da Casa:</label><input type="text" id="input_25" name="q25_n25" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_24" class="text-sm font-medium text-gray-600 block mb-1">Bairro:</label><input type="text" id="input_24" name="q24_bairro24" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_23" class="text-sm font-medium text-gray-600 block mb-1">Cidade:</label><input type="text" id="input_23" name="q23_cidade23" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_27" class="text-sm font-medium text-gray-600 block mb-1">Profissão:</label><input type="text" id="input_27" name="q27_profissao27" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-1"><label class="text-sm font-medium text-gray-600 block mb-2">Tipo de Documento:</label><div class="flex items-center space-x-4 pt-1"><span class="form-checkbox-item"><input id="q87_0" type="checkbox" class="form-checkbox" name="q87_tipoDe87[]" value="CPF"><label for="q87_0">CPF</label></span><span class="form-checkbox-item"><input id="q87_1" type="checkbox" class="form-checkbox" name="q87_tipoDe87[]" value="CI"><label for="q87_1">CI</label></span><span class="form-checkbox-item"><input id="q87_2" type="checkbox" class="form-checkbox" name="q87_tipoDe87[]" value="CNH"><label for="q87_2">CNH</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_26" class="text-sm font-medium text-gray-600 block mb-1">Nº do Documento:</label><input type="text" id="input_26" name="q26_n26" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                </div>
            </div>
            
            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">4. Envolvido 3 (Opcional)</h3>
                 <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-4">
                    <div class="lg:col-span-3"><label class="text-sm font-medium text-gray-600 block mb-2">Envolvimento:</label><div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2"><span class="form-checkbox-item"><input id="q84_0" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Condutor"><label for="q84_0">Condutor</label></span><span class="form-checkbox-item"><input id="q84_1" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Testemunha"><label for="q84_1">Testemunha</label></span><span class="form-checkbox-item"><input id="q84_2" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Vítima"><label for="q84_2">Vítima</label></span><span class="form-checkbox-item"><input id="q84_3" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Conduzido"><label for="q84_3">Conduzido</label></span><span class="form-checkbox-item"><input id="q84_4" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Proprietário"><label for="q84_4">Proprietário</label></span><span class="form-checkbox-item"><input id="q84_5" type="checkbox" class="form-checkbox" name="q84_envolvimento[]" value="Outros"><label for="q84_5">Outros</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_29" class="text-sm font-medium text-gray-600 block mb-1">Nome:</label><input type="text" id="input_29" name="q29_nome29" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="lite_mode_74" class="text-sm font-medium text-gray-600 block mb-1">Data de Nascimento:</label><input type="text" id="lite_mode_74" name="q74_dataDe74[litemode]" placeholder="DD-MM-YYYY" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-2"><label for="input_31" class="text-sm font-medium text-gray-600 block mb-1">Residência:</label><input type="text" id="input_31" name="q31_residencia31" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_34" class="text-sm font-medium text-gray-600 block mb-1">N° da Casa:</label><input type="text" id="input_34" name="q34_n34" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_33" class="text-sm font-medium text-gray-600 block mb-1">Bairro:</label><input type="text" id="input_33" name="q33_bairro33" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_32" class="text-sm font-medium text-gray-600 block mb-1">Cidade:</label><input type="text" id="input_32" name="q32_cidade32" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_36" class="text-sm font-medium text-gray-600 block mb-1">Profissão:</label><input type="text" id="input_36" name="q36_profissao36" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-1"><label class="text-sm font-medium text-gray-600 block mb-2">Tipo de Documento:</label><div class="flex items-center space-x-4 pt-1"><span class="form-checkbox-item"><input id="q88_0" type="checkbox" class="form-checkbox" name="q88_tipoDe88[]" value="CPF"><label for="q88_0">CPF</label></span><span class="form-checkbox-item"><input id="q88_1" type="checkbox" class="form-checkbox" name="q88_tipoDe88[]" value="CI"><label for="q88_1">CI</label></span><span class="form-checkbox-item"><input id="q88_2" type="checkbox" class="form-checkbox" name="q88_tipoDe88[]" value="CNH"><label for="q88_2">CNH</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_35" class="text-sm font-medium text-gray-600 block mb-1">Nº do Documento:</label><input type="text" id="input_35" name="q35_n35" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                </div>
            </div>
            
             <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">5. Envolvido 4 (Opcional)</h3>
                 <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-4">
                    <div class="lg:col-span-3"><label class="text-sm font-medium text-gray-600 block mb-2">Envolvimento:</label><div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2"><span class="form-checkbox-item"><input id="q85_0" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Condutor"><label for="q85_0">Condutor</label></span><span class="form-checkbox-item"><input id="q85_1" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Testemunha"><label for="q85_1">Testemunha</label></span><span class="form-checkbox-item"><input id="q85_2" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Vítima"><label for="q85_2">Vítima</label></span><span class="form-checkbox-item"><input id="q85_3" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Conduzido"><label for="q85_3">Conduzido</label></span><span class="form-checkbox-item"><input id="q85_4" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Proprietário"><label for="q85_4">Proprietário</label></span><span class="form-checkbox-item"><input id="q85_5" type="checkbox" class="form-checkbox" name="q85_envolvimento85[]" value="Outros"><label for="q85_5">Outros</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_38" class="text-sm font-medium text-gray-600 block mb-1">Nome:</label><input type="text" id="input_38" name="q38_nome38" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="lite_mode_75" class="text-sm font-medium text-gray-600 block mb-1">Data de Nascimento:</label><input type="text" id="lite_mode_75" name="q75_date75[litemode]" placeholder="DD-MM-YYYY" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-2"><label for="input_40" class="text-sm font-medium text-gray-600 block mb-1">Residência:</label><input type="text" id="input_40" name="q40_residencia40" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_43" class="text-sm font-medium text-gray-600 block mb-1">N° da Casa:</label><input type="text" id="input_43" name="q43_n43" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_42" class="text-sm font-medium text-gray-600 block mb-1">Bairro:</label><input type="text" id="input_42" name="q42_bairro42" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_41" class="text-sm font-medium text-gray-600 block mb-1">Cidade:</label><input type="text" id="input_41" name="q41_cidade41" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div><label for="input_45" class="text-sm font-medium text-gray-600 block mb-1">Profissão:</label><input type="text" id="input_45" name="q45_profissao45" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                    <div class="lg:col-span-1"><label class="text-sm font-medium text-gray-600 block mb-2">Tipo de Documento:</label><div class="flex items-center space-x-4 pt-1"><span class="form-checkbox-item"><input id="q89_0" type="checkbox" class="form-checkbox" name="q89_tipoDe89[]" value="CPF"><label for="q89_0">CPF</label></span><span class="form-checkbox-item"><input id="q89_1" type="checkbox" class="form-checkbox" name="q89_tipoDe89[]" value="CI"><label for="q89_1">CI</label></span><span class="form-checkbox-item"><input id="q89_2" type="checkbox" class="form-checkbox" name="q89_tipoDe89[]" value="CNH"><label for="q89_2">CNH</label></span></div></div>
                    <div class="lg:col-span-2"><label for="input_44" class="text-sm font-medium text-gray-600 block mb-1">Nº do Documento:</label><input type="text" id="input_44" name="q44_n44" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></div>
                </div>
            </div>

            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">6. Descrição do Fato e Materiais</h3>
                <div class="space-y-4">
                     <div>
                        <label for="input_46" class="text-sm font-medium text-gray-600 block mb-1">Armas, Objetos e Materiais Apreendidos/Apresentados:</label>
                        <textarea id="input_46" name="q46_armasObjetos" rows="4" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></textarea>
                    </div>
                     <div>
                        <label for="input_47" class="text-sm font-medium text-gray-600 block mb-1">Histórico (Descrição Sumária):</label>
                        <textarea id="input_47" name="q47_historicodescricao" rows="6" class="w-full p-3 border border-gray-300 bg-white rounded-lg"></textarea>
                    </div>
                </div>
            </div>
            
            <div class="mb-8 p-6 bg-gray-50 rounded-xl border border-gray-200">
                <h3 class="text-lg font-bold text-gray-800 mb-6 uppercase tracking-wider border-b pb-2">7. Relator</h3>
                <div class="grid md:grid-cols-3 gap-x-8 gap-y-4">
                     <div>
                        <label for="input_50" class="text-sm font-medium text-gray-600 block mb-1">Posto/Graduação:</label>
                        <input type="text" id="input_50" name="q50_postoGraduacao" class="w-full p-3 border border-gray-300 bg-white rounded-lg">
                    </div>
                     <div>
                        <label for="input_58" class="text-sm font-medium text-gray-600 block mb-1">Nome:</label>
                        <input type="text" id="input_58" name="q58_nome58" class="w-full p-3 border border-gray-300 bg-white rounded-lg">
                    </div>
                     <div>
                        <label for="input_51" class="text-sm font-medium text-gray-600 block mb-1">N° Matrícula:</label>
                        <input type="text" id="input_51" name="q51_nMatricula" class="w-full p-3 border border-gray-300 bg-white rounded-lg">
                    </div>
                </div>
            </div>

            <div class="flex flex-col md:flex-row flex-wrap justify-center items-center gap-4 mt-10 border-t-2 border-gray-100 pt-8">
                <button id="input_59" type="submit" class="w-full md:w-auto bg-blue-700 hover:bg-blue-800 text-white font-bold py-3 px-6 rounded-xl shadow-lg transition-transform transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-blue-300 flex items-center justify-center gap-2">
                    <i data-lucide="download" class="w-5 h-5"></i>
                    <span>Baixar PDF</span>
                </button>
                <button id="enviar_whatsapp" type="button" class="w-full md:w-auto bg-green-600 hover:bg-green-700 text-white font-bold py-3 px-6 rounded-xl shadow-lg transition-transform transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-green-300 flex items-center justify-center gap-2">
                     <i data-lucide="send" class="w-5 h-5"></i>
                    <span>Enviar Release - WhatsApp</span>
                </button>
                 <button id="botao_atualizar" type="button" class="w-full md:w-auto bg-gray-600 hover:bg-gray-700 text-white font-bold py-3 px-6 rounded-xl shadow-lg transition-transform transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-gray-300 flex items-center justify-center gap-2">
                    <i data-lucide="refresh-cw" class="w-5 h-5"></i>
                    <span>Atualizar Página</span>
                </button>
                 <button id="input_reset_59" type="reset" class="w-full md:w-auto bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-6 rounded-xl shadow-lg transition-transform transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-red-300 flex items-center justify-center gap-2">
                    <i data-lucide="trash-2" class="w-5 h-5"></i>
                    <span>Limpar</span>
                </button>
            </div>
             <input type="hidden" class="simple_spc" id="simple_spc" name="simple_spc" value="252474593439064" />
        </form>
    </div>

    <script>
        // Inicializa a biblioteca de ícones Lucide
        lucide.createIcons();

        // Função para enviar os dados formatados para o WhatsApp
        function enviarViaWhatsApp() {
            const bo_n = document.getElementById('input_3')?.value || '';
            const data_ocorrencia = document.getElementById('lite_mode_67')?.value || '';
            const hora_fato = document.getElementById('input_55_timeInput')?.value || '';
            const local = document.getElementById('input_5')?.value || '';
            const bairro = document.getElementById('input_8')?.value || '';
            const ponto_ref = document.getElementById('input_9')?.value || '';
            const material_apreendido = document.getElementById('input_46')?.value || '';
            const relatorio = document.getElementById('input_47')?.value || '';

            let mensagem = `*POLÍCIA MILITAR DO MARANHÃO*\n`;
            mensagem += `*CPI / CPAI-5 / 10º BPM*\n\n`;
            mensagem += `*TÍTULO DA OCORRÊNCIA:*\n\n`;
            mensagem += `*BO №:* ${bo_n}\n`;
            mensagem += `*Data:* ${data_ocorrencia}\n`;
            mensagem += `*Hora:* ${hora_fato}\n`;
            const localCompleto = [local, bairro, ponto_ref].filter(Boolean).join(', ');
            mensagem += `*Local:* ${localCompleto}\n`;
            mensagem += `*Localização:*\n\n`;
            mensagem += `*Procedimentos adotados:*\n\n`;

            let envolvidos_texto = "";
            
            // Função interna para processar cada envolvido e adicionar ao texto
            function adicionarEnvolvido(num, nome_id, doc_id, end_id, envolvimento_name) {
                const nome = document.getElementById(nome_id)?.value;
                if (!nome) return ""; // Se não houver nome, pula este envolvido

                const doc = document.getElementById(doc_id)?.value || 'Não informado';
                const residencia = document.getElementById(end_id)?.value || 'Não informado';

                let tipoEnvolvimento = "";
                const checkboxes = document.querySelectorAll(`input[name="${envolvimento_name}"]:checked`);
                
                if (checkboxes && checkboxes.length > 0) {
                    tipoEnvolvimento = checkboxes[0].value;
                } else {
                    return ""; 
                }
                
                const validos = ["Vítima", "Conduzido", "Proprietário", "Outros"];
                if (validos.includes(tipoEnvolvimento)) {
                    return `*${tipoEnvolvimento.toUpperCase()}:*\nNome: ${nome}\nCPF/Doc: ${doc}\nEndereço: ${residencia}\n\n`;
                }
                return "";
            }

            // Coleta dados dos 4 envolvidos
            envolvidos_texto += adicionarEnvolvido(1, 'input_11', 'input_17', 'input_13', 'q81_typeA[]');
            envolvidos_texto += adicionarEnvolvido(2, 'input_20', 'input_26', 'input_22', 'q83_envolvimento83[]');
            envolvidos_texto += adicionarEnvolvido(3, 'input_29', 'input_35', 'input_31', 'q84_envolvimento[]');
            envolvidos_texto += adicionarEnvolvido(4, 'input_38', 'input_44', 'input_40', 'q85_envolvimento85[]');

            mensagem += envolvidos_texto;
            mensagem += `*Material Apreendido/apresentado:*\n${material_apreendido}\n\n`;
            mensagem += `*Relatório:*\n${relatorio}\n\n`;
            mensagem += `*Guarnição:*`;

            const numero = "+5598985342874"; // Número de destino
            const urlWhatsApp = `https://api.whatsapp.com/send?phone=${numero}&text=${encodeURIComponent(mensagem)}`;
            window.open(urlWhatsApp, '_blank');
        }

        // Atribui as funções aos botões
        document.getElementById('enviar_whatsapp')?.addEventListener('click', enviarViaWhatsApp);
        document.getElementById('botao_atualizar')?.addEventListener('click', () => location.reload());
        
    </script>
</body>
</html>
