## Para rodar basta

> Já existe um banco para testes local ( sqlite )

- Criar um ambiente virtual e ativá-lo
- Entrar na pasta do projeto e executar:

```
pip install -r requirements.txt
```

- Rodar as migrações e o migrate

```python
python manage.py makemigrations
python manage.py migrate
```

- Rodar o servidor local

```python
python manage.py runserver
```