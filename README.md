# 🍔 Burger House - Site da Hamburgueria

Um site moderno e responsivo para hamburgueria, desenvolvido com HTML5, CSS3 e JavaScript vanilla. O projeto apresenta design atrativo, funcionalidades interativas e experiência de usuário otimizada.

## ✨ Características Principais

### Design e Interface
- **Design Responsivo**: Adaptável para desktop, tablet e mobile
- **Animações Suaves**: Transições CSS e animações JavaScript
- **Hambúrguer Animado**: Elemento visual interativo no hero section
- **Paleta de Cores Moderna**: Laranja vibrante (#FF6B35) como cor primária
- **Tipografia Profissional**: Fonte Poppins para legibilidade e Fredoka One para o logo

### Funcionalidades Interativas

#### 🛒 Sistema de Carrinho
- Adicionar produtos ao carrinho
- Controle de quantidade (+ e -)
- Cálculo automático do total
- Persistência no localStorage
- Modal responsivo para visualização
- Processo de checkout simulado

#### 🔍 Filtros do Cardápio
- Filtrar por categoria (Todos, Hambúrgueres, Acompanhamentos, Bebidas, Sobremesas)
- Animações de transição entre filtros
- Interface intuitiva com botões destacados

#### 📱 Menu Mobile
- Menu hambúrguer responsivo
- Animação de abertura/fechamento
- Navegação suave entre seções

#### 📧 Formulário de Contato
- Validação de campos em tempo real
- Verificação de formato de e-mail
- Feedback visual para o usuário
- Simulação de envio com loading state

#### 🎯 Navegação
- Scroll suave entre seções
- Header fixo com efeito de transparência
- Links de navegação com hover effects

## 🏗️ Estrutura do Projeto

```
hamburgueria-site/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos principais
├── js/
│   └── script.js       # Funcionalidades JavaScript
├── README.md           # Documentação
└── planejamento-site.md # Documento de planejamento
```

## 🎨 Seções do Site

### 1. Header/Navegação
- Logo da Burger House
- Menu de navegação responsivo
- Botão do carrinho com contador
- Design fixo com backdrop-filter

### 2. Hero Section
- Título impactante e call-to-action
- Hambúrguer animado em CSS puro
- Gradiente de fundo atrativo
- Botões de ação principais

### 3. Cardápio
- Grid responsivo de produtos
- Sistema de filtros por categoria
- Cards com hover effects
- Botões de adicionar ao carrinho

### 4. Sobre Nós
- História da hamburgueria
- Estatísticas impressionantes
- Layout em duas colunas
- Elementos visuais representativos

### 5. Contato
- Informações de contato organizadas
- Formulário funcional com validação
- Design em duas colunas
- Ícones informativos

### 6. Footer
- Informações da empresa
- Links rápidos de navegação
- Redes sociais
- Informações de contato

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: 
  - Flexbox e Grid Layout
  - Animações e transições
  - Media queries para responsividade
  - Custom properties (variáveis CSS)
- **JavaScript ES6+**:
  - Manipulação do DOM
  - Event listeners
  - LocalStorage API
  - Intersection Observer API
  - Async/await para simulações

## 📱 Responsividade

O site é totalmente responsivo com breakpoints otimizados:

- **Desktop**: 1200px+ (layout completo)
- **Tablet**: 768px - 1199px (adaptações de grid)
- **Mobile**: até 767px (menu hambúrguer, layout vertical)
- **Mobile Pequeno**: até 480px (ajustes de tipografia e espaçamento)

## 🎯 Funcionalidades Avançadas

### Sistema de Notificações
- Notificações toast personalizadas
- Diferentes tipos (sucesso, erro, info)
- Auto-dismiss após 5 segundos
- Animações de entrada e saída

### Animações de Scroll
- Intersection Observer para animações
- Fade-in-up para elementos
- Performance otimizada

### Easter Egg
- Código Konami implementado
- Surpresa para usuários curiosos

### Otimizações de Performance
- Debounce para eventos de scroll
- Lazy loading preparado
- Código modular e organizado

## 🛠️ Como Executar

1. **Clone ou baixe o projeto**
2. **Navegue até o diretório**
3. **Inicie um servidor local**:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Node.js (se tiver http-server instalado)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```
4. **Acesse**: `http://localhost:8000`

## 🎨 Personalização

### Cores
As cores podem ser facilmente alteradas modificando as variáveis CSS no início do arquivo `style.css`:

```css
:root {
    --primary-color: #FF6B35;    /* Cor principal */
    --secondary-color: #2C3E50;  /* Cor secundária */
    --accent-color: #F39C12;     /* Cor de destaque */
    /* ... outras variáveis */
}
```

### Conteúdo
- Produtos do cardápio podem ser adicionados/editados no HTML
- Informações de contato no HTML e JavaScript
- Textos e imagens facilmente substituíveis

## 🔧 Funcionalidades Futuras

- [ ] Integração com API de pagamento
- [ ] Sistema de pedidos real
- [ ] Painel administrativo
- [ ] Integração com WhatsApp
- [ ] Sistema de avaliações
- [ ] Programa de fidelidade
- [ ] PWA (Progressive Web App)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e demonstrativos. Sinta-se livre para usar como base para seus próprios projetos.

## 👨‍💻 Desenvolvedor

Projeto desenvolvido com foco em:
- Boas práticas de desenvolvimento web
- Código limpo e organizado
- Performance e acessibilidade
- Experiência do usuário moderna
- Design responsivo e atrativo

---

**Burger House** - Os melhores hambúrgueres da cidade! 🍔
