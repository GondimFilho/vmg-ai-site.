# 🌐 VMG.AI — Soluções em IA e Desenvolvimento Web

Este repositório contém o código-fonte do site **VMG.AI**, desenvolvido por **Verlândio Gondim**. A plataforma apresenta os serviços oferecidos, portfólio de projetos, depoimentos de clientes e um formulário de contato integrado via EmailJS.

## 🚀 Demonstração

🔗 [Acesse o site publicado](https://<seu-link-do-firebase>.web.app)  
*(Substitua pelo link real após o deploy no Firebase)*

---

## 📁 Estrutura

Este site é um projeto **estático**, desenvolvido apenas com **HTML, CSS e JavaScript** puro.

- `index.html`: Página principal com todas as seções (sobre, serviços, portfólio, contato)
- `foto_perfil.jpg`: Imagem de perfil usada na seção "Sobre Mim"
- Integrações externas:
  - Ícones via [Font Awesome](https://fontawesome.com/)
  - EmailJS para envio de mensagens no formulário
  - WhatsApp flutuante

---

## 🛠 Tecnologias Usadas

- HTML5
- CSS3 (inline)
- JavaScript
- Font Awesome
- [EmailJS](https://www.emailjs.com/)
- Firebase Hosting (opcional para deploy)

---

## 📷 Captura de Tela

*(Inclua aqui prints do site ou gifs, se quiser)*

---

## 📨 Contato

📧 verlandio.gondim.engenharia@gmail.com  
📱 WhatsApp: [91 98512-2880](https://wa.me/5591985122880)

---

## 📦 Deploy com Firebase Hosting

> Certifique-se de ter o Node.js e Firebase CLI instalados.

```bash
# 1. Login
firebase login

# 2. Inicializar projeto Firebase na pasta do site
firebase init hosting

# 3. Definir diretório público como "."
# 4. Não sobrescrever index.html
# 5. Fazer o deploy
firebase deploy
