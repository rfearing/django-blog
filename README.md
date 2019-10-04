# Ricardo's Blog Project

### Choices

* Style Guide: (PEP 80)[https://pep8.org/]
* Python Version 3.7.4 (using virtual env)
* Sass
	* To utilize, run `sass --watch .:.` to compile CSS
* Use a requirements.txt to install requirements for future devs (potentially replaced with `pipenv` down the line)
	* To utilize, run `pip install -r requirements.txt`

### Tutorials Viewed for this Project:

* https://docs.djangoproject.com/en/2.2/intro/
* https://www.youtube.com/watch?v=jFCNu1-Xdsw
* https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p


### Optional things to do next:
* Add another app within the Django Project
* Implement Auth0
* Pagination
* Image Upload
* WYSIWYG
* Create REST API from Blog App


### Things to look into next:
* pipenv vs Poetry vs Conda

pipenv
> pipenv is a wrapper around pip that also creates and manages your virtual environments. It has similarities to conda.

conda
> if you’re using python for data science and all the things you plan on installing are in conda its pretty good, particularly for installing really complicated dependencies with lots of random binaries

### Tools

* Bootstrap with crispy-forms (to generate Bootstrap forms)
* Pillow for images

### Notes

**Migrations:**

Make Migration `python manage.py makemigrations` <br />
Run Migration `python manage.py migrate` <br />
Register Modal in Admin `/users/admin.py`
