# django-nice-form-fields
Django forms custom imagefield that dynamically renders the loaded image.
<h1>Installation:</h1>
1.pip install django-nice-form-fields
<br>
2. Add 'django-nice-form-fields' to installed apps in settings.py.
<br>
<h1>Example:</h1>
.. code:: python

      from django import forms
      from django_nice_form_fields.fields import DynamicImageField

      class MyForm(forms.Form):

          photo = DynamicImageField(label='Photo', choose_image_text='Choose photo', change_image_text='Change photo')
