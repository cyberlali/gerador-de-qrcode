# Gerador de QR Code

Uma aplicação web prática e minimalista para gerar QR Codes a partir de qualquer texto ou URL.

## 🚀 Funcionalidades

- **Geração de QR Code:** Transforma textos ou links (URLs) em códigos QR de 150x150 pixels, gerados instantaneamente.
- **Integração com API:** Utiliza a API pública do `qrserver.com` para criar e obter as imagens dinamicamente.
- **Validação com Animação:** Se tentar gerar um código sem introduzir texto, o campo de entrada exibe uma animação de tremor ("shake") como aviso visual.
- **Transições Suaves:** A imagem do QR Code surge na tela com uma expansão suave do container.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura da página e campo de entrada de texto.
- **CSS3:** Estilização visual, cores, layout centralizado e animações (`@keyframes`).
- **JavaScript (Vanilla):** Lógica da aplicação, manipulação do DOM e atualização dinâmica da imagem.

## 📁 Estrutura de Arquivos

- `index.html`: Contém a interface principal e o script com a lógica de funcionamento.
- `style.css`: Contém todas as regras de formatação visual e de animação.

## 💻 Como Executar o Projeto

**1. Clone este repositório para o seu computador:**

`git clone https://github.com/cyberlali/gerador-de-qrcode.git`

**2. Acesse a pasta do projeto:**

`cd gerador_de_qrcode`

**3. Abra o projeto:**
Certifique-se de que os arquivos `index.html` e `style.css` se encontram na mesma pasta. Depois, basta abrir o arquivo `index.html` no seu navegador web de preferência e começar a gerar os seus códigos!

---
Desenvolvido por [Laura](https://github.com/cyberlali)
