# Coleção de Normas ISO/IEC/IEEE: Faixa 25001-30000

## Introdução

Este repositório contém uma coleção abrangente de normas técnicas internacionais na faixa numérica 25001-30000, organizadas em estrutura hierárquica por tipo de organização e categoria de documento. A coleção foca principalmente em **engenharia de software**, **qualidade de sistemas**, **segurança da informação** e **tecnologias emergentes**.

### Importância das Normas Técnicas

As normas ISO/IEC/IEEE representam o consenso internacional sobre melhores práticas em tecnologia da informação. **A série ISO/IEC 25000 (SQuaRE)** - Sistema de Requisitos e Avaliação da Qualidade de Software e Sistemas - é particularmente crucial para equipes de desenvolvimento, oferecendo metodologias padronizadas para avaliação da qualidade de software. A **série ISO/IEC 27000** estabelece frameworks completos para gestão de segurança da informação, enquanto outras séries abordam domínios especializados como saúde, transporte e sustentabilidade.

## Tabela Geral de Normas por Série Principal

| Série | Família | Quantidade Estimada | Foco Principal | Status |
|-------|---------|-------------------|----------------|---------|
| **25000-25099** | SQuaRE (Systems and Software Quality) | ~45 padrões | Qualidade de software e sistemas | ✅ Ativa |
| **25100-25499** | Tecnologias Específicas | ~15 padrões | Transporte inteligente, geometria | ✅ Ativa |
| **25500-25999** | Domínios Especializados | ~10 padrões | Saúde, biometria, segurança | ✅ Ativa |
| **26000-26999** | Responsabilidade Social e Identidade | ~25 padrões | Sustentabilidade, documentos digitais | ✅ Ativa |
| **27000-27999** | Gestão de Segurança da Informação | ~85 padrões | Cybersegurança, gestão de riscos | ✅ Ativa |
| **28000-28999** | Segurança da Cadeia de Suprimentos | ~15 padrões | Logística, segurança marítima | ✅ Ativa |
| **29000-29999** | Privacidade e Biometria | ~8 padrões | Proteção de dados, identificação | ✅ Ativa |
| **30000-30999** | Tecnologia Marítima e Reciclagem | ~12 padrões | Sustentabilidade naval, terminologia | ✅ Ativa |

### 🎨 **Para UX/UI e Experiência do Usuário**

#### **Normas Específicas para UX/UI**
A coleção contém normas essenciais para profissionais de UX/UI, com foco na avaliação científica da experiência do usuário:

- **ISO/IEC 25022:2016** - Métricas de qualidade em uso, incluindo efetividade, eficiência e satisfação do usuário
- **ISO/IEC 25040:2011** - Processo de avaliação de qualidade de produto, aplicável a interfaces digitais
- **ISO/IEC 25060:2010** - Formato comum da indústria para relatórios de usabilidade
- **ISO/IEC 25062:2006** - Modelo de referência para medição de usabilidade
- **ISO/IEC 25063:2014** - Framework para testes de usabilidade em contexto de uso

### 📋 **Para Product Owners e Coleta de Requisitos**

#### **Engenharia de Requisitos com ISO/IEC 29148:2018**
Esta é a norma fundamental para POs, oferecendo metodologia completa para:

- **Elicitação de Requisitos**: Técnicas sistemáticas para identificar necessidades dos stakeholders
- **Análise de Requisitos**: Métodos para validar consistência e completude
- **Especificação de Requisitos**: Formatos padronizados para documentação
- **Validação de Requisitos**: Critérios para verificar se requisitos atendem às necessidades

#### **Template para User Stories com Rastreabilidade ISO**
```markdown
## User Story Template (ISO/IEC 29148 compliant)

### Identificação e Rastreabilidade
- **ID**: US-001
- **Épico**: [Nome do épico]
- **Stakeholder**: [Tipo de usuário identificado na elicitação]

### Requisito Funcional
- **Como** [persona baseada em pesquisa ISO/IEC 25022]
- **Eu quero** [funcionalidade validada por ISO/IEC 29148]
- **Para que** [valor de negócio com critério de sucesso]

### Critérios de Aceitação (ISO/IEC 29119)
- [ ] Critério funcional 1 com métricas mensuráveis
- [ ] Critério de performance baseado em ISO/IEC 25023
- [ ] Critério de usabilidade seguindo ISO/IEC 25062
- [ ] Critério de acessibilidade conforme ISO/IEC 40500

### KPIs e Métricas de Qualidade
- **Efetividade**: Taxa de conclusão da tarefa > 95%
- **Eficiência**: Tempo médio de conclusão < [X] segundos
- **Satisfação**: Net Promoter Score > 8/10
- **Qualidade**: Zero defeitos críticos em produção
```

