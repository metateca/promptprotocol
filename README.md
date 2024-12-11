## Chatbot Homem-Robô Baseado em Evidências Científicas (Adaptado do ChatGPT-Vercel)

Este chatbot é uma adaptação do projeto ChatGPT-Vercel, com foco em diálogos homem-robô baseados em evidências científicas. Ele herda a interface elegante e funcionalidades avançadas do projeto original, mas com ajustes para promover interações informativas e precisas.

**Características Principais:**

1. **Interface Clara e Funcional:** Mantém a interface limpa e intuitiva do ChatGPT-Vercel, facilitando o uso tanto para iniciantes quanto para usuários avançados.
2. **Suporte a PWA:** Permite instalação como um aplicativo web progressivo (PWA) para acesso rápido e conveniente.
3. **Prompts Pré-definidos:** Inclui prompts pré-definidos com foco em temas científicos, facilitando o início de conversas sobre tópicos específicos. A busca por prompts é feita com <kbd>Espaço</kbd> ou <kbd>/</kbd>, com destaque para os termos correspondentes.
4. **Múltiplas Conversas:** Permite a criação de múltiplas conversas (sessões), cada uma com configurações individuais, como o "papel" do robô (por exemplo, especialista em biologia, física, etc.). As conversas podem ser acessadas diretamente por URLs. A busca por conversas e histórico de mensagens é feita com <kbd>Espaço</kbd><kbd>Espaço</kbd> ou <kbd>/</kbd><kbd>/</kbd>.
5. **Exportação e Importação:** Permite exportar e importar conversas e configurações para backup e compartilhamento.
6. **Monitoramento de Tokens:** Exibe em tempo real o consumo de tokens durante a conversa, permitindo que o usuário interrompa a interação se necessário.
7. **Consulta de Saldo:** Suporta diferentes métodos de consulta de saldo da API OpenAI, incluindo agendamento e envio de notificações via WeChat (opcional).
8. **Suporte a Query URL:** Permite usar o chatbot como um mecanismo de busca, respondendo diretamente a perguntas na URL (ex: `url?q=O que é a fotossíntese?`).

**Adaptações para Diálogo Homem-Robô Baseado em Evidências Científicas:**

- **Prompts Científicos:** Os prompts pré-definidos são focados em temas científicos, como:
  - "Explique a teoria da relatividade."
  - "Quais são os principais mecanismos da evolução?"
  - "Descreva o ciclo da água."
  - "Quais são os benefícios da atividade física para a saúde?"
  - "Como funciona a inteligência artificial?"
- **Personalização do "Papel" do Robô:** Cada conversa pode ser configurada para que o robô assuma um papel específico, como um especialista em uma área científica particular. Isso permite que o robô forneça respostas mais precisas e relevantes.
- **Ênfase na Precisão e Evidência:** O chatbot é configurado para priorizar respostas baseadas em evidências científicas, evitando especulações ou informações não verificadas.
- **Citação de Fontes:** O chatbot pode ser configurado para citar fontes de informação quando apropriado, aumentando a transparência e a confiabilidade das respostas.
- **Moderação de Respostas:** O chatbot é configurado para evitar respostas que promovam desinformação científica ou teorias da conspiração.

**Dicas de Uso:**

- **Contexto Efetivo:** Remova partes irrelevantes ou incorretas da conversa para manter o contexto preciso. O contexto é crucial para respostas coerentes.
- **Bloqueio de Mensagens:** Use o bloqueio de mensagens (clicando no avatar) para manter informações importantes no contexto, mesmo ao limpar a conversa ou desativar o histórico.
- **Obtenção da Chave API OpenAI:** Registre-se no OpenAI e gere uma chave API.
- **Entrada de Texto:**
  - <kbd>Enter</kbd> para enviar (opcional), <kbd>Shift</kbd>+<kbd>Enter</kbd> para nova linha.
  - <kbd>Espaço</kbd> ou <kbd>/</kbd> para buscar prompts.
  - <kbd>Espaço</kbd><kbd>Espaço</kbd> ou <kbd>/</kbd><kbd>/</kbd> para buscar conversas e histórico.
  - <kbd>↑</kbd> para preencher a entrada com a última pergunta.
- **Ações em Mensagens:**
  - **Perguntas:** Editar (preenche a entrada), Reenviar, Excluir.
  - **Respostas:** Copiar, Reenviar, Excluir.
- **Navegação:** Clique no título para ir ao topo, clique na entrada para ir ao final.
- **Query URL:** Use `url?q=pergunta` para obter respostas diretas.

**Configurações e Ações:**

- **Personificação:** Simule perguntas e respostas do usuário e do robô.
- **Geração de Imagem:** Crie uma imagem da conversa para compartilhar.
- **Geração de Markdown:** Crie um texto Markdown da conversa.
- **Limpar Conversa:** Apague o histórico da conversa.
- **Configurações Globais:** Defina senha, chave API, envio com Enter.
- **Configurações da Conversa:** Defina título, ícone, temperatura, modelo, histórico.

**Implementação:**

1. **Implantação:** Use o botão "Deploy with Vercel" ou faça um fork do repositório e importe para o Vercel.
2. **Configuração:** Defina as variáveis de ambiente (chave API, senha, etc.).
3. **Personalização:** Ajuste os prompts, o "papel" do robô e outras configurações para atender às suas necessidades.
