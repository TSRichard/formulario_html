# 📝 Formulários em HTML

![Badge HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge Estudos](https://img.shields.io/badge/estudos-Formulários%20HTML-blue)
![Badge Interatividade](https://img.shields.io/badge/interatividade-Campos%20e%20Entradas-green)

## 📚 Sobre o Projeto
Este arquivo HTML é um estudo completo sobre **formulários em HTML5**. Explorei diversos tipos de campos de entrada, atributos importantes e como estruturar um formulário para coletar diferentes tipos de dados dos usuários.

## 📁 Arquivo
| Arquivo | Descrição |
|---------|-----------|
| `formulario.html` | Demonstra a criação de formulários HTML com diversos tipos de campos e inputs |

## 🎯 O que aprendi

### Estrutura Básica do Formulário

| Tag | Significado | Função |
|-----|-------------|--------|
| `<form>` | Formulário | Container principal do formulário |
| `<fieldset>` | Conjunto de campos | Agrupa campos relacionados |
| `<legend>` | Legenda | Título do fieldset |
| `<label>` | Rótulo | Associa texto a um campo |
| `<input>` | Entrada | Campo para entrada de dados |
| `<select>` | Seleção | Lista suspensa |
| `<textarea>` | Área de texto | Campo para múltiplas linhas |

### Atributos do `<form>`

| Atributo | Valor | Função |
|----------|-------|--------|
| `method` | GET / POST | Define como os dados são enviados |
| `action` | URL | Define para onde os dados são enviados |

## 🖥️ Tipos de Input Explorados

### 📋 Campos Básicos

```html
<!-- Texto simples -->
<input type="text" size="50" maxlength="20" placeholder="Digite o nome completo" autofocus/>

<!-- Senha -->
<input type="password" placeholder="Digite sua senha"/>

<!-- Campo oculto -->
<input type="hidden" name="exemplo" value="valor">

<!-- Radio (escolha única) -->
<input type="radio" name="genero" value="feminino">Feminino
<input type="radio" name="genero" value="masculino">Masculino

<!-- Checkbox (múltiplas escolhas) -->
<input type="checkbox" name="esporte1" value="atletismo">Atletismo
<input type="checkbox" name="esporte2" value="basquete">Basquete

<!-- Lista suspensa -->
<select id="carros" name="carros">
    <option value="volvo">Volvo</option>
    <option value="mercedes">Mercedes</option>
</select>

<!-- Área de texto -->
<textarea name="mensagem" cols="60" rows="10">
    Escreva a mensagem.
</textarea>

### 📅 Campos de Data e Hora

<input type="date" min="2011-01-01"/>
<input type="datetime"/>
<input type="datetime-local"/>
<input type="month"/>
<input type="time"/>
<input type="week"/>

### 🎨 Campos Especiais
<!-- Cor -->
<input type="color"/>

<!-- Email (com validação) -->
<input type="email" required/>

<!-- Número com limites -->
<input type="number" min="2" max="8"/>

<!-- Controle deslizante -->
<input type="range" min="100" max="1000" step="100"/>

<!-- Busca -->
<input type="search" placeholder="pesquisar..."/>

<!-- Telefone -->
<input type="tel"/>

<!-- URL -->
<input type="url"/>


```
## 👨‍💻 Autor
**Richard Teixeira**
```
Estudante de Sistemas de Informação apaixonado por tecnologia.
📚 Atualmente: HTML, CSS e Python
🎯 Meta: Primeira oportunidade como desenvolvedor
```
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TSRichard)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tsrichard/)
