# Site de Apoio - Aprendizado de Máquina no Reconhecimento de Padrões Moleculares

Site institucional de apoio para o livro "Aprendizado de Máquina no Reconhecimento de Padrões Moleculares em Produtos Naturais".


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
