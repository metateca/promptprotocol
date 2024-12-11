# Chatbot Financeiro Baseado em Evidências

Este chatbot é uma adaptação do projeto ChatGPT-Vercel, com foco exclusivo em diálogos homem-robô relacionados ao contexto financeiro. Ele herda a interface elegante e funcionalidades avançadas do projeto original, mas com ajustes específicos para promover interações informativas e precisas no setor financeiro.

## Características Principais

### Interface Clara e Funcional
Mantém a interface limpa e intuitiva do ChatGPT-Vercel, facilitando o uso tanto para iniciantes quanto para especialistas do mercado financeiro.

### Suporte a PWA
Permite instalação como um aplicativo web progressivo (PWA) para acesso rápido e conveniente.

### Prompts Pré-definidos
Inclui prompts focados em temas financeiros, permitindo conversas rápidas e assertivas sobre tópicos específicos. A busca por prompts é feita com `Espaço` ou `/`, destacando os termos correspondentes.

### Múltiplas Conversas
Permite criar múltiplas sessões de conversa, cada uma com configurações individuais, como o "papel" do robô (por exemplo, especialista em planejamento financeiro, análise de investimentos, ou gestão de riscos). As conversas podem ser acessadas diretamente por URLs. A busca por conversas e histórico de mensagens é feita com `EspaçoEspaço` ou `//`.

### Exportação e Importação
Oferece a possibilidade de exportar e importar conversas e configurações para backup e compartilhamento de insights financeiros.

### Monitoramento de Tokens
Exibe em tempo real o consumo de tokens durante a conversa, permitindo controle sobre os custos de interação.

### Consulta de Saldo
Integra métodos para consulta de saldo da API OpenAI, incluindo agendamento e envio de notificações via plataformas externas (opcional).

### Suporte a Query URL
Permite usar o chatbot como um mecanismo de busca, respondendo diretamente a perguntas via URL (exemplo: `url?q=Como diversificar um portfólio?`).

---

## Adaptações para o Contexto Financeiro

### Prompts Financeiros
Os prompts pré-definidos abordam tópicos relevantes, como:
- "Explique a importância da diversificação de portfólio."
- "Quais são os principais riscos em operações cambiais?"
- "Descreva estratégias de hedge para proteger contra volatilidade."
- "Como calcular o retorno esperado de um investimento?"
- "Explique os benefícios de um planejamento financeiro de longo prazo."

### Personalização do Papel do Robô
Cada conversa pode ser configurada para que o robô assuma um papel específico, como:
- Consultor financeiro
- Especialista em gestão de riscos
- Analista de investimentos
- Planejador financeiro pessoal

### Ênfase em Evidências e Conformidade
O chatbot prioriza respostas baseadas em evidências financeiras e em conformidade com normas do mercado, evitando especulações ou informações imprecisas.

### Citação de Fontes
Pode ser configurado para citar fontes confiáveis, aumentando a transparência e a credibilidade das respostas fornecidas.

### Moderação de Respostas
O chatbot evita respostas que possam promover práticas financeiras arriscadas ou fora de conformidade com regulamentações do mercado.

---

## Dicas de Uso

### Contexto Efetivo
Remova partes irrelevantes ou incorretas da conversa para manter o contexto financeiro preciso. O contexto é crucial para respostas coerentes e alinhadas aos objetivos.

### Bloqueio de Mensagens
Use o bloqueio de mensagens (clicando no avatar) para manter informações importantes no contexto, mesmo ao limpar a conversa ou desativar o histórico.

### Entrada de Texto
- **Enter** para enviar (opcional), **Shift+Enter** para nova linha.
- **Espaço** ou **/** para buscar prompts.
- **EspaçoEspaço** ou **//** para buscar conversas e histórico.
- **↑** para preencher a entrada com a última pergunta.

### Ações em Mensagens
- **Perguntas**: Editar (preenche a entrada), Reenviar, Excluir.
- **Respostas**: Copiar, Reenviar, Excluir.

### Configurações e Ações
- **Personificação**: Simule perguntas e respostas do usuário e do robô.
- **Geração de Markdown**: Crie um texto Markdown da conversa.
- **Limpar Conversa**: Apague o histórico da conversa.
- **Configurações Globais**: Defina senha, chave API, envio com Enter.
- **Configurações da Conversa**: Defina título, ícone, temperatura, modelo, histórico.

---

## Implementação

### Implantação
- Use o botão "Deploy with Vercel" ou faça um fork do repositório e importe para o Vercel.

### Configuração
- Defina as variáveis de ambiente, como chave API e senha.

### Personalização
- Ajuste os prompts, o "papel" do robô e outras configurações para atender às suas necessidades específicas no setor financeiro.
