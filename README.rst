Base development environment
==============================

:Author:
   Érico Andrei <erico@simplesconsultoria.com.br>

::

    git clone git@github.com:simplesconsultoria/buildout.development.git
    source my_python_env/bin/activate
    python bootstrap.py

    ./bin/buildout -Nvvv -t 50
    

This buildout is a base development environment, provides functionalities for doing things like:


  *  Create a Sphinx documentation for a infrastructure project.
  *  Create a Sphinx documentation for a project.
  *  A Plone package template for Simples Consultoria's projects
  *  A policy package following the Simples Consultoria standards
  *  A basic buildout skeleton
  *  A recipe project for zc.buildout
  *  A basic Python project with a namespace package
  *  A basic Python project with a nested namespace (2 dots in name)
  *  Create a simple buildout
  *  Create a frontend buildout with Nginx, Varnish and Repoze
  *  Create a Plone buildout
  *  A Plone project that uses Archetypes content types
  *  A project for Plone products
  *  Create a Diazo theme based on beyondskins.responsive.
  *  A theme package following the Simples Consultoria standards
  *  A Zope project
  *  Nested namespace template for Simples Consultoria's packages


Example::

  ./bin/templer theme_diazo s17.theme
