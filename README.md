# [Datta Able](https://appseed.us/generator/datta-able/) Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Datta Able](https://appseed.us/generator/datta-able/)** a modern Bootstrap design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

<br />

> 🚀 Built with [Datta Able Generator](https://appseed.us/generator/datta-able/), timestamp `2022-06-25 18:07`

- 👉 [Datta Able Flask](https://appseed.us/product/datta-able/flask/) - `Product page`
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`
- ✅ [PRO Version Available](#pro-version) - `enhanced UI` and more `features` 
  
<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Datta Able - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168842521-ec98ecd5-489c-4a13-a9aa-0d47201d63de.png)

<br />



## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/224b115c-9da4-49ab-988a-efc03b6441fc.git
$ cd 224b115c-9da4-49ab-988a-efc03b6441fc
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like bold elements and beautiful websites, **Datta Able** is the most stylish Bootstrap 4 Admin Template compare to all other Bootstrap admin templates. It comes with high feature-rich pages and components with fully developer-centric code. 

- 👉 [Flask Datta PRO](https://appseed.us/product/datta-able-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Datta Able PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/170474361-a58da82b-fff9-4a59-81a8-7ab99f478f48.png)

<br />

---
[Datta Able](https://appseed.us/generator/datta-able/) Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
