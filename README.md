**Mozilla Azerbaijan**

Mozillaz.org website

Written using Python Django and mezzanine


**How to run in local**:

1. Clone repository to somewhere in your computer
2. Install requirements: `pip install -r requirements.txt`
3. Run: `python manage.py runserver`
4. Manage settings using `local_settings.py`
5. Deploy: `fab deploy`

**Localization**:

*Making messages ready for translation:

`django-admin.py makemessages -l az -a`

*Compiling messages to .mo files:

`django-admin.py compilemessages`


**TODO**:

List of basic todos. For issues and suggestions check issues page in Github.

1. Slider is not customizable, need to move it to admin.
2. (done) Disable 'Accept-Language', so that 'az' will be default for all.
3. (done) Make support for 'en' local (through selecting or direct url) for foreign visitors.
4. (done) Footer is not displayed correctly in mobile resolution.
5. Dropdown menu design is not good (look: Haqqımızda > Komanda).
6. Recent blog posts in homepage need some work, currently there is only 1 item. (3 posts for every item)
7. Disable mobile version


**Read CHANGELOG.md for Changes!**


[![Analytics](https://ga-beacon.appspot.com/UA-36541010-2/mozillazorg/)](http://www.mozillaz.org)