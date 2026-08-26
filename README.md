EpiCare ISCAL — Apoio Diagnóstico em Epilepsia (ILAE 2025)

EpiCare ISCAL é uma aplicação web / Progressive Web App (PWA) de consulta rápida e auxílio à decisão clínica (Point-of-Care), desenvolvida especialmente para residentes de neurologia, emergencistas e médicos em atendimento prático na emergência, enfermaria e ambulatório.

👨‍⚕️ Autoria e Créditos

Idealização e Conteúdo: Dr. Marcelo Simplício Carvalho

Base Científica: Classificação Oficial ILAE 2025 & Epilepsydiagnosis.org

🎯 Objetivo

Permitir que o médico realize o raciocínio diagnóstico completo e estruturado à beira do leito em 4 etapas rápidas:

Classificação da Crise Epiléptica segundo as diretrizes ILAE 2025.

Localização Semiológica Neuroanatômica Automática da zona epileptogênica provável.

Diagnóstico Sindrômico filtrado por faixa etária e achados de EEG.

Investigação Etiológica pautada nos 6 pilares da ILAE.

✨ Principais Funcionalidades

1. Classificador de Crises em Tempo Real (ILAE 2025)

Árvore de Decisão Rápida: Classificação entre crises Focais, Generalizadas, Desconhecidas e Não Classificadas.

Avaliação do Nível de Consciência: Avaliação criteriosa baseada na Percepção + Reatividade.

Manifestações Observáveis e Não Observáveis: Inclusão de auras, automatismos e termos como Mioclonia Negativa Epiléptica.

Gerador Automático de Laudo para Prontuário: Botão de cópia rápida com síntese técnica formatada para colar na evolução médica.

2. Localizador Semiológico Automático

Motor de inferência em tempo real que analisa os sintomas selecionados e a narrativa do evento para sugerir a Zona Epileptogênica Provável (Lobo Temporal Medial, Frontal, Parietal, Occipital ou Ínsula/Opercular).

3. Assistente de Diagnóstico Sindrômico (Epilepsydiagnosis.org)

Busca e filtragem instantânea de síndromes por faixa etária de início (Neonatal, Lactente, Infância, Adolescência e Adulto).

Apresentação dos padrões característicos de EEG.

Destaque para Fármacos Indicados e Fármacos Contraindicados (para prevenção de agravamento de crises).

4. Guia de Localização e Checklist Etiológico

Mapeamento sintoma-lobo e checklist das 6 categorias etiológicas (Estrutural, Genética, Infecciosa, Metabólica, Imune e Desconhecida).

5. Glossário Semiológico

Dicionário operacional para rápida checagem dos conceitos e terminologias oficiais da ILAE 2025.

📱 Instalação no Celular (PWA)

O EpiCare ISCAL funciona como um Progressive Web App (PWA) e pode ser instalado diretamente na tela inicial do smartphone sem necessidade de loja de aplicativos:

iOS (iPhone / Safari):

Acesse o link da aplicação pelo Safari.

Toque no botão Compartilhar (quadrado com seta para cima).

Selecione Adicionar à Tela de Início.

Android (Google Chrome):

Acesse o link da aplicação pelo Google Chrome.

Toque nos três pontos no canto superior direito.

Selecione Instalar aplicativo ou Adicionar à tela inicial.

📁 Estrutura do Repositório

.
├── index.html       # Arquivo principal do EpiCare ISCAL (Interface e Lógica)
├── manifest.json    # Arquivo de configuração de PWA (Nome, Ícones e Cores)
├── sw.js            # Service Worker para execução em tela cheia e cache
└── README.md        # Documentação do projeto


⚖️ Isenção de Responsabilidade Médica (Disclaimer)

O EpiCare ISCAL é uma ferramenta exclusiva de apoio à decisão clínica e consulta rápida destinada a médicos e residentes de medicina. O aplicativo não substitui o julgamento clínico individualizado do profissional responsável pelo atendimento.
