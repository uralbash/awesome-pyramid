Awesome Pyramid
===============

A curated list of awesome Pyramid apps, projects and resources. Inspired
by and based on
`awesome-python <https://github.com/vinta/awesome-python/>`__.

-  `Awesome Pyramid <#awesome-pyramid>`__

   -  `Admin Interface <#admin-interface>`__
   -  `Asset Management <#asset-management>`__
   -  `Async <#async>`__
   -  `Authentication <#authentication>`__
   -  `Authorization <#authorization>`__
   -  `Caching <#caching>`__
   -  `Debugging <#debugging>`__
   -  `Email <#email>`__
   -  `Forms <#forms>`__
   -  `Media-Management <#media-management>`__
   -  `RESTful API <#restful-api>`__
   -  `Search <#search>`__
   -  `Security <#security>`__
   -  `Settings <#settings>`__
   -  `Storage <#storage>`__
   -  `Task Queue <#task-queue>`__
   -  `Testing <#testing>`__
   -  `Translations <#translations>`__
   -  `Web frontend integration <#web-frontend-integration>`__
   -  `Workflows <#workflows>`__
   -  `Other <#other>`__

-  `Projects <#projects>`__

   -  `Framework <#framework>`__
   -  `CMS <#cms>`__
   -  `e-Commerce <#e-commerce>`__
   -  `Project Management <#project-management>`__
   -  `Other <#other>`__

-  `Contributing <#contributing>`__

Admin interface
---------------

*Packages that extend the Admin interface, adding or improving
features.*

-  `pyramid\_formalchemy <https://github.com/FormAlchemy/pyramid_formalchemy>`__
   - provides a CRUD interface for pyramid based on FormAlchemy.
-  `pyramid\_sacrud <https://github.com/ITCase/pyramid_sacrud>`__ -
   Pyramid CRUD interface based on sacrud and SQLAlchemy(that is closer
   to django.contrib.admin).

Asset Management
----------------

*Packages that help manage the static assets of a project.*

-  `pyramid\_webassets <https://github.com/sontek/pyramid_webassets>`__
   - Pyramid extension for working with the webassets library.
-  `pyramid\_bowerstatic <https://github.com/mrijken/pyramid_bowerstatic>`__
   - integration of Bowerstatic in Pyramid

Async
-----

-  `aiopyramid <https://github.com/housleyjk/aiopyramid>`__ - Run
   pyramid using asyncio.
-  `gevent-socketio <https://github.com/abourget/gevent-socketio>`__ -
   gevent-socketio is a Python implementation of the Socket.IO protocol,
   developed originally for Node.js by LearnBoost and then ported to
   other languages.

Authentication
--------------

*Packages that improve or extend the authentication methods of Pyramid.*

-  `pyramid\_ldap <https://github.com/Pylons/pyramid_ldap>`__ - an LDAP
   authentication policy for Pyramid.
-  `pyramid\_who <https://github.com/Pylons/pyramid_who>`__ -
   Authentication policy for pyramid using repoze.who 2.0 API.
-  `velruse <https://github.com/bbangert/velruse>`__ - Simplifying
   third-party authentication for web applications. it supports most of
   auth
   `providers <https://github.com/bbangert/velruse/tree/master/velruse/providers>`__.
-  `pyramid\_persona <https://github.com/madjar/pyramid_persona>`__ -
   Pyramid plugin to use `persona <https://login.persona.org/>`__ for
   authentication.

Authorization
-------------

*Packages related to authorization infrastructure and permissions.*

-  `ziggurat\_foundations <https://github.com/ergo/ziggurat_foundations>`__
   - Framework agnostic set of sqlalchemy classes that make building
   applications that require permissions an easy task.
-  `pyramid\_multiauth <https://github.com/mozilla-services/pyramid_multiauth>`__
   - An authentication policy for Pyramid that proxies to a stack of
   other authentication policies.
-  `horus <https://github.com/Pylons/horus>`__ - User registration and
   login system for the Pyramid Web Framework.

Caching
-------

*Packages that help with caching.*

-  `pyramid\_beaker <https://github.com/Pylons/pyramid_beaker>`__ - A
   Beaker session factory backend for Pyramid, also cache configurator.
-  `pyramid\_redis\_sessions <https://github.com/ericrasmussen/pyramid_redis_sessions>`__
   - Pyramid web framework session factory backed by Redis.
-  `pyramid\_dogpile\_cache <https://github.com/moriyoshi/pyramid_dogpile_cache>`__
   - dogpile.cache configuration package for Pyramid
-  `pyramid\_sessions <https://github.com/joulez/pyramid_sessions>`__ -
   Multiple session support for the Pyramid Web Framework

Debugging
---------

*Packages that help hunt down bugs.*

