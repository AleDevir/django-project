# Django Surveys Project

### Requisitos
- [Miro: Surveys Project](https://miro.com/app/board/uXjVLX7sp2I=/?share_link_id=488501560439)

### Download do projeto
- `git clone https://github.com/rafaelassacconi/django-project.git` - clona o repositório
- `cd django-project` - entra na pasta do projeto
- `python -m venv .venv` - cria virtualenv
- `source .venv/bin/activate` ou `.\.venv\Scripts\activate` - ativa virtualenv
- `pip install -r requirements.txt` - instala dependências
- `cd womakers` - entra na pasta do sistema
- `python manage.py migrate` - executa migrações
- `python manage.py createsuperuser` - cria usuário do admin
- `python manage.py runserver` - executa aplicação

### Comandos

#### Criação do projeto
- `mkdir django-project` - cria pasta do projeto
- `cd django-project` - entra na pasta do projeto
- `python -m venv .venv` - cria virtualenv
- `source .venv/bin/activate` ou `.\.venv\Scripts\activate` - ativa virtualenv
- `pip install Django` - instala Django

#### Criação da aplicação
- `django-admin startproject womakers` - cria projeto Django
- `cd womakers` - entra na pasta do sistema
- `python manage.py startapp surveys` - cria app

#### Migrações
- `python manage.py migrate` - executa migrações
- `python manage.py showmigrations` - mostra status das migrações
- `python manage.py sqlmigrate surveys 0001` - mostra SQL da migração

#### Outros
- `python manage.py runserver` - executa aplicação
- `python manage.py createsuperuser` - cria usuário do admin
- `python manage.py --help` - ver opções de comandos
- `python manage.py shell` - executa o console
- `python manage.py test` - executa os testes
- `python manage.py test surveys.tests.test_models.QuestionTestCase` - executa um teste específico

### Documentações

#### Models
- [Model example](https://docs.djangoproject.com/en/5.1/topics/db/models/#quick-example)
- [Fields](https://docs.djangoproject.com/en/5.1/ref/models/fields/)
- [DateField](https://docs.djangoproject.com/en/5.1/ref/models/fields/#datefield)

#### Admin
- [Model Admin Example](https://docs.djangoproject.com/en/5.1/ref/contrib/admin/#modeladmin-objects)
- [Model Inline](https://docs.djangoproject.com/en/5.1/ref/contrib/admin/#django.contrib.admin.StackedInline)
- [search_fields](https://docs.djangoproject.com/en/5.1/ref/contrib/admin/#django.contrib.admin.ModelAdmin.search_fields)
- [list_filter](https://docs.djangoproject.com/en/5.1/ref/contrib/admin/filters/#modeladmin-list-filters)
- [list_display](https://docs.djangoproject.com/en/5.1/ref/contrib/admin/#django.contrib.admin.ModelAdmin.list_display)

#### Views
- [ListView](https://docs.djangoproject.com/en/5.1/ref/class-based-views/generic-display/#listview)
- [DetailView](https://docs.djangoproject.com/en/5.1/ref/class-based-views/generic-display/#detailview)
- [CreateView](https://docs.djangoproject.com/en/5.1/ref/class-based-views/generic-editing/#django.views.generic.edit.CreateView.object)

#### Forms
- [Form example](https://docs.djangoproject.com/en/5.1/topics/class-based-views/generic-editing/#model-forms)
- [ModelChoiceField](https://docs.djangoproject.com/en/5.1/ref/forms/fields/#django.forms.ModelChoiceField)
- [RadioSelect](https://docs.djangoproject.com/en/5.1/ref/forms/widgets/#radioselect)
- [Form init example](https://docs.djangoproject.com/en/5.1/topics/forms/modelforms/#changing-the-queryset)

#### Templates
- [Templates examples](https://docs.djangoproject.com/en/5.1/ref/templates/language/)
- [Template tags](https://docs.djangoproject.com/en/5.1/ref/templates/language/#tags)

#### Testes
- [Django Test example](https://docs.djangoproject.com/en/5.1/topics/testing/overview/)
- [Comandos para executar testes](https://docs.djangoproject.com/en/5.1/topics/testing/overview/#running-tests)
- [Assertions](https://docs.djangoproject.com/en/5.1/topics/testing/tools/#assertions)
- [unittest Example](https://docs.python.org/3/library/unittest.html#basic-example)

#### Bootstrap
- [django-bootstrap5](https://pypi.org/project/django-bootstrap5/)
- [Base template exmaple](https://www.w3schools.com/django/django_add_bootstrap5.php)
- [List group](https://getbootstrap.com/docs/5.0/components/list-group/)
- [Cards](https://getbootstrap.com/docs/5.0/components/card/)
- [Buttons](https://getbootstrap.com/docs/5.0/components/buttons/)
- [Spacing](https://getbootstrap.com/docs/5.0/utilities/spacing/)
- [Alerts](https://getbootstrap.com/docs/5.0/components/alerts/)

#### CharJS
- [Getting Started](https://www.chartjs.org/docs/latest/getting-started/)
- [Pie Charts](https://www.chartjs.org/docs/latest/charts/doughnut.html#pie)
