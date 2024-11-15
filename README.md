# AtividadeFase3_Solubio

## Descrição do Projeto

Esta documentação descreve a arquitetura de solução desenvolvida para o Chatbot Dra. Jô, considerando os objetivos de:
- Melhorar a experiência do cliente.
- Reduzir o tempo de resposta.
- Fornecer interações eficientes e precisas.

## Componentes da Arquitetura

1. **Interface de Usuário (Front-end)**:
   - **WhatsApp**: Canal de comunicação para interações diretas com os usuários.
   - **Widget no Site**: Ponto de acesso ao chatbot via site institucional.

2. **Motor de Processamento de Linguagem Natural (NLP)**:
   - **Dialogflow**: Tecnologia responsável por interpretar as mensagens dos usuários e determinar as respostas adequadas com base na linguagem natural.

3. **Camada de Back-end**:
   - **Python (Flask/Django)**: Gerenciamento da lógica de negócios, conectando os dados do usuário e os sistemas de apoio.

4. **Banco de Dados**:
   - **MySQL**: Armazenamento de histórico de interações, informações de clientes e dados analíticos.

5. **Infraestrutura**:
   - **Google Cloud Platform**: Hospedagem escalável e segura para o back-end e o processamento do chatbot.

6. **Integrações**:
   - **API Gateway**: Facilita a comunicação entre o chatbot e sistemas de terceiros, como CRMs e ferramentas de análise.

7. **Insights e Manutenção**:
   - Monitora e melhora o aprendizado de máquina com base nas interações, garantindo a evolução contínua do chatbot.

## Funções dos Componentes

### Extraídas do PDF Enviado
- **Usuário**: Interage diretamente com o chatbot.
- **ChatBot Dra. Jô**: Central de processamento das solicitações do usuário.
- **DialogFlow**: Faz o processamento da linguagem natural e conecta o front-end ao back-end.
- **Cientista de Dados**: Realiza melhorias contínuas no aprendizado do chatbot, garantindo a acuracidade das respostas.
- **Banco de Dados MySQL**: Armazena informações das interações, permitindo consultas e análise posterior.
- **Infraestrutura Google Cloud**: Fornece um ambiente seguro e escalável para toda a solução.

## Interações

1. O usuário se comunica com o chatbot via WhatsApp ou site.
2. O chatbot utiliza o Dialogflow para interpretar a mensagem e encaminhá-la para o back-end.
3. O back-end processa a solicitação e consulta o banco de dados ou serviços externos via API Gateway.
4. A resposta é retornada ao usuário por meio da interface de comunicação.

## Arquivos

- **Arquitetura_Chatbot_Dra_Jo.drawio**: Esquema inicial da arquitetura.
- **Arquitetura_Chatbot_Dra_Jo_Interacoes.drawio**: Versão detalhada com as interações entre componentes.

## Resultados Esperados

- Redução do tempo de resposta para solicitações de clientes.
- Atendimento escalável e eficiente.
- Evolução contínua no aprendizado e na precisão do chatbot.

