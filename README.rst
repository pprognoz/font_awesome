Installation
============

Add font_awesome to static files

{% addtoblock "css" %}
        <link href="/static/font-awesome/scss/fontawesome.scss" rel="stylesheet" type="text/x-scss"/>
{% endaddtoblock %}

::

    git+https://github.com/useHTML5/font_awesome.git@0.1#egg=font_awesome # галерея


    INSTALLED_APPS = [
    // ...
    'font_awesome', # self font_awesome
    // ...


..