### 🏃‍♂️ **Para Scrum Masters e Metodologias Ágeis**

#### **ISO/IEC 29110 - O Padrão ISO Específico para Metodologias Ágeis**
Esta série é única por ser desenhada especificamente para **equipes pequenas (até 25 pessoas)** e **metodologias ágeis**:

- **ISO/IEC 29110-1:2016** - Visão geral e conceitos para organizações pequenas
- **ISO/IEC 29110-2-1:2015** - Framework de processos adaptado para Scrum
- **ISO/IEC 29110-4-1:2018** - Especificação de processos para times ágeis
- **ISO/IEC 29110-5-1-1:2012** - Guias de implementação prática

### 🤖 **Para Equipes de Desenvolvimento de IA**

#### **Frameworks de Qualidade para IA**
- **ISO/IEC 25059:2023** - Modelo específico para sistemas de IA incluindo características únicas:
  - **Adaptabilidade funcional**: Capacidade de aprendizado e evolução
  - **Explicabilidade**: Interpretabilidade das decisões algorítmicas  
  - **Imparcialidade**: Prevenção de viés e discriminação
  - **Robustez**: Performance sob condições incertas

# 📚 1. **Série ISO/IEC 25000 (SQuaRE)**

> *Software product Quality Requirements and Evaluation*

A série **ISO/IEC 25000** é o padrão internacional para **definir, medir e avaliar a qualidade de produtos de software e sistemas**.

## 📘 Subséries principais:

| Norma ISO/IEC   | Título (PT)                                           | Objetivo principal                                     |
| --------------- | ----------------------------------------------------- | ------------------------------------------------------ |
| **25000**       | Guia geral (SQuaRE)                                   | Visão geral da família de normas                       |
| **25001**       | Guia de referência da arquitetura SQuaRE              | Estrutura dos modelos e relações entre eles            |
| **25002**       | Guia para uso de modelos de qualidade                 | Explica como usar os modelos em requisitos e avaliação |
| **25010**       | Modelo de qualidade do produto                        | Define 9 características principais de qualidade       |
| **25011**       | Modelo de qualidade para TI corporativa               | Qualidade em serviços de TI empresariais               |
| **25012**       | Modelo de qualidade de dados                          | Propriedades para dados e bancos de dados              |
| **25014**       | Modelo de qualidade de serviços de TI                 | Similar ao 25010, mas focado em serviços               |
| **25019**       | Modelo de qualidade em uso                            | Avaliação da experiência do usuário final              |
| **25020**       | Guia de aplicação dos modelos                         | Diretrizes para uso integrado de 25010/19/24           |
| **25021**       | Repositório de medidas de qualidade                   | Catálogo de métricas utilizáveis                       |
| **25022**       | Medidas de qualidade em uso                           | Métricas para as características da 25019              |
| **25023**       | Medidas da qualidade do produto                       | Métricas para as características da 25010              |
| **25024**       | Medidas da qualidade de dados                         | Métricas para a 25012                                  |
| **25030**       | Requisitos de qualidade do produto de software        | **Coleta e documentação de requisitos de qualidade**   |
| **25040**       | Processo de avaliação da qualidade                    | Como executar uma avaliação de qualidade               |
| **25041**       | Guia para avaliação da qualidade                      | Complementa a 25040 com exemplos e métodos             |
| **25042**       | Requisitos para ferramentas de avaliação da qualidade | Define critérios para ferramentas automatizadas        |
| **25045**       | Avaliação de modelos de qualidade                     | Aplicação prática de modelos 25010, 25019, etc.        |
| **25050–25099** | Reservadas para domínios específicos                  | Ex: qualidade em IA, IoT, aplicações móveis, etc.      |

---

# 📚 2. **Normas complementares para coleta de requisitos, testes e qualidade**

## 📘 Engenharia de requisitos

| Norma ISO/IEC | Título (PT)                                               | Descrição breve                                                                             |
| ------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **29148**     | Engenharia de requisitos                                  | Norma **central** para elicitação, análise, especificação, validação e gestão de requisitos |
| **12207**     | Processos de ciclo de vida de software                    | Contém seção sobre engenharia de requisitos                                                 |
| **26514**     | Documentação de software – Manual do usuário              | Requisitos de documentação funcional e técnica                                              |
| **15288**     | Processos de ciclo de vida de sistemas (eng. de sistemas) | Complementa a 12207 com foco em sistemas                                                    |