-  `pyramid\_debugtoolbar <https://github.com/Pylons/pyramid_debugtoolbar>`__
   - provides a debug toolbar useful while you're developing your
   Pyramid application.
-  `pyramid\_exclog <https://github.com/Pylons/pyramid_exclog>`__ - a
   package which logs exceptions from Pyramid applications.
-  `pyramid\_debugtoolbar\_dogpile <https://github.com/jvanasco/pyramid_debugtoolbar_dogpile>`__
   - dogpile caching support for pyramid\_debugtoolbar

Email
-----

*Packages that help manage email sending.*

-  `pyramid\_mailer <https://github.com/Pylons/pyramid_mailer>`__ - A
   package for sending email from your Pyramid application.
-  `pyramid\_marrowmailer <https://github.com/iElectric/pyramid_marrowmailer>`__
   - Pyramid integration package for marrow.mailer, formerly known as
   TurboMail

Forms
-----

*Packages that extend the functionality of forms or add new types of
forms.*

-  `deform <https://github.com/Pylons/deform>`__ - is a Python HTML form
   generation library.
-  `colander <https://github.com/Pylons/colander>`__ - A
   serialization/deserialization/validation library for strings,
   mappings and lists.
-  `WTForms <https://github.com/wtforms/wtforms>`__ - is a flexible
   forms validation and rendering library for python web development.
-  `ColanderAlchemy <https://github.com/stefanofontanelli/ColanderAlchemy>`__
   - helps you to auto-generate Colander schemas that are based on
   SQLAlchemy mapped classes.

Media-Management
----------------

-  `pyramid\_elfinder <https://github.com/ITCase/pyramid_elfinder>`__ -
   This is conector for elfinder file manager, written for pyramid
   framework.

RESTful API
-----------

*Packages for developing RESTful APIs.*

-  `cornice <https://github.com/mozilla-services/cornice>`__ - provides
   helpers to build & document REST-ish Web Services with Pyramid, with
   decent default behaviors. It takes care of following the HTTP
   specification in an automated way where possible.
-  `rest\_toolkit <https://github.com/wichert/rest_toolkit>`__ - is a
   Python package which provides a very convenient way to build REST
   servers. It is build on top of Pyramid, but you do not need to know
   much about Pyramid to use rest\_toolkit.
-  `pyramid\_royal <https://github.com/hadrien/pyramid_royal>`__ - Royal
   is a pyramid extension which eases writing RESTful web applications.

Search
------

*Packages that provide search capabilities to projects.*

-  `hypatia <https://github.com/Pylons/hypatia>`__ - A Python indexing
   and searching system.

Security
--------

*Packages that improve the security of a project.*

Settings
--------

*Packages that help manage the configurability of projects.*

-  `pyramid\_zcml <https://github.com/Pylons/pyramid_zcml>`__ - Zope
   Configuration Markup Language configuration support for Pyramid.

Storage
-------

*Packages that extend the functionality of the existing storage backend
or provide new storage backends.*

-  `pyramid\_sqlalchemy <https://github.com/wichert/pyramid_sqlalchemy>`__
   - provides some basic glue to facilitate using SQLAlchemy with
   Pyramid.
-  `pyramid\_zodbconn <https://github.com/Pylons/pyramid_zodbconn>`__ -
   ZODB Database connection management for Pyramid.
-  `pyramid\_mongoengine <https://github.com/marioidival/pyramid_mongoengine>`__
   - pyramid-mongoengine package based on flask-mongoengine

Task Queue
----------

*Packages that make working with task/background queues easier.*

-  `pyramid\_celery <https://github.com/sontek/pyramid_celery>`__ -
   Pyramid configuration with celery integration. Allows you to use
   pyramid .ini files to configure celery and have your pyramid
   configuration inside celery tasks.
-  `pyramid\_rq <https://github.com/wichert/pyramid_rq>`__ - Support
   using the rq queueing system with pyramid The easiest way to monitor
   and use `RQ <http://python-rq.org>`__ in your Pyramid projects.

Templates
---------

-  `pyramid\_mako <https://github.com/Pylons/pyramid_mako>`__ - Mako
   templating system bindings for the Pyramid web framework.
-  `pyramid\_chameleon <https://github.com/Pylons/pyramid_chameleon>`__
   - Chameleon template compiler for pyramid.
-  `pyramid\_jinja2 <https://github.com/Pylons/pyramid_jinja2>`__ -
   Jinja2 templating system bindings for the Pyramid web framework.

Testing
-------

*Packages that help test code or generate test data.*

-  `webtest <https://github.com/Pylons/webtest>`__ - Wraps any WSGI
   application and makes it easy to send test requests to that
   application, without starting up an HTTP server.

Translations
------------

*Packages help with the task of translating projects.*

Web frontend integration
------------------------

Workflows
---------

*Packages that do process, procedure and/or business tasks management.*

