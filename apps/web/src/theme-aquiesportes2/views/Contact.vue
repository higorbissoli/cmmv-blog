<template>
    <div class="w-full relative">
        <div class="lg:max-w-4xl md:max-w-3xl px-4 sm:px-6 mx-auto">
            <div class="bg-white rounded-lg px-4 sm:px-6 py-8">
                <h1 class="text-3xl font-bold mb-6 text-neutral-900">Contato</h1>
                <a id="contact" title="Contato"></a>
                <p class="mb-6 text-neutral-700 text-justify">Entre em contato conosco através dos canais abaixo. Nossa equipe está sempre pronta para esclarecer dúvidas, receber sugestões ou atender às suas necessidades.</p>

                <h2 class="text-2xl font-semibold mt-8 mb-4 text-neutral-800">Informações de Contato</h2>
                <a id="contact-info" title="Informações de Contato"></a>

                <div class="mb-6">
                    <h3 class="text-xl font-medium mt-6 mb-3 text-neutral-800">E-mail</h3>
                    <p class="mb-4 text-neutral-700 text-justify">Para questões gerais, parcerias, sugestões ou solicitações:</p>
                    <p class="mb-4 text-neutral-700"><strong>E-mail:</strong> <code class="px-1.5 py-0.5 bg-gray-100 rounded">higor@tos.world</code></p>
                </div>

                <div class="mb-6">
                    <h3 class="text-xl font-medium mt-6 mb-3 text-neutral-800">Redação</h3>
                    <p class="mb-4 text-neutral-700 text-justify">Para envio de releases, convites para eventos ou comunicação com a redação:</p>
                    <p class="mb-4 text-neutral-700"><strong>E-mail:</strong> <code class="px-1.5 py-0.5 bg-gray-100 rounded">higor@tos.world</code></p>
                </div>

                <div class="mb-6">
                    <h3 class="text-xl font-medium mt-6 mb-3 text-neutral-800">Publicidade e Parcerias</h3>
                    <p class="mb-4 text-neutral-700 text-justify">Para oportunidades de publicidade, parcerias comerciais e colaborações:</p>
                    <p class="mb-4 text-neutral-700"><strong>E-mail:</strong> <code class="px-1.5 py-0.5 bg-gray-100 rounded">higor@tos.world</code></p>
                </div>

                <h2 class="text-2xl font-semibold mt-8 mb-4 text-neutral-800">Redes Sociais</h2>
                <a id="social-media" title="Redes Sociais"></a>
                <p class="mb-4 text-neutral-700 text-justify">Siga-nos em nossas redes sociais para ficar por dentro das últimas notícias e interagir conosco:</p>
                
                <ul class="mb-6 pl-5 list-disc text-neutral-700 text-justify">
                    <li class="mb-2"><strong>Facebook:</strong> /aqiesportes</li>
                    <li class="mb-2"><strong>X:</strong> @aqiesportes</li>
                    <li class="mb-2"><strong>Instagram:</strong> @aqui_esportes</li>
                    <li class="mb-2"><strong>Telegram:</strong> <a href="https://t.me/+iAoa8PKqZChlZTEx" target="_blank" class="text-[#001E62] hover:underline">https://t.me/+iAoa8PKqZChlZTEx</a></li>
                </ul>

                <h2 class="text-2xl font-semibold mt-8 mb-4 text-neutral-800">Formulário de Contato</h2>
                <a id="contact-form" title="Formulário de Contato"></a>
                
                <div class="bg-gray-50 rounded-lg p-6 mb-6">
                    <form class="space-y-4">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <label for="name" class="block text-sm font-medium text-neutral-700 mb-1">Nome *</label>
                                <input type="text" id="name" name="name" required
                                    class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-[#001E62] focus:border-[#001E62]">
                            </div>
                            <div>
                                <label for="email" class="block text-sm font-medium text-neutral-700 mb-1">E-mail *</label>
                                <input type="email" id="email" name="email" required
                                    class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-[#001E62] focus:border-[#001E62]">
                            </div>
                        </div>
                        
                        <div>
                            <label for="subject" class="block text-sm font-medium text-neutral-700 mb-1">Assunto *</label>
                            <input type="text" id="subject" name="subject" required
                                class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-[#001E62] focus:border-[#001E62]">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-neutral-700 mb-1">Mensagem *</label>
                            <textarea id="message" name="message" rows="5" required
                                class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-[#001E62] focus:border-[#001E62]"></textarea>
                        </div>
                        
                        <div>
                            <button type="submit" 
                                class="bg-[#001E62] hover:bg-[#001545] text-white font-medium px-6 py-3 rounded-md transition-colors">
                                Enviar Mensagem
                            </button>
                        </div>
                    </form>
                </div>

                <h2 class="text-2xl font-semibold mt-8 mb-4 text-neutral-800">Horário de Atendimento</h2>
                <a id="business-hours" title="Horário de Atendimento"></a>
                <p class="mb-4 text-neutral-700 text-justify">Nossa equipe responde aos contatos nos seguintes horários:</p>
                <ul class="mb-6 pl-5 list-disc text-neutral-700 text-justify">
                    <li class="mb-2"><strong>Segunda a Sexta:</strong> 9h às 18h</li>
                    <li class="mb-2"><strong>Sábado:</strong> 9h às 14h</li>
                    <li class="mb-2"><strong>Domingo e Feriados:</strong> Não há atendimento</li>
                </ul>

                <div class="bg-blue-50 border-l-4 border-[#001E62] p-4 mb-6">
                    <div class="flex">
                        <div class="flex-shrink-0">
                            <svg class="h-5 w-5 text-[#001E62]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <div class="ml-3">
                            <p class="text-sm text-neutral-700">
                                <strong>Tempo de resposta:</strong> Normalmente respondemos em até 24 horas durante dias úteis. 
                                Para solicitações urgentes, utilize nossos canais de redes sociais.
                            </p>
                        </div>
                    </div>
                </div>

                <p class="text-sm text-neutral-600 mt-8">
                    Agradecemos o seu contato e interesse no <strong>Aqui Esportes</strong>. 
                    Faremos o possível para responder o mais rapidamente possível.
                </p>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
import { useHead } from '@unhead/vue';

useHead({
    title: 'Contato - Aqui Esportes',
    meta: [
        {
            name: 'description',
            content: 'Entre em contato com a equipe do Aqui Esportes. Informações de contato, formulário e redes sociais.'
        },
        {
            name: 'keywords',
            content: 'Aqui Esportes, contato, e-mail, redes sociais, redação, comercial'
        }
    ]
})
</script> 