---

## 📘 Testes de software

| Norma ISO/IEC          | Título (PT)                                        | Descrição breve                                 |
| ---------------------- | -------------------------------------------------- | ----------------------------------------------- |
| **29119-1**            | Conceitos e definições de testes                   | Terminologia padronizada para testes            |
| **29119-2**            | Processo de teste                                  | Define o processo completo de testes            |
| **29119-3**            | Documentação de teste                              | Tipos de documentos (plano de teste, relatório) |
| **29119-4**            | Técnicas de teste                                  | Técnicas formais e informais                    |
| **29119-5**            | Teste baseado em riscos                            | Aplicação de testes com foco em riscos críticos |
| **ISO/IEC/IEEE 12207** | Inclui testes no processo de verificação/validação | Amplo, cobre testes dentro do ciclo de vida     |

---

## 📘 Qualidade de software

Além da série ISO/IEC 25000:

| Norma ISO/IEC     | Título (PT)                                         | Descrição breve                                              |
| ----------------- | --------------------------------------------------- | ------------------------------------------------------------ |
| **9126**          | Modelo anterior à 25010 (obsoleto, mas ainda usado) | Introduziu o modelo com características e subcaracterísticas |
| **14598**         | Avaliação da qualidade de produto de software       | Antecessora da série 25040–25045                             |
| **15504 / 330xx** | SPICE – Avaliação de processos                      | Mede **maturidade dos processos** de qualidade               |
| **ISO/IEC 38500** | Governança de TI                                    | Diretrizes para gestão de qualidade em TI                    |

---

# 📘 3. Qualidade e testes em **Scrum e métodos ágeis**

## 📘 Não há normas ISO específicas para "Scrum", pois Scrum é definido pelo **Scrum Guide** (Ken Schwaber e Jeff Sutherland).

Mas existem normas e frameworks **compatíveis com métodos ágeis**, que tratam de qualidade e testes no contexto de Scrum.

| Documento ou padrão            | Foco                                                               |
| ------------------------------ | ------------------------------------------------------------------ |
| **Scrum Guide (2020)**         | Define papéis, artefatos e eventos do Scrum                        |
| **ISO/IEC/IEEE 29119 + Scrum** | Aplicável no Scrum para estruturar testes formais ou automatizados |
| **ISTQB Agile Extension**      | Técnicas de teste adaptadas ao contexto Scrum e DevOps             |
| **SAFe**                       | Framework ágil escalado que inclui qualidade contínua              |
| **Disciplined Agile (DA PMI)** | Incorpora qualidade e engenharia ágil estruturada                  |
| **ISO 25010 + Scrum**          | Usado para definir *critérios de aceitação* com base em qualidade  |
| **CMMI-DEV v2.0 Ágil**         | Avaliação da maturidade de processos em ambientes ágeis            |

---

# 🧭 Resumo visual — Categorias e normas principais

| Área                       | Normas/Guias recomendados                                                                |
| -------------------------- | ---------------------------------------------------------------------------------------- |
| ✅ Qualidade de produto     | ISO/IEC 25010, 25023, 25040, 25042                                                       |
| ✅ Qualidade percebida      | ISO/IEC 25019, 25022                                                                     |
| ✅ Qualidade de dados       | ISO/IEC 25024                                                                            |
| ✅ Medição e avaliação      | ISO/IEC 25020, 25030, 25045, 25021                                                       |
| ✅ Requisitos               | ISO/IEC/IEEE 29148, ISO/IEC 12207, ISO/IEC 15288                                         |
| ✅ Testes de software       | ISO/IEC/IEEE 29119 (partes 1 a 5), ISO/IEC 12207                                         |
| ✅ Scrum + qualidade/testes | Scrum Guide + ISO/IEC 25010 + ISO 29119 + ISTQB Agile + SAFe + CMMI Agile                |
| ✅ Processos de engenharia  | ISO/IEC/IEEE 12207 (software), ISO/IEC/IEEE 15288 (sistemas), ISO/IEC 33001+ (SPICE)     |
| ✅ Governança e compliance  | ISO/IEC 38500 (TI), ISO 27001 (segurança), ISO 9001 (qualidade geral), LGPD/GDPR (dados) |

---

## Organização por Pasta

