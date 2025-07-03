# TaskApi

Uma **API simples de agendamento de tarefas** desenvolvida com **PHP puro**, criada com o objetivo de **estudo e prática** da linguagem.

## ✨ Funcionalidades

* 📝 CRUD de tarefas (Criar, Listar, Atualizar, Deletar)
* 📌 Filtros por status (pendente, em andamento, concluída)
* 📅 Datas de criação e conclusão

```

## 🚀 Como usar

### Pré-requisitos

* PHP 8.2+
* Servidor local (Apache, Nginx ou embutido via `php -S`)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/diego5x/TaskApi.git
cd TaskApi
```

2. Inicie o servidor embutido:

```bash
php -S localhost:8000
```

3. Acesse a API via:
   `http://localhost:8000`

## 🧪 Exemplos de uso (via Postman ou curl)

### Criar uma tarefa

```http
POST /tasks
Content-Type: application/json

{
  "title": "Estudar PHP",
  "description": "Aprender estrutura MVC simples",
  "due_date": "2025-07-10"
}
```

### Listar tarefas

```http
GET /tasks
```

### Atualizar tarefa

```http
PUT /tasks/1
{
  "status": "concluída"
}
```

### Deletar tarefa

```http
DELETE /tasks/1
```

## 📚 Objetivo educacional

Este projeto não usa frameworks como Laravel ou Symfony intencionalmente, para **entender a fundo os conceitos do PHP puro**, incluindo:

* Manipulação de rotas
* Separação de responsabilidades (MVC)
* Autenticação básica
* Consumo e resposta de APIs REST

