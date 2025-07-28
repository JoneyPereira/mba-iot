# mba-iot
```mermaid
graph TD
    A[Internet das Coisas - IoT] --> A1[Objetivo: Conectar objetos físicos à internet]
    A --> A2[Componentes]
    A2 --> A2a[Dispositivos e Sensores]
    A2 --> A2b[Conectividade: Wi-Fi, LoRa, 5G]
    A2 --> A2c[Gateways]
    A2 --> A2d[Plataforma em Nuvem]

    A --> A3[Geração de grandes volumes de dados]
    A3 --> B[Big Data]

    B --> B1[Objetivo: Armazenar, processar e analisar dados]
    B --> B2[Características - Os 5 V's]
    B2 --> B2a[Volume]
    B2 --> B2b[Velocidade]
    B2 --> B2c[Variedade]
    B2 --> B2d[Veracidade]
    B2 --> B2e[Valor]

    B --> B3[Tecnologias]
    B3 --> B3a[Armazenamento: Hadoop, NoSQL]
    B3 --> B3b[Processamento: Spark, Kafka]
    B3 --> B3c[Visualização: Power BI, Grafana]

    A3 --> C[Integração IoT + Big Data]
    B --> C

    C --> C1[Fases da Integração]
    C1 --> C1a[Captura de dados]
    C1 --> C1b[Transmissão]
    C1 --> C1c[Armazenamento]
    C1 --> C1d[Processamento]
    C1 --> C1e[Análise com IA / ML]
    C1 --> C1f[Ações automatizadas]

    C --> C2[Impactos]
    C2 --> C2a[Eficiência operacional]
    C2 --> C2b[Automação inteligente]
    C2 --> C2c[Novos modelos de negócio]
    C2 --> C2d[Desafios: Segurança e privacidade]
```
## Resumo visual: Fundamentos de Big Data e Internet das Coisas II
```mermaid
graph TD
  A[Fundamentos de Big Data e IoT II] --> B[Aplicacoes da Ciencia de Dados]
  B --> B1[Onde aplicar]
  B1 --> B1a[Varejo, Saude, Financas, Industria, etc.]
  B --> B2[Exemplos praticos]
  B2 --> B2a[Netflix, Uber, Amazon]
  B --> B3[BI vs Ciencia de Dados]
  B3 --> B3a[BI: analise descritiva]
  B3 --> B3b[Ciencia de Dados: preditiva e prescritiva]

  A --> C[Aprendizado de Maquina]
  C --> C1[Definicao]
  C1 --> C1a[IA que aprende com dados]
  C --> C2[Tipos de aprendizado]
  C2 --> C2a[Supervisionado]
  C2 --> C2b[Nao supervisionado]
  C2 --> C2c[Reforco]
  C --> C3[Aplicacoes]
  C3 --> C3a[Reconhecimento de imagem e voz]
  C3 --> C3b[Fraudes, veiculos autonomos]

  A --> D[Introducao ao Hadoop]
  D --> D1[Definicao]
  D1 --> D1a[Framework distribuido]
  D --> D2[Componentes]
  D2 --> D2a[HDFS]
  D2 --> D2b[MapReduce]
  D2 --> D2c[YARN]
  D2 --> D2d[Hadoop Common]
  D --> D3[Caracteristicas]
  D3 --> D3a[Escalavel, tolerante a falhas, custo baixo]
  D --> D4[MapReduce]
  D4 --> D4a[Map: pares chave-valor]
  D4 --> D4b[Reduce: agregacao de resultados]

  A --> E[Mineracao de Dados]
  E --> E1[Definicao]
  E1 --> E1a[Descoberta de padroes]
  E --> E2[Etapas]
  E2 --> E2a[Selecao, pre-processamento, transformacao]
  E2 --> E2b[Mineracao, avaliacao, apresentacao]
  E --> E3[KDD]
  E3 --> E3a[Integracao, limpeza, reducao, interpretacao]
  E --> E4[Big Data]
  E4 --> E4a[5Vs: Volume, Velocidade, Variedade, Veracidade, Valor]
  E --> E5[Aplicacoes]
  E5 --> E5a[Fraudes, diagnostico medico, redes sociais]
```
## Fundamentos de Big Data e IoT IV
```mermaid
mindmap
  root((Fundamentos de Big Data e IoT IV))

    BI
      Definição
        BI = transformar dados em decisões
      Arquitetura
        Fontes de Dados
        ETL
        Data Warehouse
        Ferramentas de BI
        Dashboards e Relatórios
      Aplicações nas Empresas
        Otimização de processos
        Previsão de tendências
        Redução de custos
        Tomada de decisão

    Dashboards
      Definição
        Painel visual de dados em tempo real
      Benefícios
        Clareza
        Agilidade
        Monitoramento
        Compartilhamento
      Aplicações na Ciência de Dados
        Métricas de modelos
        Dados de sensores
        Indicadores de negócio

    Design Thinking e Inovação
      Definição
        Processo centrado no usuário
      Etapas
        Empatia
        Definição
        Ideação
        Prototipagem
        Teste
      Relação com Inovação
        Soluções criativas
        Iteratividade
      Processo de Negócio
        Desenvolvimento de produtos
        Cultura criativa

    Inteligência Artificial
      Conceito
        Simular a inteligência humana
      Histórico
        1950: conceito inicial
        1980-90: redes neurais
        Atualidade: deep learning, NLP, IA generativa
      Aplicações
        Saúde
        Finanças
        Indústria
        Varejo
        Mobilidade
        IoT
```
## Aplicações de Internet das Coisas
```mermaid
mindmap
  root((Internet das Coisas - IoT))
    Aplicações
      Saúde
      Agricultura
      Indústria 4.0
      Cidades Inteligentes
    Computação em Nuvem
      Características
        Elasticidade
        Sob demanda
        Multitenancy
        Alta disponibilidade
      Datacenter
        Tradicional
          Infraestrutura física
          Alto custo inicial (CAPEX)
          Escalabilidade limitada
        Nuvem
          Virtualização
          Pagamento por uso (OPEX)
          Alta escalabilidade
      SLA, Custos e Segurança
        SLA define uptime e suporte
        Custos baseados em uso
        Segurança com criptografia e controle de acesso
    Aplicações Web e WoT
      Diferença
        IoT: conexão de objetos
        WoT: uso de protocolos Web
      REST e ROA
        REST
          HTTP
          Stateless
          Verbos: GET, POST, PUT, DELETE
        ROA
          Foco em recursos
          URL como identificador
      Controle de Acesso
        CBAC
          Baseado em contexto (ex: local, horário)
        ABAC
          Baseado em atributos (ex: cargo, projeto)
    Web Services
      REST
        Leve
        Usa JSON/XML
        APIs modernas
      SOAP
        Robusto
        Usa XML
        Ambientes legados
      Exemplos
        REST: Twitter, GitHub, IoT APIs
        SOAP: Bancos, sistemas governamentais
    Plataformas Comerciais
      Amazon AWS
        EC2, S3, Lambda, IoT Core
      Microsoft Azure
        VM, Blob Storage, IoT Hub
      Google Cloud
        Compute Engine, Cloud Storage, Firebase
      IBM Cloud
        Watson, Node-RED, IoT Platform
```
## Arquitetura de referência IoT-A (Internet of Things - Architecture)
```mermaid
graph TD
    A[Camada de Aplicação] --> B[Camada de Serviço]
    B --> C[Camada de Rede]
    C --> D[Camada de Percepção]

    subgraph Níveis da IoT-A
        A
        B
        C
        D
    end

    A:::app
    B:::service
    C:::network
    D:::perception

    classDef app fill:#c9f0ff,stroke:#333,stroke-width:2px
    classDef service fill:#c2f5c0,stroke:#333,stroke-width:2px
    classDef network fill:#ffe4b3,stroke:#333,stroke-width:2px
    classDef perception fill:#ffb3b3,stroke:#333,stroke-width:2px
```
- Camada de Percepção: sensores, RFID, atuadores — coleta dados do mundo físico.
- Camada de Rede: protocolos de comunicação e transporte dos dados coletados.
- Camada de Serviço: processamento, gerenciamento e armazenamento de dados.
- Camada de Aplicação: entrega os serviços ao usuário final (painéis, apps, relatórios).
## Arquitetura e Infraestrutura de IoT II
```mermaid
mindmap
  root((IoT - Arquitetura e Infraestrutura II))

    Protocolos de Comunicação
      Conceito
        - Regras para troca de dados
        - Eficiência e interoperabilidade
      Importância
        - Comunicação eficiente
        - Baixo consumo
        - Conectividade escalável
      Comparação
        MQTT
          - Leve
          - Assíncrono
          - Broker
        CoAP
          - Baseado em REST
          - Leve e multicast
        HTTP
          - Comum na web
          - Pesado para IoT
        LoRaWAN
          - Longo alcance
          - Baixo consumo
        AMQP
          - Alta confiabilidade
          - Complexo

    Protocolo MQTT
      Objetivos
        - Eficiência em redes instáveis
        - Comunicação leve
      Características
        - Publish/Subscribe
        - Baseado em TCP/IP
        - QoS 0, 1, 2
        - Necessita de Broker
      Estrutura
        - Cliente
        - Broker
        - Tópico
        - Mensagem

    Middleware
      Definição
        - Software intermediário
        - Conecta dispositivos e apps
      Serviços
        - Gerenciamento de dispositivos
        - Agregação de dados
        - Segurança
        - Gerenciamento de rede
      Vantagens
        - Escalabilidade
        - Integração facilitada
        - Interoperabilidade

    Objetos Inteligentes
      Definição
        - Dispositivos com sensores, atuadores e conectividade
      Exemplos
        - Sensores
        - Wearables
        - Câmeras
        - Carros conectados
      Aplicações
        - Saúde
        - Indústria
        - Agricultura
        - Cidades inteligentes
        - Varejo
```
