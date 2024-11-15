# AtividadeFase3_Solubio

## Descrição do Projeto

Esta documentação descreve a arquitetura de solução desenvolvida para o Chatbot Dra. Jô, considerando os objetivos de:
- Melhorar a experiência do cliente.
- Reduzir o tempo de resposta.
- Fornecer interações eficientes e precisas.

## Componentes da Arquitetura

![image](https://github.com/user-attachments/assets/7b97feb2-c544-4795-ad49-edc70e85f1c0)

**usuário**

   O usuário será o cliente que estará em constante interação com o sistema de chatbot da Dra.Jô

**ChatBot**

   O chatbot será o responsável pelo front-end da interação com o usuário. Nele podemos realizar as perguntas e consultar todos os comandos propostos pela challenge

**Processamento de Linguagem Natural (NLP)**

   Tecnologia responsável por interpretar as mensagens dos usuários e determinar as respostas adequadas com base na linguagem natural. utilizaremos o Dialogflow para interagir e interpretar os dados

**Camada de Back-end**

   Gerenciamento da lógica de negócios, conectando os dados do usuário e os sistemas de apoio. Será utilizado o código Python que pe amplamente utilizado para soluções de machine learning e integração com        vários modelos e tipos de APIs
   
**Infraestrutura**

   Hospedagem escalável e segura para o back-end e o processamento do chatbot. Nele será utilizado o Google Cloud Platform, pois para a integração com o sistema Dialogflow contemplado para o processamento de     linguagem natural
   
**Banco de Dados**

   Armazenamento de histórico de interações, informações de clientes e dados analíticos. utilizaremos o MySQL para este tipo de interação.

**Insights e Manutenção**

   Podemos extrair insights importantes dos resultados do processamento de linguagem natural que analisados de forma correta, por um cientista de dados, teremos constantemente manutenções e aprimoramentos do     próprio código afim de aumentar a imersão da experiencia do usuário com o chatbot

## Previsão de custo Mensal

![image](https://github.com/user-attachments/assets/bdfbfc4c-505b-417d-ab95-e2c1cc644fe3)


## Resultados Esperados

**Redução significativa no tempo de resposta**: Automatizar o atendimento ao cliente permitirá respostas instantâneas, eliminando atrasos e melhorando a satisfação dos usuários ao atender demandas de forma ágil e precisa.

**Atendimento escalável e eficiente**: O chatbot será capaz de gerenciar simultaneamente um grande volume de solicitações, mantendo a consistência na qualidade das respostas, independentemente da quantidade de usuários atendidos.

**Evolução contínua no aprendizado e na precisão**: Com a implementação de técnicas de aprendizado de máquina, o chatbot será constantemente aprimorado. A análise das interações permitirá ajustes em tempo real para refinar respostas, reconhecer novas intenções e atender a demandas mais complexas.

**Melhor experiência do usuário (UX)**: A interface intuitiva e as respostas personalizadas, baseadas no histórico e nas preferências dos usuários, proporcionarão interações mais satisfatórias, reforçando o relacionamento com a marca.

**Geração de insights estratégicos**: A coleta de dados estruturados durante as interações permitirá análises mais detalhadas sobre o comportamento dos clientes, possibilitando decisões informadas e o desenvolvimento de novos serviços ou produtos.
