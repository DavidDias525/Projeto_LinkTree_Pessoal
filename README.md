# 💻 Portfólio Pessoal - David Dias

Este é o repositório do portfólio pessoal e profissional de **David Dias**, estudante de **Análise e Desenvolvimento de Software**. A página foi desenhada para funcionar como um cartão de visitas digital interativo, centralizando redes sociais, projetos recentes e tecnologias de domínio.

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando práticas modernas de desenvolvimento web focado no front-end essencial:

- **HTML5**: Estruturação semântica de todo o conteúdo da página.
- **CSS3 Moderno**: Estilização avançada utilizando componentes de layout como **Flexbox** e **CSS Grid**, além de variáveis de cores e gradientes complexos.

---

## ✨ Funcionalidades e Diferenciais Visuais

O design da aplicação conta com uma identidade visual marcante utilizando uma paleta de cores baseada em `slateblue` e uma tipografia limpa (`Trebuchet MS`).

### 🎨 Animações e Efeitos
* **Animação Fade-In (`.animate-fade-in`)**: Transição suave com deslocamento vertical (`translateY`) que introduz os elementos da página de forma fluida assim que ela é carregada.
* **Efeito de Zoom**: A foto de perfil possui uma transição de escala (`scale(1.05)`) ao passar o ponteiro do mouse (`:hover`).
* **Elevação de Cards e Botões**: Efeito de profundidade com sombras virtuais (`box-shadow`) e elevações suaves de posicionamento ao interagir com os links e projetos.

### 🗂️ Grid de Projetos
A seção de portfólio está dividida em uma grade flexível que exibe de maneira limpa as seguintes especialidades:
* **Front-end App**: Focado no ecossistema JavaScript moderno e React.
* **Back-end API**: Construção de servidores e integração de banco de dados com Node.js.

### 🔗 Botões de Redes Sociais Customizados
Cada botão de navegação possui uma identidade que remete diretamente à plataforma de destino:
* **LinkedIn**: Fundo na cor sólida azul oficial corporativa.
* **GitHub**: Fundo escuro característico do repositório.
* **Instagram**: Gradiente linear multicolorido combinando as cores da marca.

---

## 📱 Responsividade (Mobile Friendly)

A página foi totalmente projetada sob o conceito de **Responsividade Web**. Através de regras de `@media (max-width: 550px)`, o layout se adapta dinamicamente a telas menores e smartphones:
* O sistema de grade de projetos (`projects-grid`) passa automaticamente de 2 colunas para **1 coluna vertical**.
* Os botões de navegação lateral (`nav`) são reestruturados para empilhamento vertical ocupando a largura total da tela (`width: 100%`), melhorame a usabilidade em dispositivos touch.

---

## 🌐 Contatos & Redes Sociais

Substitua os links abaixo pelas URLs do seu perfil real:

- 👔 LinkedIn: `https://www.linkedin.com/in/seu-usuario/`
- 🐙 GitHub: `https://github.com/seu-usuario/`
- 📸 Instagram: `https://www.instagram.com/seu-usuario/`

---

## 🛠️ Como Subir no GitHub e Publicar (GitHub Pages)

Siga os passos abaixo no terminal para salvar seu projeto na nuvem e publicá-lo para que qualquer pessoa consiga acessá-lo online de graça.

### 1. Inicializar e Enviar o Código para o GitHub
Dentro da pasta raiz do seu projeto, execute os seguintes comandos no terminal:

```bash
# Inicializar o repositório Git local
git init

# Adicionar todos os arquivos ao estágio de envio
git add .

# Criar o primeiro commit com uma mensagem descritiva
git commit -m "feat: estrutura inicial do portfolio e readme"

# Criar e alternar para a branch principal (main)
git branch -M main

# Vincular o repositório local ao seu repositório remoto do GitHub
# (Substitua a URL abaixo pela URL gerada no seu GitHub ao criar o repositório)
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git

# Enviar os arquivos para a nuvem
git push -u origin main
```

### 2. Ativar o GitHub Pages (Colocar o Site Online)
Depois de subir o código para o GitHub, siga estes passos na interface web:

1. Acesse a página do seu repositório no **GitHub**.
2. No menu superior do repositório, clique na aba **Settings** (Configurações).
3. Na barra lateral esquerda, desça até a seção **Code and automation** e clique em **Pages**.
4. Sob a opção **Build and deployment**, localize o campo **Source** e certifique-se de que está selecionado `Deploy from a branch`.
5. No campo **Branch**, mude de `None` para **`main`** (ou a branch correspondente) e mantenha a pasta como `/root`.
6. Clique no botão **Save**.

> ⏱️ **Nota**: Aguarde de 1 a 2 minutos. O GitHub gerará um link público no topo dessa mesma página do *GitHub Pages* com o formato: `https://seu-usuario.github.io/nome-do-repositorio/`.