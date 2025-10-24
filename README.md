# Organização de Projetos Sociais - Website

## Descrição

Este é um projeto web completo desenvolvido como trabalho acadêmico, focando na aplicação de fundamentos de **HTML5 semântico**, **formulários complexos** e **multimídia**. O website representa uma organização fictícia dedicada a projetos sociais e voluntariado.

## Estrutura do Projeto

```
projeto-web/
├── html/
│   ├── index.html          # Página inicial
│   ├── projetos.html       # Página de projetos sociais
│   └── cadastro.html       # Página com formulário de cadastro
├── css/
│   └── styles.css          # Estilos CSS
├── imagens/
│   ├── missao.jpg          # Imagem da seção "Missão"
│   ├── valores.jpg         # Imagem da seção "Valores"
│   ├── contato.jpg         # Imagem da seção "Contato"
│   ├── educacao.jpg        # Imagem do projeto de educação
│   ├── saude.jpg           # Imagem do projeto de saúde
│   ├── alimentacao.jpg     # Imagem do projeto de alimentação
│   └── ambiente.jpg        # Imagem do projeto ambiental
└── README.md               # Este arquivo
```

## Especificações Técnicas

### HTML5 Semântico

- **3 páginas HTML** com estrutura semântica completa
- Uso de tags semânticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Hierarquia de títulos (`<h1>` a `<h4>`) lógica e consistente
- Imagens otimizadas em todas as páginas

### Páginas Implementadas

#### 1. **Página Inicial (index.html)**
- Apresentação da organização
- Seção "Sobre Nós" com missão e valores
- Informações de contato completas
- Destaques recentes

#### 2. **Projetos Sociais (projetos.html)**
- Descrição de 4 projetos ativos:
  - Educação para Todos
  - Saúde Comunitária
  - Alimentação Segura
  - Sustentabilidade Ambiental
- Seção "Como Ajudar" com informações sobre voluntariado e doações
- Histórias de impacto e testemunhas

#### 3. **Cadastro (cadastro.html)**
- Formulário completo com validação HTML5
- Campos implementados:
  - Nome Completo (text, required, minlength, maxlength)
  - Email (email, required)
  - CPF (text, pattern, required)
  - Telefone (tel, pattern, required)
  - Data de Nascimento (date, required)
  - Endereço (text, required, minlength, maxlength)
  - CEP (text, pattern, required)
  - Cidade (text, required)
  - Estado (select, required)
  - Tipo de Contribuição (checkbox)
  - Projeto de Interesse (select, required)
  - Disponibilidade de Tempo (select)
  - Mensagem Adicional (textarea, maxlength)
  - Consentimento (checkbox, required)

### Validação

- **Validação Nativa HTML5**: Uso de atributos como `required`, `type`, `pattern`, `minlength`, `maxlength`
- **Agrupamento Lógico**: Uso de `<fieldset>` e `<legend>` para organizar campos
- **Máscaras de Input**: Padrões regex para CPF, telefone e CEP
- **Validação JavaScript**: Verificação adicional para checkboxes

### CSS Responsivo

- Design responsivo para dispositivos móveis, tablets e desktops
- Media queries para telas menores que 768px e 480px
- Flexbox e Grid para layout moderno
- Cores consistentes com paleta azul profissional

### Imagens Otimizadas

- Todas as imagens foram redimensionadas para 800x600px
- Compressão JPEG com qualidade 85
- Tamanho total otimizado para melhor performance

## Como Usar

1. **Abrir as páginas**: Abra os arquivos HTML em um navegador web
   - `html/index.html` - Página inicial
   - `html/projetos.html` - Projetos sociais
   - `html/cadastro.html` - Formulário de cadastro

2. **Navegar**: Use o menu de navegação para ir entre as páginas

3. **Testar o Formulário**: Preencha o formulário de cadastro e veja a validação em ação

## Validação W3C

Todos os arquivos HTML foram validados conforme os padrões W3C HTML5:
- ✓ Estrutura semântica correta
- ✓ Atributos válidos
- ✓ Hierarquia de títulos apropriada
- ✓ Imagens com atributo `alt`

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e formulários
- **CSS3**: Estilos responsivos
- **JavaScript**: Validação adicional do formulário
- **Imagens**: JPEG otimizado

## Requisitos Atendidos

- ✓ Mínimo 3 páginas HTML com estrutura semântica completa
- ✓ Hierarquia de títulos lógica e consistente
- ✓ Imagens em todas as páginas
- ✓ Página inicial com informações de contato
- ✓ Página de projetos sociais (voluntariado e doações)
- ✓ Página de cadastro com formulário complexo
- ✓ Validação nativa HTML5
- ✓ Agrupamento lógico de campos
- ✓ Máscaras de input para CPF, telefone e CEP
- ✓ Código fonte completo e organizado
- ✓ Imagens otimizadas
- ✓ Arquivos HTML validados (W3C)

## Autor

Desenvolvido como trabalho acadêmico de Fundamentos de Lançamento de Link da Web.

## Data

Outubro de 2024
