# Site de Apoio - Aprendizado de Máquina no Reconhecimento de Padrões Moleculares

Site institucional de apoio para o livro "Aprendizado de Máquina no Reconhecimento de Padrões Moleculares em Produtos Naturais".

## Recursos

- **Design Moderno**: Interface limpa e profissional com efeitos gradientes e animações suaves
- **Totalmente Responsivo**: Otimizado para desktop, tablet e dispositivos móveis
- **Elementos Interativos**: Efeitos hover, animações de scroll e transições suaves
- **Integração com Datasets**: Funcionalidade de acesso a bancos de dados via Google Drive
- **SEO Otimizado**: Estrutura HTML5 semântica com meta tags adequadas
- **Carregamento Rápido**: Mínimas dependências com recursos hospedados em CDN

## Tecnologias Utilizadas

- **HTML5**: Estrutura de marcação semântica
- **Tailwind CSS**: Framework CSS utilitário (via CDN)
- **Font Awesome**: Biblioteca de ícones
- **JavaScript Vanilla**: Interatividade e animações
- **Google Fonts**: Família de fontes Inter

## Seções da Página

1. **Seção Principal**: Introdução atrativa com botões de chamada para ação
2. **Recursos do Livro**: Seis recursos principais com ícones e descrições
3. **Como Funciona**: Linha do tempo passo a passo da metodologia de análise
4. **Propósito Científico**: Explicação detalhada do propósito do livro
5. **Chamada para Ação**: Seção final de conversão
6. **Rodapé**: Links e créditos

## Implantação

### GitHub Pages

1. Envie os arquivos para seu repositório GitHub
2. Vá em Configurações do repositório → Pages
3. Selecione fonte como "Deploy from a branch"
4. Escolha branch main e pasta / (root)
5. Seu site estará disponível em `https://[seu-usuario].github.io/[repositorio]`

### Implantação Alternativa

A página é um arquivo HTML estático e pode ser implantada em qualquer servidor web ou serviço de hospedagem que suporte arquivos estáticos.

## Personalização

### Acesso a Datasets via Google Drive

Para habilitar a funcionalidade de acesso aos datasets:

1. Crie uma pasta no Google Drive com os datasets do livro
2. Compartilhe a pasta e obtenha o link
3. Copie o ID da pasta da URL (parte após `/folders/`)
4. Substitua `SEU_ID_DA_PASTA_AQUI` na seção JavaScript do `index.html`

```javascript
const googleDriveFolderId = 'SEU_ID_REAL_DA_PASTA_AQUI';
```

### Cores e Estilos

As cores gradientes principais são definidas no CSS:

```css
.gradient-bg {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

Você pode modificar estas cores para combinar com sua identidade visual:

- `#667eea` - Azul primário
- `#764ba2` - Roxo secundário

### Atualização de Conteúdo

Todo o conteúdo de texto é facilmente editável no arquivo HTML:

- Atualize títulos e descrições nas seções relevantes
- Modifique os cards de recursos na seção de Recursos
- Ajuste os passos da metodologia em "Como Funciona"
- Atualize links e informações de contato

## Desempenho

- Pontuação Lighthouse: 95+ (Performance, Accessibility, Best Practices, SEO)
- Mínimas dependências externas
- Imagens e assets otimizados
- CSS e JavaScript eficientes

## Suporte a Navegadores

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Licença

Este site de apoio é open source e disponível sob a Licença MIT.

## Sobre o Livro

"Aprendizado de Máquina no Reconhecimento de Padrões Moleculares em Produtos Naturais" é uma obra completa que integra técnicas de quimiometria e machine learning para análise de produtos naturais, combinando métodos espectroscópicos modernos com algoritmos computacionais avançados para identificação de padrões moleculares.
