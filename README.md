# Bem-vindo à Efficientia

> Inovação, segurança e bem-estar animal no transporte rodoviário.

---

## Sobre a Nossa Empresa

A **Efficientia** é uma empresa de tecnologia (constituída como Sociedade Limitada - ME) dedicada a modernizar a logística e o transporte de carga viva. Nosso foco é fornecer soluções digitais que eliminam burocracias, reduzem o desperdício de papel e garantem a conformidade com legislações exigentes (como a Portaria SDA/MAPA nº 1.280/2025).

Nosso trabalho é fortemente alinhado ao **ODS 12** (Consumo e Produção Responsáveis), especificamente promovendo o uso eficiente de recursos e reduzindo a geração de resíduos por meio da digitalização completa de processos.

---

## Nosso Principal Projeto: App Efficientia

O **Efficientia** é um sistema desenvolvido para otimizar a rotina dos motoristas de transporte de bovinos, voltado inicialmente para a malha logística da JBS/Friboi.

### O Problema
Atualmente, por exigência legal, o motorista precisa preencher um longo diário de viagem em papel. Isso resulta em retrabalho, documentos danificados (sujos ou amassados), letras ilegíveis e grande perda de tempo para profissionais que já têm uma jornada desgastante nas estradas.

### A Solução
Substituímos o papel por um aplicativo inteligente focado na usabilidade do caminhoneiro (nossa persona, focada em eficiência). O app automatiza a maior parte dos dados e simplifica a operação.

**Principais Diferenciais e Funcionalidades:**
- **Registro Semi-Automático:** Horários, datas e identificação do motorista são inseridos automaticamente pelo sistema.
- **Funcionamento Offline:** Coleta dados mesmo sem internet e sincroniza quando a conexão é restabelecida.
- **Assinatura Digital Integrada:** Permite que o motorista, manobrista e curraleiro assinem diretamente na tela do dispositivo.
- **Chatbot com IA:** Um assistente virtual voltado para tirar dúvidas do caminhoneiro e melhorar a logística.
- **Dashboards e Relatórios:** Geração automática de boletins de embarque e desembarque para a empresa parceira.

---
### Ecossistema e Repositórios do Projeto

Abaixo estão os links para os repositórios integrados que compõem o ecossistema do projeto no nosso GitHub Enterprise:

| Módulo / Escopo | Repositório | Descrição |
| :--- | :--- | :--- |
| **Página Inicial / Org** | [`/Efficientia`](https://github.com/Efficientia) | Visão geral da empresa e do projeto principal (este README). |
| **Aplicativo Mobile** | [`/mobile-app`](https://github.com/Efficientia/Efficientia-mobile.git) | Código-fonte da aplicação React Native/Flutter utilizada pelos motoristas. |
| **API Backend** | [`/backend-api`]() | API central de negócios, persistência de dados e regras operacionais. |
| **Módulo de IA (Chatbot)** | [`/ai-service`](https://github.com/Efficientia/IA-desktop.git) | Serviço dedicado aos modelos de inteligência artificial e processamento do Chatbot. |
| **Infraestrutura / CI/CD** | [`/infrastructure`]() | Scripts de implantação, Docker e Workflows do GitHub Actions. |
| **Padrões Globais / Templates** | [`/.github`](https://github.com/Efficientia/.github.git) | Templates de Pull Request (`PULL_REQUEST_TEMPLATE.md`), Issues e padrões da Org. |

---
### CI/CD e Implantação (Pipeline)

Para garantir a qualidade do código e entregas contínuas, utilizamos pipelines automatizados baseados em **GitHub Actions**:

- **Validação de Código:** Todo Pull Request aberto dispara testes automatizados e linters de padronização.
- **Deploy Continuo (CD):** Merges na branch `main` ativam a automação para build da aplicação, geração de artefatos e publicação nos ambientes de staging/produção.
- *Consulte o repositório [`/.github`](https://github.com/Efficientia/.github) ou os workflows em cada repositório para conferir os arquivos `.yml` de cada pipeline.*

## Sócios Fundadores

A Efficientia é estruturada e dirigida pelos sócios:
* **Giovanni Araujo Donegatti**
[![GitHub Profile](https://img.shields.io/badge/GitHub-GiovanniDonegatti-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/ODonegatti)

* **Julie Annie David Dias Correa**
[![GitHub Profile](https://img.shields.io/badge/GitHub-JulieAnnie-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/alunojulieannieddcorrea)

* **Osmar Felipe De Carvalho**
[![GitHub Profile](https://img.shields.io/badge/GitHub-OsmarFelipe-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/alunoosmarfelipe)

* **Lucas Guerriero Santos**
[![GitHub Profile](https://img.shields.io/badge/GitHub-LucasGuerriero-181717?style=flat-square&logo=github)](https://github.com/LucasEntweihen)

* **Lucas de Oliveira Candido**
[![GitHub Profile](https://img.shields.io/badge/GitHub-LucasCandido-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/LocShore)

* **Noé Rodrigo Carrion Cusiquispe**
[![GitHub Profile](https://img.shields.io/badge/GitHub-NoeRodrigo-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/noecarrion)

* **Rogério Buscariolo da Silva**
[![GitHub Profile](https://img.shields.io/badge/GitHub-RogerioBuscariolo-181717?style=flat-square&logo=github)](https://github.com/PedroMacedo-Silva)

* **Matheus Carlos da Silva Pereira**
[![GitHub Profile](https://img.shields.io/badge/GitHub-MatheusCarlos-181717?style=flat-square&logo=github)](https://github.com/orgs/Efficientia/people/LamarckV)

* **Pedro Macêdo Silva**
[![GitHub Profile](https://img.shields.io/badge/GitHub-PedroMacedo-181717?style=flat-square&logo=github)](https://github.com/PedroMacedo-Silva)

---