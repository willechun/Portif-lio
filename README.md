# Portif-lio
# Portfólio Profissional — Wille Santos

Portfólio profissional desenvolvido para apresentar projetos, competências técnicas e experiências práticas na área de **Suporte de TI, Infraestrutura, Redes e Desenvolvimento**.

O projeto utiliza **HTML, CSS e JavaScript**, com integração à API pública do GitHub para carregar automaticamente os repositórios públicos e apresentar os principais projetos desenvolvidos.

---

## 🎯 Objetivo

Criar uma apresentação profissional e técnica que permita visualizar de forma rápida:

- Projetos desenvolvidos;
- Competências técnicas;
- Experiências práticas;
- Conhecimentos em infraestrutura e suporte;
- Projetos de programação e automação;
- Perfil profissional e formas de contato.

O portfólio foi desenvolvido com foco em **clareza, responsividade, manutenção simples e demonstração prática de conhecimentos técnicos**.

---

## 🛠️ Tecnologias utilizadas

### Front-end

- HTML5
- CSS3
- JavaScript
- Design responsivo
- Flexbox
- CSS Grid

### Integrações

- GitHub REST API
- Links para projetos e repositórios
- WhatsApp
- LinkedIn
- E-mail

### Desenvolvimento

- Git
- GitHub
- JavaScript assíncrono
- Fetch API
- Manipulação do DOM
- Tratamento de erros
- Validação de dados

---

## ⚙️ Funcionalidades

### 📂 Projetos do GitHub

Os projetos públicos são carregados dinamicamente através da API do GitHub.

A aplicação apresenta informações como:

- Nome do repositório;
- Descrição;
- Linguagem principal;
- Quantidade de estrelas;
- Forks;
- Link direto para o projeto.

### 🔄 Tratamento de falhas

A integração com o GitHub possui mecanismos para evitar que uma indisponibilidade externa comprometa toda a página.

Entre os recursos implementados:

- Timeout da requisição;
- Tratamento de erros;
- Estado de carregamento;
- Estado de lista vazia;
- Nova tentativa de carregamento;
- Fallback para projetos previamente definidos;
- Validação dos links dos projetos.

---

## 🧩 Arquitetura

O projeto utiliza uma estrutura simples e modular para facilitar manutenção e evolução.

```text
portfolio-wille-santos/
│
├── index.html
│
├── css/
│   └── styles.css
│
├── js/
│   └── app.js
│
└── README.md
```

### Responsabilidade de cada arquivo

**`index.html`**

Responsável pela estrutura semântica da página e organização das seções.

**`css/styles.css`**

Responsável por:

- Layout;
- Responsividade;
- Tipografia;
- Cores;
- Componentes visuais;
- Estados da interface.

**`js/app.js`**

Responsável por:

- Comunicação com a API do GitHub;
- Processamento dos dados;
- Renderização dos projetos;
- Tratamento de erros;
- Atualização dinâmica da interface.

---

## 🔗 Integração com GitHub

A aplicação utiliza a API pública do GitHub para consultar os repositórios do usuário.

Fluxo simplificado:

```text
Usuário acessa o portfólio
          │
          ▼
JavaScript inicia requisição
          │
          ▼
GitHub REST API
          │
          ▼
Processamento dos dados
          │
          ▼
Validação das informações
          │
          ▼
Renderização dos projetos
```

A utilização da API permite que novos repositórios públicos possam aparecer no portfólio sem necessidade de alterar manualmente o HTML.

---

## 🛡️ Confiabilidade

O projeto foi estruturado considerando possíveis falhas de serviços externos.

Caso a API do GitHub não esteja disponível, o sistema possui comportamento alternativo para evitar que a seção de projetos fique completamente inutilizável.

Também são considerados cenários como:

- Falha de conexão;
- Timeout;
- Resposta inválida;
- Lista de projetos vazia;
- Limitação temporária da API;
- Links inválidos.

---

## 💻 Como executar localmente

Não é necessário instalar frameworks ou dependências externas para executar o projeto.

