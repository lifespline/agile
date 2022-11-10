.. raw:: html

   <a href="https://github.com/lifespline/agile.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork me on GitHub" data-recalc-dims="1"></a>

=============
The Manifesto
=============

Main Flow
---------

The main flow is the sequential iteration of the states ``sleep``, ``morning-preparation``, :ref:`engage-flow <engage_flow>`, ``evening-preparation``.

.. image:: ../../static/img/main-flow.png
    :width: 400
    :alt: Main Flow

.. _engage_flow:

Engage Flow
-----------

The ``engage-flow`` starts by ``envisioning`` what to engage with. This can be achieved by consulting with the `backlog network graph <https://www.duckduckgo.com>`_ (for **context**), the `backlog <https://github.com/orgs/lifespline/projects/2>`_ (for **details**) and the `schedule <https://www.duckduckgo.com>`_ (for **scheduled milestones**). Knowing what to engage with, proceed engaged in full focus. The occurring subtasks (0.8 of them) must be logged as samples ``lifespline/samples-*`` so that they can be practiced upon later. Keep track of the subtasks on the `ipad notes <https://www.duckduckgo.com>`_ (to prevent loss of **context**). When the task is finished, you must to through the states of ``envision``, ``structure``, ``reduce`` and ``schedule`` *TODO*. When these states have been finished, one iteration has been completed, and the new ``engaged`` iteration can commence.

.. image:: ../../static/img/engage-flow.png
    :width: 400
    :alt: Engage Flow

.. _versioning_and_control_flow:

Versioning and Control Flow
---------------------------

.. image:: ../../static/img/versioning-and-control-flow.png
    :width: 400
    :alt: Versioning and Control Flow



Reducing From Imaginary To Real
-------------------------------

.. image:: ../../static/img/realization-flow.png
    :width: 400
    :alt: Realization Flow

.. image:: ../../static/img/scheduled-realization-flow.png
    :width: 400
    :alt: Scheduled realization flow

.. image:: ../../static/img/reduction-and-scheduling.png
    :width: 400
    :alt: Scheduled realization flow

Group And Individual Productivity Variation
-------------------------------------------

.. image:: ../../static/img/variation-group-individual.png
    :width: 400
    :alt: Realization Flow

.. _problem_analysis_flow:

Problem Analysis Flow
---------------------

The ``problem-analysis-flow`` is understanding a problem statement before beginning the development of a solution. This step is very important because often the problem statement requires iterations of analysis before the problem statement is specified sufficiently in order to be tackled.

.. image:: ../../static/img/problem-analysis-flow.png
    :width: 400
    :alt: Problem Analysis Flow

.. _backlog:

Backlog
~~~~~~~

Track the ``item``.

.. _prob_statement:

Problem Statement
~~~~~~~~~~~~~~~~~

Add problem statement, or *that which seems to best describe* the ``item``, without having any consideration about what might solve the problem. The problem statement is a set of problem statements. Each set maps to a ``product feature``. The problem statement maps to a ``product`` that satisfies the problem statement.

.. _prob_analysis:

Problem/Solution Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~

Analyse the problem from within the framework of a possible solution (we assume **a problem can only be analysed from whithin the framework of a possible solution**). The analysis outputs problem statement behaviours that satisfy the problem statements.

.. _behaviour:

Behaviour
~~~~~~~~~

Discuss what defines a behaviour that provides a solution to the :ref:`problem statements <prob_statement>`. This typically requires that the problem statement translates to **behaviour requirements** in the :ref:`problem analysis <prob_analysis>`. These requirements are **behaviours** that the solution must show. The requirements should also include **behaviour verification tests**. The behaviours and the behaviour verification tests should be written in a mid-level language for automation purposes.

Typically the behaviours aren't all necessary, some of them are nice-to-haves, it's crucial to identify which behaviours are closest to the problem statement so that the **value throughput** is always high.

When you're specifying the problem statements behaviours, iterate through the specification and remove/move behaviours that don't map to the problem statement specifically. Each problem statement maps to a ``product feature`` and each behaviour maps to a ``product feature behaviour`` or a ``user story``.

Having finalised all the problem statements' behaviours it is possible to analyse the :ref:`architecture for a tecnhical solution <architecture>`.

.. _architecture:

Architecture
~~~~~~~~~~~~

Having finalised all the problem statements' behaviours it is possible to analyse the architecture for a tecnhical solution.