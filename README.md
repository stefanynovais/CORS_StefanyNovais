# 📘 Guia de Execução – Backend e Frontend

Este projeto é composto por duas partes:

- **Backend em Node.js**, rodando na porta **8080**
- **Frontend estático**, rodando na porta **3000**

A seguir estão todas as instruções necessárias para executar corretamente cada parte.

---

## 🚀 1. Como Executar o Backend (API – Porta 8080)

O backend foi criado utilizando **Node.js** e **Express**.

### 📌 Requisitos
- Node.js instalado na máquina  
- Estar dentro da pasta **`backend/`** onde está o arquivo `server.js`

### ▶️ Passo a passo para iniciar o backend

1. Abra o terminal.
2. Navegue até a pasta do backend:

```bash
cd backend
```

3. Execute o servidor:

```bash
node server.js
```

### ✅ Resultado esperado no terminal:

```bash
API Backend rodando em: http://localhost:8080
```

## 🌐 2. Como Executar o Frontend (Cliente – Porta 3000)

Para servir o frontend, utilizamos o pacote serve, que cria um servidor estático simples.

### 📌 Requisitos

Ter o pacote serve instalado globalmente:

```bash
npm install -g serve
```

Estar dentro da pasta frontend/, onde está o arquivo HTML.

### ▶️ Passo a passo para iniciar o frontend

1. Abra o terminal.

2. Navegue até a pasta do frontend:

```bash
cd frontend
```

3. Execute o servidor na porta 3000:

```bash
serve -l 3000
```

### ✅ Acesse a aplicação no navegador:

```bash
http://localhost:3000
```

### 🎉 Tudo pronto para realizar testes de comunicação entre as portas 8080 e 3000. 
