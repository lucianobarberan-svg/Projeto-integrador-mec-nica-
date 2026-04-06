Sistema de Controle de Mecânica

Sistema web simples em Django para controle de clientes, estoque e ordens de serviço de uma oficina mecânica.

🚀 Funcionalidades
- Cadastro e listagem de clientes
- Controle de peças em estoque
- Criação de ordens de serviço
- Cálculo automático do valor total (peças + mão de obra)

📂 Estrutura
- clientes/ → gerenciamento de clientes
- estoque/ → controle de peças
- ordens/ → ordens de serviço

🛠️ Instalação

1. Clone o repositório:
   `bash
   git clone https://github.com/seuusuario/mecanica.git
   cd mecanica
   `

2. Crie e ative um ambiente virtual:
   `bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   `

3. Instale as dependências:
   `bash
   pip install django
   `

4. Configure o banco de dados:
   `bash
   python manage.py makemigrations
   python manage.py migrate
   `

5. Crie um usuário administrador:
   `bash
   python manage.py createsuperuser
   `

6. Rode o servidor:
   `bash
   python manage.py runserver
   `

7. Acesse no navegador:
   - Admin: http://127.0.0.1:8000/admin (127.0.0.1 in Bing)
   - Clientes: http://127.0.0.1:8000/clientes/ (127.0.0.1 in Bing)
   - Estoque: http://127.0.0.1:8000/estoque/ (127.0.0.1 in Bing)
   - Ordens: http://127.0.0.1:8000/ordens/ (127.0.0.1 in Bing)

📦 Requisitos
- Python 3.10+
- Django 5.x

📜 Licença
Este projeto é livre para uso e modificação.
