Flask-Injector Changelog
========================

Version 0.6.0
-------------

* Added support for injecting into Flask-RESTFul Resource constructors

Version 0.5.0
-------------

* Removed ``init_app`` and ``post_init_app`` functions
* Fixed a bug with Flask-Injector modifying possibly shared view generated by View.as_view
  (see GH issue #6, test case provided by Nicholas Hollett)
* Work only with Injector >= 0.9.0 now

Version 0.4.0
-------------

* Deprecated ``init_app`` and ``post_init_app`` in favour of ``FlaskInjector``
* Made Flask error handlers support injection

Version 0.3.4
-------------

* Made it possible to inject into Jinja template globals

Version 0.3.3
-------------

* Accomodated to Injector >= 0.9.0
