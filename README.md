
#  Projeto Laravel

## Requisitos

- PHP 8.2 ou superior  
- Composer instalado na máquina

---

## Como rodar o projeto localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-projeto.git
   cd seu-projeto
   ```

2. Duplique o arquivo `.env.example` e renomeie para `.env`:
   ```bash
   cp .env.example .env
   ```

3. Instale as dependências:
   ```bash
   composer install
   ```

4. Gere a chave da aplicação:
   ```bash
   php artisan key:generate
   ```

5. (Opcional) Configure seu banco de dados no arquivo `.env`.

6. Rode as migrations (se houver):
   ```bash
   php artisan migrate
   ```

7. Inicie o servidor de desenvolvimento:
   ```bash
   php artisan serve
   ```

8. Acesse o projeto em:  
   [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

##  Criando um novo projeto Laravel do zero

Para criar um novo projeto Laravel localmente:

```bash
composer create-project laravel/laravel nome-do-projeto
```

Ou, para criar no diretório atual:

```bash
composer create-project laravel/laravel .
```

---

##  Testes

(Se houver testes no projeto, você pode adicionar aqui: `php artisan test` ou `phpunit`.)

---

##  Licença

Este projeto está sob a licença MIT.
