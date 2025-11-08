# Dracula Theme for Notepad++

Um tema escuro moderno, elegante e confortável para o **Notepad++**, inspirado na paleta clássica do [Dracula Theme](https://draculatheme.com).  
Este tema foi adaptado e aprimorado por **Saulo de Tarso**, com foco em legibilidade, contraste equilibrado e uma experiência agradável durante longas sessões de codificação.

---

## Paleta de Cores

| Elemento | Cor | Descrição |
|-----------|------|-----------|
| Fundo | `#282A36` | Roxo escuro suave |
| Texto padrão | `#F8F8F2` | Branco-acinzentado |
| Comentários | `#6272A4` | Azul acinzentado (itálico) |
| Palavras-chave | `#FF79C6` | Rosa magenta (negrito) |
| Strings e caracteres | `#F1FA8C` | Amarelo pastel (negrito) |
| Números | `#BD93F9` | Roxo claro |
| Funções e operadores | `#8BE9FD` | Azul ciano |
| Erros | `#FF5555` | Vermelho forte |
| Seleção | `#44475A` | Cinza azulado suave |
| Linha ativa | `#3A3C4E` | Destaque leve da linha atual |
| Colchetes/Parênteses | `#50FA7B` | Verde-limão para pareamento |

---

## Fonte Utilizada

- **JetBrains Mono**  
  Uma fonte moderna, projetada especialmente para programadores, garantindo excelente legibilidade em ambientes escuros.

---

## Linguagens Suportadas

O tema oferece suporte visual consistente para as linguagens mais utilizadas por desenvolvedores **Fullstack**:

- Java  
- C / C++  
- Rust 
- HTML / XML  
- CSS 
- JavaScript  
- Python 
- JSON

---

## Instalação

1. Baixe o arquivo:  
   **[`Dracula_Theme_NotepadPlus.xml`](./Dracula_Theme_NotepadPlus.xml)**

2. Copie o arquivo para o diretório de temas do Notepad++:
   ```bash
   C:\Users\<seu_usuario>\AppData\Roaming\Notepad++\themes\
   ```
* A estrutura segue o formato padrão do Notepad++
```xml
<NotepadPlus>
  <GUIConfig name="Dracula">
    <GlobalStyles>...</GlobalStyles>
  </GUIConfig>
  <LexerStyles>
    <LexerType name="java">...</LexerType>
    <LexerType name="cpp">...</LexerType>
    <LexerType name="rust">...</LexerType>
    <LexerType name="xml">...</LexerType>
  </LexerStyles>
</NotepadPlus>
```
--- 
* Abra o Notepad++ e vá até:

* Configurações → Estilo → Tema → Dracula

* Clique em Salvar e aplicar.

## Personalização

Você pode ajustar facilmente:

* Fonte: alterando fontName="Consolas" (ou outra de sua preferência);

* Tamanho da fonte: usando fontSize="11" nas tags XML;

* Cores: modificando os valores fgColor (texto) e bgColor (fundo) nas seções <WordsStyle>.

## Créditos

Baseado na paleta original Dracula Theme
 por Zeno Rocha
.

Adaptado e configurado para o Notepad++ por Saulo de Tarso.

## Licença

Este projeto está sob a licença MIT, permitindo livre uso, modificação e distribuição, desde que os créditos sejam mantidos.

Tema Dracula – Dark, moderno e confortável.
Desenmvolvido por Saulo de Tarso.