### 1. **25001-30000.IEC IEEE** (Padrões Tri-Organizacionais)
**Conteúdo**: Normas desenvolvidas em colaboração entre ISO, IEC e IEEE  
**Quantidade**: ~10-15 padrões  
**Foco**: Engenharia de sistemas, processos de ciclo de vida

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC/IEEE 24748-1 | Orientações de gestão do ciclo de vida | 2018 | Standard | Framework para gestão de ciclo de vida de sistemas complexos |
| ISO/IEC/IEEE 24748-2 | Processos do ciclo de vida de sistemas | 2018 | Standard | Processos específicos para engenharia de sistemas |
| ISO/IEC/IEEE 24748-4 | Planejamento de engenharia de sistemas | 2016 | Standard | Metodologias de planejamento para projetos de engenharia |
| ISO/IEC/IEEE 24748-5 | Planejamento de desenvolvimento de software | 2017 | Standard | Estratégias de planejamento para desenvolvimento ágil e tradicional |
| ISO/IEC/IEEE 24765 | Vocabulário de engenharia de sistemas e software | 2017 | Standard | Terminologia unificada para domínios técnicos |

### 2. **25001-30000** (Padrões ISO Puros)
**Conteúdo**: Normas desenvolvidas exclusivamente pela ISO  
**Quantidade**: ~20-30 padrões  
**Foco**: Transporte, saúde, manufatura, sustentabilidade

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO 25112 | Sistemas de transporte inteligente - Localização de incidentes | 2010 | Standard | Protocolos para reportar incidentes de trânsito |
| ISO 25178-2 | Especificações geométricas de produtos - Textura superficial | 2012 | Standard | Métodos de medição de rugosidade e textura |
| ISO 26000 | Orientações sobre responsabilidade social | 2010 | Standard | Framework global para sustentabilidade organizacional |
| ISO 26262-1 | Veículos rodoviários - Segurança funcional | 2018 | Standard | Padrão de segurança para sistemas automotivos críticos |
| ISO 28000 | Sistemas de gestão de segurança para cadeia de suprimentos | 2022 | Standard | Gerenciamento de riscos em logística e transporte |

### 3. **25001-30000.IEC** (Padrões ISO/IEC Conjuntos)
**Conteúdo**: Normas desenvolvidas conjuntamente por ISO e IEC  
**Quantidade**: ~180-220 padrões  
**Foco**: Tecnologia da informação, qualidade de software, cibersegurança

#### **Série SQuaRE (25000-25099) - Qualidade de Software e Sistemas**
| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC 25000 | SQuaRE - Guia do framework | 2014 | Standard | Arquitetura geral do sistema de qualidade |
| ISO/IEC 25001 | SQuaRE - Planejamento e gestão | 2014 | Standard | Processos de planejamento para avaliação de qualidade |
| ISO/IEC 25010 | Modelos de qualidade de sistema e software | 2023 | Standard | **8 características de qualidade**: funcionalidade, performance, compatibilidade, usabilidade, confiabilidade, segurança, manutenibilidade, portabilidade |
| ISO/IEC 25012 | Modelo de qualidade de dados | 2008 | Standard | **15 características** para qualidade de dados corporativos |
| ISO/IEC 25020 | Modelo de referência de medição | 2019 | Standard | Framework matemático para métricas de qualidade |
| ISO/IEC 25040 | Processo de avaliação | 2011 | Standard | Metodologia sistemática para avaliação de produtos |
| ISO/IEC 25051 | Requisitos para software RUSP | 2014 | Standard | Qualidade para produtos de software comerciais |
| ISO/IEC 25059 | Modelo de qualidade para sistemas de IA | 2023 | Standard | **Extensão específica para IA**: adaptabilidade, explicabilidade, imparcialidade, robustez |

#### **Série Testes de Software (29119) - Framework Completo para Testing**
| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC 29119-1 | Conceitos e definições de teste | 2022 | Standard | Vocabulário e princípios fundamentais de teste |
| ISO/IEC 29119-2 | Processos de teste | 2021 | Standard | **Processos de teste organizacional, gerencial e dinâmico** |
| ISO/IEC 29119-3 | Documentação de teste | 2021 | Standard | Templates para planos, casos e relatórios de teste |
| ISO/IEC 29119-4 | Técnicas de teste | 2021 | Standard | **Técnicas black-box, white-box e baseadas na experiência** |
| ISO/IEC 29119-5 | Teste orientado por palavras-chave | 2016 | Standard | Automação de testes com abordagem keyword-driven |

