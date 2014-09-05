# Awesome Pyramid

A curated list of awesome Pyramid apps, projects and resources. Inspired by and based on [awesome-python](https://github.com/vinta/awesome-python/).

- [Awesome Pyramid](#awesome-pyramid)
    - [Admin Interface](#admin-interface)
    - [Asset Management](#asset-management)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Caching](#caching)
    - [Debugging](#debugging)
    - [Email](#email)
    - [Fields](#fields)
    - [File Transfers](#file-transfers)
    - [Forms](#forms)
    - [Migrations](#migrations)
    - [Model Extensions](#model-extensions)
    - [Project Management](#project-management)
    - [RESTful API](#restful-api)
    - [Search](#search)
    - [Security](#security)
    - [Settings](#settings)
    - [Storage](#storage)
    - [Task Queue](#task-queue)
    - [Testing](#testing)
    - [Thumbnail](#thumbnail)
    - [Cropping Images](#cropping-image)
    - [Translations](#translations)
    - [Web frontend integration](#web-frontend-integration)
    - [Workflows](#workflows)
    - [Other](#other)
- [Projects](#projects)
    - [CMS](#cms)
    - [e-Commerce](#e-commerce)
    - [Project Management](#project-management)
    - [Other](#other)
- [Resources](#resources)
    - [Books](#books)
    - [Websites](#websites)
    - [Conferences](#conferences)
    - [Videos](#videos)
- [Contributing](#contributing)




## Admin interface

*Packages that extend the Admin interface, adding or improving features.*

* [pyramid_formalchemy](https://github.com/FormAlchemy/pyramid_formalchemy) - provides a CRUD interface for pyramid based on FormAlchemy.
* [pyramid_sacrud](https://github.com/ITCase/pyramid_sacrud) - Pyramid CRUD interface based on sacrud and SQLAlchemy(that is closer to django.contrib.admin).

## Asset Management

*Packages that help manage the static assets of a project.*

* [pyramid_webassets](https://github.com/sontek/pyramid_webassets) - Pyramid extension for working with the webassets library.

## Authentication

*Packages that improve or extend the authentication methods of Pyramid.*

## Authorization

*Packages related to authorization infrastructure and permissions.*

* [ziggurat_foundations](https://github.com/ergo/ziggurat_foundations) - Framework agnostic set of sqlalchemy classes that make building applications that require permissions an easy task.
* [pyramid_multiauth](https://github.com/mozilla-services/pyramid_multiauth) - An authentication policy for Pyramid that proxies to a stack of other authentication policies.
* [horus](https://github.com/Pylons/horus) - User registration and login system for the Pyramid Web Framework.

## Caching

*Packages that help with caching.*

* [pyramid_beaker](https://github.com/Pylons/pyramid_beaker) - A Beaker session factory backend for Pyramid, also cache configurator.

## Debugging

*Packages that help hunt down bugs.*

* [pyramid_debugtoolbar](https://github.com/Pylons/pyramid_debugtoolbar) - provides a debug toolbar useful while you're developing your Pyramid application.

## Email

*Packages that help manage email sending.*

* [pyramid_mailer](https://github.com/Pylons/pyramid_mailer) - A package for sending email from your Pyramid application.

## Fields

*Packages that extend the functionality of existing field type or add new field types.*

## File Transfers

*Packages that help transfer files between projects and users*

## Forms

*Packages that extend the functionality of forms or add new types of forms.*

* [deform](https://github.com/Pylons/deform) - is a Python HTML form generation library.
* [colander](https://github.com/Pylons/colander) - A serialization/deserialization/validation library for strings, mappings and lists.

## RESTful API

*Packages for developing RESTful APIs.*

* [cornice](https://github.com/mozilla-services/cornice) - provides helpers to build & document REST-ish Web Services with Pyramid, with decent default behaviors. It takes care of following the HTTP specification in an automated way where possible.

## Migrations

*Packages that help migrate the database when there are schema updates.*

## Model Extensions

*Packages that extend the functionality of models or add new classes of models.*

## Project Management

## Search

*Packages that provide search capabilities to projects.*

* [hypatia](https://github.com/Pylons/hypatia) - A Python indexing and searching system.

## Security

*Packages that improve the security of a project.*

## Settings

*Packages that help manage the configurability of projects.*

## Storage

*Packages that extend the functionality of the existing storage backend or provide new storage backends.*

* [pyramid_sqlalchemy](https://github.com/wichert/pyramid_sqlalchemy) - provides some basic glue to facilitate using SQLAlchemy with Pyramid.

## Task Queue

*Packages that make working with task/background queues easier.*

* [pyramid_celery](https://github.com/sontek/pyramid_celery) - Pyramid configuration with celery integration. Allows you to use pyramid .ini files to configure celery and have your pyramid configuration inside celery tasks.
* [pyramid_rq](https://github.com/wichert/pyramid_rq) - Support using the rq queueing system with pyramid
The easiest way to monitor and use [RQ](http://python-rq.org) in your Pyramid projects.

## Templates

* [pyramid_mako](https://github.com/Pylons/pyramid_mako) - Mako templating system bindings for the Pyramid web framework.
* [pyramid_chameleon](https://github.com/Pylons/pyramid_chameleon) - Chameleon template compiler for pyramid.
* [pyramid_jinja2](https://github.com/Pylons/pyramid_jinja2) - Jinja2 templating system bindings for the Pyramid web framework.

## Testing

*Packages that help test code or generate test data.*

## Thumbnail

*Packages that help generate thumbnails.*

## Cropping Image

*Packages that help to crop Images.*

## Translations

*Packages help with the task of translating projects.*

## Web frontend integration

## Workflows

*Packages that do process, procedure and/or business tasks management.*

## Other

* [pyramid_layout](https://github.com/Pylons/pyramid_layout) - Pyramid add-on for managing UI layouts.
* [pyramid_skins](https://github.com/Pylons/pyramid_skins) - This package provides a simple framework to integrate code with templates and resources.
* [waitress](https://github.com/Pylons/waitress) - Waitress is meant to be a production-quality pure-Python WSGI server with very acceptable performance. It has no dependencies except ones which live in the Python standard library.

# Projects

*Outstanding Pyramid projects.*

## CMS

* [nive_cms](https://github.com/nive/nive_cms) - Nive is professional out the box content management system for mobile and desktop websites based on python and the webframework pyramid. Please refer to the website cms.nive.co for detailed information.
* [substanced](https://github.com/Pylons/substanced) - An application server built upon the Pyramid web framework. It provides a user interface for managing content as well as libraries and utilities which make it easy to create applications.
* [Kotti](https://github.com/Kotti/Kotti) - A user-friendly, light-weight and extensible web content management system. Based on Pyramid and SQLAlchemy.

## e-Commerce

## Other

## Project Management

# Resources

Where to discover new Pyramid apps and projects.

## Books

## Websites

* [Try Pyramid](http://trypyramid.com/) - Pyramid is easy to set up and use.
* [Pyramid site](http://www.pylonsproject.org/projects/pyramid/about) official site of Pyramid.

## Conferences


## Videos


# Contributing

[Contributing](http://docs.pylonsproject.org/en/latest/#contributing)