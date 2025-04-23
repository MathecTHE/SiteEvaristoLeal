# Elementos para Importação no Elementor

Este arquivo contém exemplos de código HTML que podem ser copiados e colados diretamente no Elementor para recriar os elementos do site da Construtora Evaristo & Leal.

## Hero Section

```html
<h1>Há mais de 25 anos construindo com qualidade, segurança e excelência.</h1>
<p>Transformamos sonhos em realidade com projetos inovadores e sustentáveis que atendem às necessidades dos nossos clientes.</p>
<a href="#servicos" class="elementor-button elementor-size-md">Conheça Nossos Serviços</a>
```

## Seção de Serviços

### Título da Seção
```html
<h2>Conheça Nossos Serviços</h2>
```

### Card de Serviço (repetir para cada serviço)
```html
<div class="service-card-elementor">
  <div class="elementor-image">
    <img src="CAMINHO_DA_IMAGEM" alt="Construção Residencial">
  </div>
  <h3>Construção Residencial</h3>
  <p>Casas e apartamentos com qualidade superior e acabamento impecável.</p>
  <a href="servicos.html" class="elementor-button elementor-size-sm">Saiba Mais</a>
</div>
```

## Seção de História

```html
<h2>Nossa História</h2>
<p>A Construtora Evaristo & Leal foi fundada em 1998 com o objetivo de oferecer serviços de construção civil de alta qualidade. Desde então, temos nos dedicado a entregar projetos que superam as expectativas de nossos clientes.</p>
<p>Com mais de 25 anos de experiência no mercado, nossa equipe de profissionais altamente qualificados está comprometida com a excelência em cada detalhe. Utilizamos materiais de primeira linha e técnicas construtivas modernas para garantir resultados duradouros e sustentáveis.</p>
<p>Ao longo dos anos, construímos uma reputação sólida baseada na confiança, transparência e compromisso com prazos. Nossos valores fundamentais de integridade, qualidade e inovação orientam todas as nossas ações.</p>
<a href="#contato" class="elementor-button elementor-size-md">Fale com Nossa Equipe</a>
```

## Processo de Trabalho

### Título da Seção
```html
<h2>Nosso Processo de Trabalho</h2>
```

### Etapa do Processo (repetir para cada etapa)
```html
<div class="process-step-elementor">
  <div class="step-number-elementor">1</div>
  <h3>Consulta Inicial</h3>
  <p>Realizamos uma reunião para entender suas necessidades, objetivos e expectativas para o projeto.</p>
</div>
```

## Galeria de Projetos

### Título da Seção
```html
<h2>Galeria: Projetos Residenciais</h2>
```

### Configuração da Galeria
- Use o widget "Gallery" do Elementor
- Configure para exibir 3 colunas em desktop, 2 em tablet e 1 em mobile
- Ative o overlay com título e subtítulo
- Configure a classe CSS personalizada: project-gallery-elementor

## Footer

### Informações de Contato
```html
<h3>Contato</h3>
<div class="contact-info">
  <i class="fas fa-map-marker-alt"></i>
  <p>Av. Rio Branco, 156 - Centro<br>Rio de Janeiro - RJ, 20040-901</p>
</div>
<div class="contact-info">
  <i class="fas fa-phone"></i>
  <p>(21) 3456-7890</p>
</div>
<div class="contact-info">
  <i class="fas fa-envelope"></i>
  <p>contato@evaristoleal.com.br</p>
</div>
```

### Ícones Sociais
```html
<div class="social-icons-elementor">
  <a href="#" class="elementor-icon">
    <i class="fab fa-facebook-f"></i>
  </a>
  <a href="#" class="elementor-icon">
    <i class="fab fa-instagram"></i>
  </a>
  <a href="#" class="elementor-icon">
    <i class="fab fa-linkedin-in"></i>
  </a>
  <a href="#" class="elementor-icon">
    <i class="fab fa-whatsapp"></i>
  </a>
</div>
```

### Copyright
```html
<p>&copy; 2025 Construtora Evaristo & Leal. Todos os direitos reservados.</p>
```