#### **Série Engenharia de Requisitos e Processos Ágeis**
| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC 29148 | Engenharia de requisitos de sistemas e software | 2018 | Standard | **Framework completo para elicitação, análise, especificação e validação de requisitos** |
| ISO/IEC 29110-1 | Processos de ciclo de vida para VSEs - Visão geral | 2016 | Standard | **Processos ágeis para organizações pequenas (até 25 pessoas)** |
| ISO/IEC 29110-2-1 | Processos de ciclo de vida para VSEs - Framework | 2015 | Standard | **Gestão de projetos e desenvolvimento para equipes Scrum** |
| ISO/IEC 29110-4-1 | Processos de ciclo de vida para VSEs - Especificação | 2018 | Standard | **Processos de desenvolvimento compatíveis com metodologias ágeis** |
| ISO/IEC 29110-5-1-2 | Guias de implementação para VSEs | 2011 | Standard | **Orientações práticas para implementação em times ágeis** |

#### **Série Segurança da Informação (27000-27099) - Framework Completo para Segurança da Informação**
| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC 27000 | SGSI - Visão geral e vocabulário | 2018 | Standard | Fundamentos dos sistemas de gestão de segurança |
| ISO/IEC 27001 | SGSI - Requisitos | 2022 | Standard | **Padrão certificável** para segurança da informação |
| ISO/IEC 27002 | Controles de segurança da informação | 2022 | Standard | **93 controles organizados em 4 temas**: organizacional, pessoas, físico, tecnológico |
| ISO/IEC 27005 | Gestão de riscos de segurança da informação | 2018 | Standard | Metodologia para análise e tratamento de riscos |
| ISO/IEC 27017 | Código de prática para serviços em nuvem | 2015 | Standard | Controles específicos para computação em nuvem |
| ISO/IEC 27701 | Gestão de informações de privacidade | 2019 | Standard | Extensão da 27001 para compliance com GDPR/LGPD |

### 4. **25001-30000.IEC TS** (Especificações Técnicas IEC)
**Conteúdo**: Especificações técnicas normativas em desenvolvimento  
**Quantidade**: ~8-12 padrões  
**Foco**: Tecnologias emergentes, standards em evolução

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC TS 25011 | SQuaRE - Modelos de qualidade de serviços | 2017 | TS | Qualidade específica para arquiteturas de serviços e APIs |
| ISO/IEC TS 27110 | Framework de desenvolvimento de cibersegurança | 2021 | TS | Orientações para criação de frameworks customizados |
| ISO/IEC TS 30104 | Ataques de segurança física e técnicas de mitigação | 2015 | TS | Proteção contra ataques físicos a hardware |

### 5. **25001-30000.TR** (Relatórios Técnicos)
**Conteúdo**: Documentos informativos com dados de pesquisa e orientações  
**Quantidade**: ~25-35 padrões  
**Foco**: Estado da arte, metodologias, dados de survey

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC TR 25060 | Formato comum da indústria para usabilidade | 2010 | TR | Framework para relatórios de teste de usabilidade |
| ISO/IEC TR 24766 | Capacidades de ferramentas de engenharia de requisitos | 2009 | TR | Análise comparativa de ferramentas CASE |
| ISO/IEC TR 27008 | Diretrizes para auditores de controles de segurança | 2011 | TR | Metodologias de auditoria para ISO 27001 |
| ISO/TR 25257 | Informática em saúde - Requisitos de negócio | 2009 | TR | Análise de necessidades do setor de saúde |

### 6. **25001-30000.TS** (Especificações Técnicas Gerais)
**Conteúdo**: Especificações técnicas de todas as organizações  
**Quantidade**: ~15-20 padrões  
**Foco**: Necessidades urgentes de mercado

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/TS 25114 | Gestão de relatório de dados de sonda | 2010 | TS | Protocolos para sistemas de telemetria veicular |
| ISO/TS 25237 | Informática em saúde - Pseudonimização | 2008 | TS | Técnicas de anonimização para dados médicos |
| ISO/TS 25110 | Interface de cobrança eletrônica | 2017 | TS | Sistemas de pagamento para pedágios automatizados |

### 7. **25001-30000.IEC TR** (Relatórios Técnicos IEC)
**Conteúdo**: Relatórios técnicos específicos da IEC  
**Quantidade**: ~10-15 padrões  
**Foco**: Tecnologias eletrônicas e de TI

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC TR 24772 | Vulnerabilidades de linguagens de programação | 2013 | TR | Análise de segurança em C, C++, Java, Ada |
| ISO/IEC TR 24731 | Extensões da biblioteca C | 2007 | TR | Funções seguras para programação em C |
| ISO/IEC TR 30102 | Plataformas de aplicações distribuídas | 2012 | TR | Arquiteturas para sistemas distribuídos |

