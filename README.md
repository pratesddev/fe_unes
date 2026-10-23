# 🚀 UNES

> Site institucional de uma universidade fictícia, desenvolvido como exercício de HTML5.

[![Status](https://img.shields.io/badge/status-Educacional-blue)]()
[![Version](https://img.shields.io/badge/version-0.1.0-blue)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()

---

## 📋 Sobre o projeto

O **UNES** é um projeto de estudo desenvolvido durante o curso **Domine Web – 20 Cursos**, disponível na Udemy. A proposta é construir um site institucional simples para uma universidade fictícia, praticando a estruturação de páginas com HTML5.

O projeto contém três páginas estáticas: página inicial, apresentação da universidade e contato. A navegação entre elas é feita por links HTML, e os elementos visuais utilizam imagens locais armazenadas no diretório `imagens/`.

### 🎯 Objetivos de aprendizagem

- Praticar a estrutura básica de um documento HTML5.
- Utilizar títulos, parágrafos, listas, links, imagens e formulários.
- Compreender a navegação entre páginas estáticas.
- Organizar os arquivos de um pequeno projeto front-end.
- Reconhecer técnicas legadas de construção de layout e identificar oportunidades de modernização.

### 🧩 Características da implementação

- **Tecnologia:** HTML5.
- **Estilização:** atributos HTML tradicionais e estilos de apresentação diretamente na marcação; não há folha CSS separada nesta versão.
- **Layout:** tabelas HTML utilizadas para organizar a estrutura visual, exclusivamente para fins didáticos.
- **Conteúdo:** textos demonstrativos e informações fictícias.
- **Formulário:** a página de contato apresenta campos para e-mail, assunto e descrição. Não há integração com backend para processar ou enviar mensagens.

> **Nota didática:** tabelas devem ser reservadas à apresentação de dados tabulares, e não usadas para estruturar layouts. Em uma evolução do projeto, recomenda-se adotar HTML semântico e CSS com Flexbox ou Grid, além de revisar acessibilidade e responsividade.

---

## 🖥️ Páginas do projeto

| Página | Arquivo | Descrição |
|---|---|---|
| Página inicial | `index.html` | Apresentação inicial da universidade fictícia. |
| Quem somos | `quem_somos.html` | Conteúdo institucional, lista de motivos para estudar e objetivos. |
| Contato | `contato.html` | Formulário demonstrativo de contato, sem envio funcional. |

As páginas compartilham a navegação principal com links para **Home**, **Quem somos** e **Contato**.

---

## 🛠️ Tecnologias e recursos

- **HTML5** — estrutura e conteúdo das páginas.
- **Imagens locais** — recursos gráficos armazenados no diretório `imagens/`.
- **Git** — controle de versão do projeto.

Este projeto não utiliza, em sua versão atual, frameworks JavaScript, gerenciadores de pacotes, ferramentas de build ou dependências externas.

---

## 📁 Estrutura do projeto

```text
fe_unes/
├── imagens/
│   ├── capa.png
│   ├── fundo.png
│   ├── fundo2.png
│   └── logo.png
├── index.html
├── quem_somos.html
├── contato.html
└── README.md
```

---

## ▶️ Como executar

Como o projeto é composto por arquivos HTML estáticos, não é necessário instalar dependências.

1. Faça o download ou clone o repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.

### Executar com o VS Code

Abra a pasta do projeto no Visual Studio Code e, se desejar, utilize a extensão **Live Server** para visualizar as páginas com recarregamento automático durante a edição.

Não há comandos `npm install`, `npm run dev` ou etapa de compilação para esta versão.

---

## ✅ Testes e validação

Após abrir o projeto, verifique manualmente:

- [ ] A página inicial abre corretamente.
- [ ] Os links de navegação levam às páginas correspondentes.
- [ ] As imagens e os fundos são carregados.
- [ ] A página “Quem somos” exibe os títulos e a lista ordenada.
- [ ] O formulário da página “Contato” apresenta os campos esperados.
- [ ] As páginas podem ser abertas em diferentes larguras de janela.

**Limitação conhecida:** o formulário é apenas visual/demonstrativo e não envia mensagens para um servidor. O layout utiliza uma estrutura fixa com tabela e pode não se adaptar adequadamente a telas pequenas.

---

## 🗺️ Melhorias futuras

Sugestões para uma próxima versão:

1. Separar a apresentação visual em um arquivo CSS.
2. Substituir tabelas de layout por elementos semânticos (`header`, `nav`, `main`, `section` e `footer`) e CSS Flexbox/Grid.
3. Melhorar a responsividade para dispositivos móveis.
4. Adicionar textos alternativos descritivos às imagens.
5. Revisar a hierarquia dos títulos, rótulos e atributos dos campos do formulário.
6. Implementar validação e integração do formulário com um backend, caso o projeto passe a ter essa finalidade.
7. Substituir os textos de preenchimento por conteúdo institucional coerente.

---

## 👤 Autor

**Diego Prates**

- GitHub: [@pratesddev](https://github.com/pratesddev)
- LinkedIn: [Diego Prates](https://linkedin.com/in/prates-diego)
- E-mail: [dmoprates1@gmail.com](mailto:dmoprates1@gmail.com)

---

<div align="center">

Desenvolvido por **Diego Prates** para fins educacionais.

</div>