Other
-----

-  `pyramid\_layout <https://github.com/Pylons/pyramid_layout>`__ -
   Pyramid add-on for managing UI layouts.
-  `pyramid\_skins <https://github.com/Pylons/pyramid_skins>`__ - This
   package provides a simple framework to integrate code with templates
   and resources.
-  `waitress <https://github.com/Pylons/waitress>`__ - Waitress is meant
   to be a production-quality pure-Python WSGI server with very
   acceptable performance. It has no dependencies except ones which live
   in the Python standard library.
-  `pyramid\_handlers <https://github.com/Pylons/pyramid_handlers>`__ -
   analogue of Pylons-style “controllers” for Pyramid.
-  `pyramid\_rpc <https://github.com/Pylons/pyramid_rpc>`__ - RPC
   service add-on for Pyramid, supports XML-RPC in a more extensible
   manner than pyramid\_xmlrpc with support for JSON-RPC and AMF.
-  `pyramid\_autodoc <https://github.com/SurveyMonkey/pyramid_autodoc>`__
   - Sphinx extension for documenting your Pyramid APIs.
-  `pyramid\_tm <https://github.com/Pylons/pyramid_tm>`__ - Centralized
   transaction management for Pyramid applications (without middleware).
-  `paginate <https://github.com/Pylons/paginate>`__ - Python pagination
   module.
-  `pyramid\_tablib <https://github.com/lxneng/pyramid_tablib>`__ -
   tablib renderer (xlsx, xls, csv) for pyramid
-  `pyramid\_sacrud\_pages <https://github.com/ITCase/pyramid_sacrud_pages>`__
   - Provides a collections of tree pages to your Pyramid application.
-  `tomb\_routes <https://github.com/sontek/tomb_routes>`__ - Simple
   utility library around pyramid routing

Projects
========

*Outstanding Pyramid projects.*

Framework
---------

-  `Ringo <http://ringo-dev.intevation.de/>`__ - Ringo is a Python based
   high level web application framework build on top of Pyramid. The
   framework can be used to build form based management or
   administration software.

CMS
---

-  `nive\_cms <https://github.com/nive/nive_cms>`__ - Nive is
   professional out the box content management system for mobile and
   desktop websites based on python and the webframework pyramid. Please
   refer to the website cms.nive.co for detailed information.
-  `substanced <https://github.com/Pylons/substanced>`__ - An
   application server built upon the Pyramid web framework. It provides
   a user interface for managing content as well as libraries and
   utilities which make it easy to create applications.
-  `Kotti <https://github.com/Kotti/Kotti>`__ - A user-friendly,
   light-weight and extensible web content management system. Based on
   Pyramid and SQLAlchemy.
-  `KARL <http://karlproject.org/>`__ - A moderately-sized application
   (roughly 80K lines of Python code) built on top of Pyramid. It is an
   open source web system for collaboration, organizational intranets,
   and knowledge management. It provides facilities for wikis,
   calendars, manuals, searching, tagging, commenting, and file uploads.
   See the KARL site for download and installation details.

e-Commerce
----------

Project Management
------------------

Other
-----

-  `cluegun <https://github.com/Pylons/cluegun>`__ - A simple pastebin
   application based on Rocky Burt’s ClueBin. It demonstrates form
   processing, security, and the use of ZODB within a Pyramid
   application.
-  `shootout <https://github.com/Pylons/shootout.git>`__ - An example
   “idea competition” application by Carlos de la Guardia and Lukasz
   Fidosz. It demonstrates URL dispatch, simple authentication,
   integration with SQLAlchemy and pyramid\_simpleform.
-  `virginia <https://github.com/Pylons/virginia.git>`__ - A very simple
   dynamic file rendering application. It is willing to render
   structured text documents, HTML documents, and images from a
   filesystem directory. It’s also a good example of traversal. An
   earlier version of this application runs the repoze.org website.
-  `Akhet <http://docs.pylonsproject.org/projects/akhet/en/latest/>`__ -
   A Pyramid library and demo application with a Pylons-like feel. Its
   most known for its former application scaffold, which helped users
   transition from Pylons and those preferring a more Pylons-like API.
   The scaffold has been retired but the demo plays a similar role.
-  `Khufu Project <http://khufuproject.github.com/>`__ - Khufu is an
   application scaffolding for Pyramid that provides an environment to
   work with Jinja2 and SQLAlchemy.
-  `Ptah <https://github.com/ptahproject/ptah>`__ - Ptah is a fast, fun,
   open source high-level Python web development environment.
-  `pyramid\_sacrud\_example <https://github.com/ITCase/pyramid_sacrud_example>`__
   - Demo app for pyramid extension of sacrud

Contributing
============

Just fork and send a pull request with your awesome Pyramid apps,
projects or resources.