### 8. **25001-30000.HL7** (Padrões de Informática em Saúde)
**Conteúdo**: Normas relacionadas à interoperabilidade em saúde  
**Quantidade**: ~5-8 padrões  
**Foco**: Troca de informações médicas, terminologias

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO 25237 | Informática em saúde - Pseudonimização | 2017 | Standard | Proteção de privacidade em sistemas de saúde |
| ISO 25720 | Linguagem de marcação para variação de sequência genômica | 2009 | Standard | Padrões para dados de genômica |
| ISO/TR 25257 | Sistemas de codificação de produtos medicinais | 2009 | TR | Terminologias farmacêuticas padronizadas |

### 9. **25001-30000.CIE** (Padrões de Iluminação e Cor)
**Conteúdo**: Normas relacionadas à iluminação, cor e tecnologia de displays  
**Quantidade**: ~3-5 padrões  
**Foco**: Colorimetria, medição de luz

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/CIE 11664-4 | Colorimetria - Espaço de cor CIE 1976 L*a*b* | 2019 | Standard | Espaço de cores para medição colorimétrica |
| ISO/CIE 11664-6 | Colorimetria - Fórmula de diferença de cor CIEDE2000 | 2014 | Standard | Algoritmo para cálculo de diferenças de cor |

### 10. **25001-30000.PAS** (Especificações Publicamente Disponíveis)
**Conteúdo**: Especificações para necessidades urgentes do mercado  
**Quantidade**: ~8-12 padrões  
**Foco**: Soluções rápidas, acordos de workshop

| Código | Título | Ano | Tipo | Descrição |
|--------|--------|-----|------|-----------|
| ISO/IEC PAS 28005 | Desembaraço eletrônico portuário | 2012 | PAS | Sistemas de liberação automatizada de cargas |
| ISO/PAS 28007 | Diretrizes para empresas de segurança marítima privada | 2012 | PAS | Padrões para proteção anti-pirataria |

## Organização por Tema

### 🏗️ **Qualidade e Engenharia de Software**
- **Pasta Principal**: `25001-30000.IEC`
- **Série SQuaRE (25000-25099)**: Framework completo para qualidade de software
- **Aplicações**: Desenvolvimento ágil, DevOps, testes automatizados
- **Standards Essenciais**: ISO/IEC 25010 (modelos de qualidade), ISO/IEC 25040 (avaliação)

### 🔒 **Segurança e Privacidade**
- **Pasta Principal**: `25001-30000.IEC`
- **Série 27000**: Gestão de segurança da informação
- **Aplicações**: Compliance GDPR/LGPD, auditorias de segurança, gestão de riscos
- **Standards Essenciais**: ISO/IEC 27001 (certificação), ISO/IEC 27701 (privacidade)

### 🧪 **Testes e Avaliação**
- **Pastas**: `25001-30000.IEC`, `25001-30000.TR`
- **Série 29119**: Framework completo para testes de software e sistemas
- **Standards Essenciais**: ISO/IEC 29119 (séries de teste), ISO/IEC 25040 (processo de avaliação), ISO/IEC 25021 (elementos de medição)

### 📋 **Gerenciamento de Projetos e Metodologias Ágeis**
- **Pastas**: `25001-30000.IEC`, `25001-30000.TR`
- **Série 29110**: Processos de ciclo de vida para entidades muito pequenas (VSEs) - **Compatível com Scrum/Agile**
- **Standards Essenciais**: ISO/IEC 29110 (desenvolvimento ágil para pequenas equipes), ISO/IEC 25010 (qualidade em metodologias ágeis)

### 📝 **Engenharia de Requisitos**
- **Pastas**: `25001-30000.IEC`, `25001-30000.TR`
- **Standard Chave**: ISO/IEC 29148 (engenharia de requisitos)
- **Aplicações**: Coleta, análise, especificação e validação de requisitos

### 🌐 **Inteligência Artificial e Sistemas Emergentes**
- **Pasta Principal**: `25001-30000.IEC`
- **Standard Chave**: ISO/IEC 25059 (qualidade para sistemas de IA)
- **Aplicações**: MLOps, governança de IA, explicabilidade de algoritmos

### 🏥 **Informática em Saúde**
- **Pasta Principal**: `25001-30000.HL7`
- **Foco**: Interoperabilidade, privacidade médica, terminologias
- **Aplicações**: Sistemas hospitalares, telemedicina, dados genômicos

### 🚢 **Sustentabilidade e Responsabilidade Social**
- **Pastas**: `25001-30000`, `25001-30000.IEC`
- **Série 26000**: Responsabilidade social organizacional
- **Série 30000**: Reciclagem naval e sustentabilidade marítima

