# Set up

1. Create a new project using djangoadmin :

    ```bash
    django-admin startproject test_proj
    ```
2. Create and activate virtual environment
3. Install django
4. Start project using this template, ensuring to replace `test_proj` with the appropriate project name on the command below:

    ```bash
    django-admin startproject --template https://github.com/christinegatwiri/django_template/archive/refs/heads/main.zip test_proj .
    ```
5. Rename all the `.template` files by removing the `.template` extensions

6. Rename the `env` to `.env`

7. Populate the `.env` with real values

8. Setup your database, and run migrations.
