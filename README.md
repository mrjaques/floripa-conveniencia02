````markdown
# 📱 Cardápio Digital com Integração WhatsApp

Um projeto de **website responsivo** para estabelecimentos como lanchonetes, bares, restaurantes e conveniências que desejam um **cardápio digital simples, rápido e direto ao ponto** — com integração ao WhatsApp para facilitar o pedido do cliente e o recebimento pela loja.

---

## 🚀 Funcionalidades

- 🛒 **Pedidos Online**: o cliente acessa o site, escolhe os itens, preenche os dados de entrega e é direcionado automaticamente ao WhatsApp com o pedido formatado.
- 📦 **Integração com WhatsApp**: sem precisar baixar apps! Tudo pelo navegador e finalizado via WhatsApp.
- 📊 **Painel Administrativo**: a loja acessa um painel interno para visualizar, acompanhar e gerenciar os pedidos recebidos.
- 📱 **Design Responsivo**: funciona em celulares, tablets e computadores.
- 🔐 **Admin Protegido por Senha**.

---

## 🧱 Tecnologias Utilizadas

- **HTML5 / CSS3 / JavaScript**
- **PHP** (para o painel admin e controle de pedidos)
- **Planilha Excel / JSON / MySQL** (dependendo da versão de armazenamento)
- **WhatsApp API Link Format**

---

## 🧾 Como Funciona

1. O cliente acessa o site (ex: `meu-site.com`).
2. Visualiza os produtos organizados em categorias.
3. Seleciona os itens desejados e clica em "Finalizar Pedido".
4. Preenche nome, endereço e outras informações necessárias.
5. É direcionado para o WhatsApp com todos os dados já preenchidos.
6. A loja recebe o pedido e organiza a entrega.
7. O painel admin mostra os pedidos recebidos e permite marcar como entregues, visualizar detalhes e atualizar o cardápio.

---

## 💻 Demonstração

🔗 [Acesse o site de exemplo](https://rapidoo-delivery.netlify.app/)  
*Obs: versão estática de demonstração. Algumas funcionalidades dinâmicas como pedidos e painel admin podem estar limitadas.*

---

## 📂 Estrutura do Projeto

```bash
/
├── index.html               # Página principal com o cardápio
├── assets/                  # Imagens, CSS e JS
├── admin/                   # Painel administrativo protegido
│   ├── login.php
│   ├── dashboard.php
│   └── ...
├── pedidos/                 # Armazena os pedidos recebidos (dependendo da implementação)
├── config/                  # Configurações gerais (ex: número do WhatsApp, categorias, etc.)
└── README.md
````

---

## ⚙️ Como Instalar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/seu-repositorio.git
```

2. Configure o número do WhatsApp e dados no arquivo de configuração (ex: `config/config.php`).

3. Suba os arquivos para sua hospedagem PHP (ex: HostGator, InfinityFree, etc).

4. Acesse o painel admin via `seusite.com/admin` e insira suas credenciais.

---

## 📬 Contato

Dúvidas ou sugestões? Entre em contato:

* WhatsApp: [Clique aqui](https://wa.me/5551996277338)
* Email: [seuemail@exemplo.com](mailto:mrjaques7@gmail.com)

---

## 📝 Licença

Este projeto é de uso livre para fins educativos e comerciais com os devidos créditos ao autor.

```
