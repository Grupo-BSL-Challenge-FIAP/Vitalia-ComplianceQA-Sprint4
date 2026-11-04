<p align="center">
  <img width="270" height="270" alt="image" src="https://res.cloudinary.com/dt26mfzpw/image/upload/v1788957793/vitalia-logo-full_khdewh.png" />
</p>

# 🐾 Vitalia


**Sprint 4 · Compliance Quality Assurance e Tests · Test Plan com Azure DevOps**

API REST em **ASP.NET Core / .NET 10** do módulo comercial da plataforma **Vitalia** (categorias, produtos, carrinho, checkout e pedidos), publicada no **Azure Web App** por uma pipeline de **CI/CD no Azure DevOps** e persistindo dados em um **Oracle Database em nuvem (Oracle)**.

---

## 📑 Índice

- [👥 Integrantes](#-integrantes)
- [🔗 Links](#-links)
- [📚 Descrição da solução](#-descrição-da-solução)
- [🚀 Stack de tecnologias](#-stack-de-tecnologias)
- [🧰 Projeto no Azure DevOps](#-projeto-no-azure-devops)

---

## 👥 Integrantes

<table>
  <tr>
    <td width="130">
      <img src="https://github.com/moisesBarsoti.png" width="120" style="border-radius: 50%;"/>
    </td>
    <td>
      <b>Moisés Barsoti Andrade de Oliveira</b><br/>
      <b>RM:</b> 565049 &nbsp;&nbsp;|&nbsp;&nbsp;<b>Turma:</b> 2TDSPO - FIAP <br/>
    </td>
  </tr>
  <tr>
    <td width="130">
      <img src="https://github.com/sSofia-s.png" width="120" style="border-radius: 50%;"/>
    </td>
    <td>
      <b>Sofia Siqueira Fontes</b><br/>
      <b>RM:</b> 563829 &nbsp;&nbsp;|&nbsp;&nbsp;<b>Turma:</b> 2TDSPG - FIAP <br/>
    </td>
  </tr>
  <tr>
    <td width="130">
      <img src="https://github.com/manuelalacerda.png" width="120" style="border-radius: 50%;"/>
    </td>
    <td>
      <b>Manuela de Lacerda Soares</b><br/>
      <b>RM:</b> 564887 &nbsp;&nbsp;|&nbsp;&nbsp;<b>Turma:</b> 2TDSPG - FIAP <br/>
    </td>
  </tr>
</table>

---

## 🔗 Links

| Item | Link |
|------|------|
| Repositório no GitHub | https://github.com/Grupo-BSL-Challenge-FIAP/Vitalia-ComplianceQA-Sprint4 |
| Projeto no Azure DevOps | https://dev.azure.com/Grupo-BSL-Vitalia/Vitalia%20-%20Sprint%204%20-%20Compliance%20QA%20e%20Tests |
| Vídeo no YouTube | `<URL vídeo>` |
| Swagger - API Java | https://vitalia-txa9.onrender.com/swagger-ui/index.html#/ |

---

## 📚 Descrição da solução

O **Vitalia** é uma plataforma de saúde e cuidado de pets, com aplicativo mobile, dispositivos de monitoramento e serviços de backend. 
Nesta entrega, o escopo é a validação da API REST Java do projeto, que oferece recursos relacionados a usuários, pets, consultas, históricos clínicos, alertas e medições.

A Sprint 4 concentra-se em qualidade e testes. Os casos manuais são registrados no Azure DevOps e associados aos itens de trabalho correspondentes. Os testes automatizados são preparados para execução no Postman Web contra a API Java.

---

## 🚀 Stack de tecnologias

| Camada | Tecnologia |
|---|---|
| Linguagem da API | Java |
| Autenticação e autorização | JWT Bearer |
| Documentação dos endpoints | Swagger / OpenAPI |
| Hospedagem da API | Render |
| Banco de dados | Oracle Database |

### Qualidade e entrega

| Uso | Ferramenta |
|---|---|
| Registro e acompanhamento dos casos manuais | Azure DevOps Boards |
| Testes automatizados da API | Postman Web |
| Versionamento e documentação | GitHub |
| Demonstração dos testes automatizados | Demonstração em Vídeo |

---

## 🧰 Projeto no Azure DevOps

| Configuração | Valor |
|--------------|-------|
| Organização | `Grupo-BSL-Vitalia` |
| Project name | Vitalia - Sprint 4 - Compliance QA e Tests |
| Description | Sistema de monitoramento de saúde em tempo real para pets. |
| Visibility | Private |
| Version control | Git |
| Work item process | `Scrum` |
| Acesso do professor | Convidado com nível de acesso **Basic** |

## Parte A - Testes manuais (Azure Boards)
- Menu Test Plans: 1 suíte por PBI da Sprint 4, 6 Test Cases, cada um na Iteration do PBI.
- Sistema sob teste: API Java do Vitalia (Swagger no Render).
- Catálogo completo: [`docs/`](docs/)
- Evidências: `docs/Resultados testes manuais`

- ## Parte B - Automação (Postman na web)
- Collection e Environment: [`postman/`](postman/)
- 5 requisições: login, rota sem token, perfil, pets do tutor e validação de campo obrigatório.
- Como executar: importar o JSON no Postman e executar.
  
---
