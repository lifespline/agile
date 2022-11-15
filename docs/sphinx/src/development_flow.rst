.. raw:: html

   <a href="https://github.com/lifespline/agile.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork me on GitHub" data-recalc-dims="1"></a>

================
Development Flow
================

The sections below show the ``lifespline/agile`` development flow.

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   development_flow/home
   development_flow/backlog
   development_flow/problem_analysis
   development_flow/architecture_analysis
   development_flow/development

.. _technical_requirements:

Technical Requirements
~~~~~~~~~~~~~~~~~~~~~~

Gather information from all the **behaviour** and **behaviour test specifications** from all the **problem statements** and consider the **technical requirements** of these specifications, establishing a correspondence (TODO: automate this process).

.. note::

    The specificity of the **technical requirements** is a function of the specificity of the **behaviour specifications**, *i.e.*, the **technical requirements** are to be abstracted as much as possible from their implementation.

    *Example*: If the **behaviour specification** suggests that the data layer will hold different file types, then the **technical requirement** should detail a technology that accommodates for different file types, otherwise it should abstain from specifying the data persistency technology.

.. note::

    The technical requirements hierarchy establish a correspondence between the technical requirements and the behaviour. It's important to visualize which technical requirements satisfy behaviour satisfy which problem statement, and which technical requirements satisfy which behaviours, *etc.*, all the way down to **who wrote which line of code when: 100% transparency**.

.. _architecture_components:

Architecture Components
~~~~~~~~~~~~~~~~~~~~~~~

Gather information from all the **technical requirements** and consider the **architecture components** that answer all of them, establishing a correspondence (TODO: automate this process).

.. note::

    The specificity of the **technical requirements** is a function of the specificity of the **behaviour specifications**, *i.e.*, the **technical requirements** are to be abstracted as much as possible from their implementation.

    *Example*: If the **behaviour specification** suggests that the data layer will hold different file types, then the **technical requirement** should detail a technology that accommodates for different file types, otherwise it should abstain from specifying the data persistency technology.

.. _architecture_technologies:

Architecture Technologies
~~~~~~~~~~~~~~~~~~~~~~~~~
