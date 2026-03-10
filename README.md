# 🚢 Ocean Crown - Shipping & Logistics

![Ocean Crown](https://img.shields.io/badge/Status-Active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?logo=fontawesome&logoColor=white)

## 📋 Sobre o Projeto

**Ocean Crown** é um website moderno e responsivo desenvolvido para uma empresa de transporte e logística internacional. O site apresenta uma interface profissional que destaca os serviços de frete marítimo, aéreo, terrestre e cargas de projeto oferecidos pela empresa, sediada em Dubai (Emirados Árabes Unidos).

O projeto foi desenvolvido como parte do curso do **SENAI** e implementa as melhores práticas de desenvolvimento front-end, incluindo design responsivo, arquitetura CSS modular e experiência do usuário otimizada.

---

## ✨ Características

- 🎨 **Design Moderno e Profissional** - Interface clean e elegante
- 📱 **Totalmente Responsivo** - Adaptável para mobile, tablet e desktop
- 🎯 **Arquitetura CSS Modular** - Organização em componentes reutilizáveis
- 🚀 **Performance Otimizada** - Carregamento rápido e eficiente
- ♿ **Acessível** - Seguindo boas práticas de acessibilidade
- 🎭 **Animações e Transições** - Interações suaves e agradáveis
- 📐 **Grid System** - Layout baseado em CSS Grid

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica do documento
- **CSS3** - Estilização e layout
  - CSS Grid Layout
  - Flexbox
  - Media Queries
  - CSS Variables (Custom Properties)
  - Transitions e Transforms
- **Font Awesome 7.0.1** - Ícones vetoriais
- **Google Fonts** (opcional) - Tipografia customizada

---

## 📁 Estrutura do Projeto

```
Ocean_Crown/
│
├── index.html                 # Arquivo HTML principal
│
├── assets/                    # Recursos estáticos
│   └── images/               # Imagens do projeto
│       ├── about/           # Imagens da seção About
│       ├── company/         # Imagens da seção Company
│       ├── global/          # Imagens globais (globo)
│       ├── hero/            # Imagens da seção Hero
│       └── services/        # Imagens dos serviços
│
├── css/                      # Arquivos de estilo
│   ├── main.css             # Arquivo CSS principal (imports)
│   ├── media.css            # Media queries (responsividade)
│   │
│   ├── base/                # Estilos base
│   │   └── reset.css        # Reset CSS / Normalização
│   │
│   ├── layout/              # Layouts estruturais
│   │   ├── header.css       # Estilos do cabeçalho
│   │   ├── footer.css       # Estilos do rodapé
│   │   └── grid.css         # Sistema de grid
│   │
│   ├── sections/            # Estilos das seções
│   │   ├── hero.css         # Seção hero (principal)
│   │   ├── features.css     # Cards de características
│   │   ├── why__us.css      # Seção "Por que nos escolher"
│   │   ├── about.css        # Seção sobre a empresa
│   │   ├── company.css      # Informações da empresa
│   │   ├── services.css     # Seção de serviços
│   │   └── surface.css      # Seção de cobertura global
│   │
│   └── components/          # Componentes reutilizáveis
│       └── button.css       # Estilos dos botões
│
└── DisplayGrid/             # (Pasta auxiliar)
```

---

## 🎨 Seções do Website

### 1. **Header (Cabeçalho)**
- Logo da empresa com slogan
- Informações de contato
- Menu de navegação responsivo
- Hamburguer menu para mobile

### 2. **Hero Section**
- Título principal impactante
- Call-to-action (CTA) para cotação
- Cards de serviços principais:
  - ✈️ Air Freight (Frete Aéreo)
  - 🚛 Land Freight (Frete Terrestre)
  - 🚢 Sea Freight (Frete Marítimo)
  - 🚜 Project Cargo (Carga de Projeto)
  - 📋 Shipping Agency (Agência de Navegação)

### 3. **Why Choose Us (Por Que Nos Escolher)**
- Destaque dos diferenciais competitivos:
  - Envio de baixo custo
  - Preços competitivos
  - Entregas pontuais e excelentes

### 4. **About (Sobre)**
- Informações sobre a empresa
- Localização das sedes (Dubai, Basra, Antwerp)
- Imagens institucionais

### 5. **Company (Empresa)**
- Apresentação do fundador (Anwar Alam)
- Card "Who We Are" (Quem Somos)
- Card "Logistics Redefined" (Logística Redefinida)
- Destaque para inovação no setor

### 6. **Services (Serviços)**
- Galeria de serviços oferecidos
- Múltiplos cards com imagens e descrições

### 7. **Surface (Cobertura Global)**
- Visualização da presença global
- Imagem do globo terrestre

### 8. **Footer (Rodapé)**
Organizado em 4 colunas:

1. **Branding**
   - Logo da empresa
   - Texto descritivo
   - Links para redes sociais (Twitter, Facebook, YouTube)

2. **Service**
   - Links rápidos para serviços:
     - Air Freight
     - Sea Freight
     - Land Freight
     - Warehousing
     - Project Cargo
     - Customs Clearance

3. **Outlook**
   - Links institucionais:
     - About Us
     - Our Team
     - Contact
     - Career
     - News
     - Partners

4. **Subscribe**
   - Newsletter com formulário de inscrição
   - Campo de e-mail com botão de envio

---

## 🚀 Como Usar

### 1. **Clone o Repositório**
```bash
git clone https://github.com/guimunizzz/Ocean_Crown-SENAI.git
```

### 2. **Navegue até a Pasta do Projeto**
```bash
cd Ocean_Crown-SENAI
```

### 3. **Abra o Arquivo HTML**
Simplesmente abra o arquivo `index.html` em seu navegador preferido:
- Clique duas vezes no arquivo, ou
- Arraste o arquivo para o navegador, ou
- Use uma extensão como Live Server no VS Code

### 4. **Desenvolvimento Local (Opcional)**
Se estiver usando o **VS Code**, recomenda-se usar a extensão **Live Server**:
1. Instale a extensão "Live Server"
2. Clique com o botão direito em `index.html`
3. Selecione "Open with Live Server"

---

## 📱 Responsividade

O website é totalmente responsivo com três breakpoints principais:

### 🖥️ **Desktop** (acima de 920px)
- Layout completo com 4 colunas no footer
- Todos os elementos visíveis
- Menu horizontal completo

### 📱 **Tablet** (658px - 920px)
- Grid adaptado para 2 colunas
- Footer com 2 colunas
- Espaçamento otimizado

### 📱 **Mobile** (até 657px)
- Layout em coluna única
- Menu hamburguer
- Footer em coluna única
- Elementos centralizados
- Otimizado para touch

---

## 🎯 Metodologia CSS

### **BEM (Block Element Modifier)**
O projeto utiliza a metodologia BEM para nomenclatura de classes:

```css
/* Block */
.header { }

/* Element */
.header__nav { }
.header__nav-item { }

/* Modifier */
.header__nav-item.is-active { }
```

### **Arquitetura Modular**
- **Base**: Reset e normalização
- **Layout**: Estruturas de página (header, footer, grid)
- **Sections**: Seções específicas da página
- **Components**: Componentes reutilizáveis

---

## 🎨 Paleta de Cores

```css
/* Cores Principais */
--primary-color: #4a90e2;      /* Azul principal */
--dark-bg: #1a1a2e;            /* Fundo escuro */
--dark-secondary: #2c2c44;     /* Fundo escuro secundário */

/* Cores de Texto */
--text-white: #ffffff;         /* Texto branco */
--text-gray: #b8b8b8;          /* Texto cinza */
--text-light-gray: #7a7a8c;    /* Texto cinza claro */

/* Cores de Hover */
--hover-blue: #357ab8;         /* Azul hover */
```

---

## 📦 Dependências

- **Font Awesome 7.0.1** - CDN
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
  ```

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 🐛 Problemas Conhecidos

- Nenhum problema crítico identificado no momento
- Para reportar bugs, abra uma [issue](https://github.com/guimunizzz/Ocean_Crown-SENAI/issues)

---

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais como parte do programa do **SENAI**.

---

## 👨‍💻 Autor

**Guilherme Muniz**

- GitHub: [@guimunizzz](https://github.com/guimunizzz)
- Instituição: SENAI-SP
- Curso: Front-End - 3º Semestre

---

## 📚 Recursos Adicionais

- [MDN Web Docs](https://developer.mozilla.org/) - Documentação de referência
- [CSS-Tricks](https://css-tricks.com/) - Guias e tutoriais CSS
- [Font Awesome](https://fontawesome.com/) - Biblioteca de ícones
- [BEM Methodology](https://en.bem.info/) - Metodologia BEM