## Sugestões de Uso com IA e Automação

### 🤖 **Para Equipes de Desenvolvimento de IA**

#### **Frameworks de Qualidade para IA**
- **ISO/IEC 25059:2023** - Modelo específico para sistemas de IA incluindo características únicas:
  - **Adaptabilidade funcional**: Capacidade de aprendizado e evolução
  - **Explicabilidade**: Interpretabilidade das decisões algorítmicas  
  - **Imparcialidade**: Prevenção de viés e discriminação
  - **Robustez**: Performance sob condições incertas

#### **Implementação em MLOps e Metodologias Ágeis**
```yaml
# Exemplo de pipeline CI/CD com padrões ISO/IEC
quality_gates:
  - functional_suitability: ISO/IEC 25010 checklist
  - performance_efficiency: Métricas ISO/IEC 25023
  - security: Controles ISO/IEC 27002
  - ai_specific: Verificações ISO/IEC 25059
  - testing: ISO/IEC 29119 test processes
  - requirements: ISO/IEC 29148 validation
  - agile_lifecycle: ISO/IEC 29110 for small teams

# Exemplo de pipeline CI/CD com padrões ISO/IEC
quality_gates:
  - functional_suitability: ISO/IEC 25010 checklist
  - performance_efficiency: Métricas ISO/IEC 25023
  - security: Controles ISO/IEC 27002
  - ai_specific: Verificações ISO/IEC 25059
  - testing: ISO/IEC 29119 test processes
  - requirements: ISO/IEC 29148 validation
  - agile_lifecycle: ISO/IEC 29110 for small teams
```

#### **Governança e Compliance**
- **ISO/IEC 25001** para planejamento de qualidade em projetos de IA
- **ISO/IEC 27001** para segurança de dados de treinamento
- **ISO/IEC 27701** para compliance com proteção de dados

### 🔧 **Para Automação de Testes e Metodologias Ágeis**

#### **Framework de Testes Automatizados ISO/IEC 29119**
- **ISO/IEC 29119-2**: Processos de teste organizacional para integração em pipelines CI/CD
- **ISO/IEC 29119-4**: Técnicas de teste para automação (black-box, white-box, baseadas em experiência)
- **ISO/IEC 29119-5**: Teste orientado por palavras-chave para frameworks como Selenium e Cypress

#### **Integração com Metodologias Ágeis (Scrum/Kanban)**
- **ISO/IEC 29110**: Processos de ciclo de vida específicos para equipes pequenas (VSEs - Very Small Entities)
- **Aplicação em Scrum**: Processos adaptados para sprints de 1-4 semanas
- **Gestão de requisitos ágil**: ISO/IEC 29148 para user stories e critérios de aceitação

#### **Métricas Automatizadas**
- **ISO/IEC 25022**: Medição automatizada de qualidade em uso
- **ISO/IEC 25023**: Métricas de produto implementáveis em pipelines
- **ISO/IEC 25024**: Qualidade de dados para datasets de treinamento

#### **Ferramentas de Avaliação Ágil**
- **ISO/IEC 25040**: Processo de avaliação de produtos
- **ISO/IEC 25051**: Requisitos para software RUSP

#### **Template para User Stories com ISO/IEC 29148**
```markdown
## User Story Template (ISO/IEC 29148 compliant)

### Functional Requirements
- **As a** [type of user]
- **I want** [functionality]
- **So that** [business value]

### Non-Functional Requirements (ISO/IEC 25010)
- **Performance**: Response time < 2s
- **Usability**: Accessibility Level AA
- **Security**: Authentication required
- **Reliability**: 99.9% uptime

### Acceptance Criteria (ISO/IEC 29119)
- [ ] Functional test cases pass
- [ ] Performance benchmarks met
- [ ] Security controls verified
- [ ] Usability tested with target users

### Test Strategy (ISO/IEC 29119-4)
- **Unit Tests**: White-box testing
- **Integration Tests**: Black-box testing
- **User Acceptance Tests**: Experience-based testing
```

### 📊 **Para Business Intelligence, Analytics e Gestão de Projetos Ágeis**

#### **Qualidade de Dados Corporativos**
- **ISO/IEC 25012** - Framework para 15 características de qualidade de dados
- Implementação em pipelines ETL com validações automáticas
- Dashboards de monitoramento baseados em métricas padronizadas

#### **Gestão de Projetos Ágeis com Métricas ISO**
- **ISO/IEC 25022**: Medição automatizada de qualidade em uso
- **ISO/IEC 25023**: Métricas de produto implementáveis em pipelines
- **ISO/IEC 25024**: Qualidade de dados para datasets de treinamento

