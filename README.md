# Django Blog Project

This Django project was created following the [Django Girls](https://tutorial.djangogirls.org/en/django_start_project/) tutorial on building a blog posting website. It serves as a great starting point for anyone looking to learn Django and develop a simple yet functional blog.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have the following installed on your system:

- Python (version 3.6 or higher)
- Django

```bash
pip install django
```

### Installing

1. Clone the repository to your local machine:

```bash
git clone git@github.com:Pranav-001/Blogging-Website-Django.git
```

2. Change into the project directory:

```bash
cd django-blog
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

4. Activate the virtual environment:

   - On Windows:

   ```bash
   venv\Scripts\activate
   ```

   - On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

5. Install the project dependencies:

```bash
pip install -r requirements.txt
```

6. Apply migrations:

```bash
python manage.py migrate
```

7. Create a superuser account (admin) to manage the blog:

```bash
python manage.py createsuperuser
```

Follow the prompts to set a username, email, and password for the admin account.

8. Run the development server:

```bash
python manage.py runserver
```

The blog will be accessible at [http://127.0.0.1:8000/](http://127.0.0.1:8000/), and the admin interface can be accessed at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/).

## Usage

- Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the blog.
- Log in to the admin interface at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) to manage blog posts and users.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- [Django Girls](https://djangogirls.org/) for the excellent tutorial.
- The Django project team for creating such a powerful web framework.
- Open-source contributors who help make projects like this possible.

Happy coding! 🚀
