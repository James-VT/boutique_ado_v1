Alright, putting this here because you'll inevitably forget this stuff.

You made this project during a period that straddled several of Gitpod's regular meltdowns (sorry, "updates") and so its dependencies/requirements ended up completely borked. Every single time this workspace is re-opened/re-loaded, you need to add allauth and pillow back into it. If we end up adding any other dependencies later on, the same thing will probably have to happen with those. Pump these into the terminal:

pip3 install django-allauth==0.41.0

pip3 install pillow

pip3 install django-crispy-forms

pip3 install stripe

pip3 install django-countries

pip3 install dj_database_url

pip3 install psycopg2-binary

pip3 install gunicorn

pip3 install boto3

pip3 install django-storages

pip3 freeze > requirements.txt

---

Try to get some sleep.