#### **KPIs para Scrum Masters baseados em ISO**
- **Velocidade da Equipe**: Métricas ISO/IEC 29110 para VSEs
- **Qualidade do Produto**: Características ISO/IEC 25010
- **Eficácia dos Testes**: Cobertura ISO/IEC 29119
- **Gestão de Requisitos**: Rastreabilidade ISO/IEC 29148

#### **Gestão de Riscos Automatizada**
- **ISO/IEC 27005** para análise de riscos de IA
- **ISO 28000** para riscos de cadeia de suprimentos
- Integração com ferramentas de GRC (Governance, Risk, Compliance)

## Licença e Informações do Projeto

### 📜 **Direitos Autorais e Uso**

As normas técnicas são propriedade intelectual das organizações que as desenvolvem:
- **ISO Standards**: Copyright © International Organization for Standardization
- **IEC Standards**: Copyright © International Electrotechnical Commission  
- **IEEE Standards**: Copyright © Institute of Electrical and Electronics Engineers

### 🔓 **Política de Acesso**

Este repositório fornece **estrutura organizacional e metadados** apenas. Para acesso aos documentos completos:

- **Aquisição Oficial**: [ISO Store](https://www.iso.org/store.html), [IEC Webstore](https://webstore.iec.ch/), [IEEE Xplore](https://ieeexplore.ieee.org/)
- **Bibliotecas Institucionais**: Muitas universidades e empresas mantêm assinaturas
- **Versões Gratuitas**: Algumas normas têm versões públicas disponíveis

### 🎯 **Finalidade do Repositório**

- **Catalogação**: Organização sistemática por tipo e tema
- **Navegação**: Facilitar descoberta de normas relevantes
- **Educação**: Promover conhecimento sobre melhores práticas
- **Pesquisa**: Apoiar análise acadêmica e industrial

### ⚖️ **Uso Responsável**

- Respeitar direitos autorais das organizações de padronização
- Utilizar apenas para fins educacionais e de pesquisa quando aplicável
- Adquirir licenças apropriadas para uso comercial
- Citar fontes adequadamente em trabalhos acadêmicos

### 🤝 **Contribuições**

Contribuições são bem-vindas para:
- **Metadados**: Melhorar descrições e categorizações
- **Organização**: Sugerir estruturas mais eficientes
- **Atualizações**: Reportar novos padrões ou revisões
- **Correções**: Identificar inconsistências na catalogação

---

## 🏷️ **Rodapé**

### **Créditos e Reconhecimentos**

- **Pesquisa e Curadoria**: Equipe de Engenharia de Software
- **Organização Temática**: Baseada em frameworks oficiais das organizações de padronização
- **Estrutura de Navegação**: Desenvolvida com base em melhores práticas de documentação técnica

### **Atualizações e Manutenção**

- **Última Atualização**: Julho 2025
- **Próxima Revisão**: Dezembro 2025
- **Frequência**: Trimestral para novos padrões, anual para revisões estruturais

### **Contato e Suporte**

- **Issues Técnicos**: Abrir issue no repositório GitHub
- **Sugestões de Melhorias**: Pull requests são bem-vindos
- **Dúvidas sobre Padrões**: Consultar documentação oficial das organizações

### **Tecnologias Utilizadas**

- **Catalogação**: Markdown estruturado com metadados YAML
- **Controle de Versão**: Git com versionamento semântico
- **Automação**: Scripts Python para validação de integridade
- **Pesquisa**: Indexação full-text para busca eficiente

---

*"A excelência em engenharia de software não é um acidente. É resultado da aplicação sistemática de melhores práticas comprovadas e padrões internacionais reconhecidos."*

**📚 Total de Normas Catalogadas**: ~300-400 padrões incluindo frameworks completos para **Scrum/Agile (ISO/IEC 29110)**, **Testes de Software (ISO/IEC 29119)** e **Engenharia de Requisitos (ISO/IEC 29148)**  
**🔄 Status do Repositório**: Ativo e mantido  
**📅 Período de Cobertura**: 2005-2025 (com atualizações contínuas)

### 🎯 **Destaques para Equipes Ágeis**

- **ISO/IEC 29110**: O único padrão ISO específico para equipes pequenas e metodologias ágeis
- **ISO/IEC 29119**: Framework completo de testes compatível com TDD/BDD
- **ISO/IEC 29148**: Padrão para engenharia de requisitos aplicável a user stories
- **ISO/IEC 25010**: Modelo de qualidade essencial para Definition of Done