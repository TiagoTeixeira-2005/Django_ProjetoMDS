# Django de Monitoramento de Gastos Públicos

Estrutura base do nosso projeto em Django, fornecendo os componentes essenciais e a configuração inicial para o desenvolvimento de funcionalidades personalizadas e escaláveis.

## Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas:
- **Python** (versão 3.8 ou superior)
- **Git**

## Instalação e configuração

1. **Clone o repositório**:
   ```bash
   git clone 
   cd Django_MGP
   ```

2. **Crie um ambiente virtual**:
   ```bash
   python3 -m venv venv  # Linux/Mac
   source venv/bin/activate  # Linux/Mac
   python -m venv venv     # Windows
   .\venv\Scripts\Activate.ps1     # Windows
   ```

3. **Instale as dependências**:
   ```bash
   pip install django
   ```

4. **Aplique as migrações do banco de dados** (se aplicável):
   Caso o projeto utilize banco de dados, execute:
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor**:
   ```bash
   python manage.py runserver
   ```

6. **Acesse o projeto no navegador**:
   Abra [http://127.0.0.1:8000/](http://127.0.0.1:8000/) para visualizar o projeto.

## Estrutura do projeto
- `manage.py`: Comando principal para gerenciar o projeto.
- `db.sqlite3` (se aplicável): Banco de dados utilizado pelo Django.

## Contribuição

Sinta-se à vontade para abrir **issues** ou enviar **pull requests** com melhorias!

## Licença

Este projeto é de uso livre para fins educativos.
