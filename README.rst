==========================
Zen Coding Django Snippets
==========================
Overview
--------

This is a set of snippets for
`Eclipse Zen Coding plugin <https://github.com/sergeche/eclipse-zencoding>`_ to use in Django
templates. At the moment it includes snippets for all standard Django templates tags.

Installation
------------

#. Make sure that `Eclipse Zen Coding plugin <https://github.com/sergeche/eclipse-zencoding>`_
   is installed and working.
#. Download the `zen-django.xml <https://github.com/andreyfedoseev/zen-coding-django-snippets/raw/master/zen-django.xml>`_
   file.
#. Open Eclipse preferences and go to *Zen Coding → Snippets*. 
#. Click *Import...* button and select the *zen-django.xml*.
#. That's it, you can use the snippets now.

Snippets list
-------------
=============== ============================================
 Abbreviation                        Tag
=============== ============================================
 autoescape      ``{% autoescape %} {% autoescape %}``
 block           ``{% block %} {% endblock %}``
 comment         ``{% comment %} {% endcomment %}``
 csrf            ``{% csrf_token %}``
 csrf_token      ``{% csrf_token %}``
 cycle           ``{% cycle %}``
 debug           ``{% debug %}``
 ext             ``{% extends "" %}``
 extends         ``{% extends "" %}``
 filter          ``{% filter %} {% endfilter %}``
 firstof         ``{% firstof %}``
 for             ``{% for in %} {% endfor %}``
 fore            ``{% for in %} {% empty %} {% endfor %}``
 if              ``{% if %} {% endif %}``
 ifchanged       ``{% ifchanged %} {% endifchanged %}``
 ife             ``{% if %} {% else %} {% endif %}``
 ifelse          ``{% if %} {% else %} {% endif %}``
 ifeq            ``{% ifequal %} {% endifequal %}``
 ifequal         ``{% ifequal %} {% endifequal %}``
 ifnotequal      ``{% ifnotequal %} {% endifnotequal %}``
 inc             ``{% include %}``
 include         ``{% include %}``
 load            ``{% load %}``
 now             ``{% now "" %}``
 regroup         ``{% regroup by as %}``
 spaceless       ``{% spaceless %} {% endspaceless %}``
 ssi             ``{% ssi %}``
 templatetag     ``{% templatetag %}``
 url             ``{% url %}``
 widthratio      ``{% widthratio %}``
 with            ``{% with as %} {% endwith %}``
=============== ============================================

Hints
-----

You can use some of these snippets to wrap a text fragment with a tag. To do that select the text
and choose *Wrap With Abbreviation...* from *Zen Coding* menu. This works for tags which have an
ending tag, like ``{% if %} {% endif %}``.

You can use the *Tab* key to move the cursor to next logical position. For example use the ``for``
snippet and hit *Tab* to see how the cursor moves.