### 1. Clone o repositório

```bash
git clone https://github.com/willechun/portfolio-wille-santos.git
```

### 2. Entre na pasta

```bash
cd portfolio-wille-santos
```

### 3. Execute um servidor local

Com Python:

```bash
python -m http.server 8000
```

### 4. Acesse

```text
http://localhost:8000
```

Também é possível abrir o `index.html` diretamente no navegador para uma visualização básica.

---

## 📱 Responsividade

O portfólio foi desenvolvido para diferentes tamanhos de tela:

- Desktop;
- Notebook;
- Tablet;
- Smartphone.

O layout utiliza CSS responsivo para adaptar os componentes conforme a largura disponível.

---

## 🧪 Competências técnicas demonstradas

Além da apresentação visual, o projeto demonstra conhecimentos práticos em:

### Suporte de TI

- Diagnóstico de problemas;
- Manutenção preventiva;
- Troubleshooting;
- Identificação de causas;
- Documentação técnica;
- Análise de desempenho.

### Sistemas

- Windows;
- Windows Server;
- Linux;
- Active Directory;
- Microsoft 365;
- PowerShell.

### Redes

- TCP/IP;
- DNS;
- DHCP;
- Gateway;
- Endereçamento IP;
- Diagnóstico de conectividade.

### Desenvolvimento

- Python;
- HTML;
- CSS;
- JavaScript;
- APIs;
- Git;
- GitHub.

### Automação

- Scripts;
- Automatização de tarefas;
- Tratamento de dados;
- Integração entre sistemas.

---

## 📌 Projetos

Os projetos apresentados no portfólio são obtidos a partir dos repositórios públicos do GitHub.

Entre os projetos públicos desenvolvidos estão:

- **Projeto-Git** — primeiro projeto utilizando Git;
- **NetFlix-Copia** — reprodução de interface utilizando HTML/CSS;
- **Certificado-digital** — projeto desenvolvido com HTML, CSS e JavaScript;
- **Card** — componente responsivo;
- **Site-de-Clinica** — site para clínica de psicopedagogia;
- **Calculadora** — aplicação desenvolvida com JavaScript.

Consulte os repositórios para visualizar o código-fonte e a implementação de cada projeto.

---

## 📈 Evolução do projeto

O portfólio foi estruturado para permitir futuras evoluções, como:

- Novos projetos;
- Estudos de caso técnicos;
- Projetos de automação;
- Scripts para suporte de TI;
- Ferramentas desenvolvidas em Python;
- Projetos de infraestrutura;
- Integrações com APIs;
- Documentação técnica;
- Demonstrações de troubleshooting.

---

## 🚀 Próximas melhorias

Planejamento de evolução:

- [ ] Adicionar estudos de caso técnicos;
- [ ] Adicionar projetos de automação com Python;
- [ ] Criar seção específica para scripts de suporte;
- [ ] Adicionar demonstrações dos projetos;
- [ ] Melhorar documentação dos repositórios;
- [ ] Adicionar métricas e resultados quando existirem;
- [ ] Criar domínio personalizado;
- [ ] Implementar monitoramento básico do site.

---

## 👨‍💻 Sobre

**Wille Santos**

Analista de Suporte de TI | Infraestrutura | Redes | Desenvolvimento

Localização: **Recife – PE**

Perfil profissional voltado para suporte técnico, diagnóstico de problemas, infraestrutura, redes, sistemas e desenvolvimento de soluções utilizando tecnologia e automação.

---

## 📫 Contato

**E-mail**

willejusto50@gmail.com

**GitHub**

https://github.com/willechun

**LinkedIn**

https://www.linkedin.com/in/wille-santos-9a266738

**WhatsApp**

https://wa.me/5581973414182

---

## 📄 Licença

Este projeto foi desenvolvido como portfólio profissional e demonstração de conhecimentos técnicos.

O código pode ser utilizado como referência para estudos, respeitando os direitos sobre conteúdos, marcas e recursos de terceiros utilizados nos projetos apresentados.

---

⭐ Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório.
