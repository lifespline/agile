.. raw:: html

   <a href="https://github.com/lifespline/agile.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork me on GitHub" data-recalc-dims="1"></a>

=========================
Problem/Solution Analysis
=========================

If the :ref:`problem statement <prob_statement>` consists of multiple problem statements, **there is some underlying problem that can be analyzed from within the framework of a possible solution to all the problem statements** (we assume a problem can only be analyzed from within the framework of a possible solution). The analysis outputs a generic solution that will satisfy all the problem statement.

.. code-block:: rst

   Problem Statement
   ┣╸ <Problem Statement 1>
   ┣╸ ...
   ┗╸ <Problem Statement M>

.. note::

    It's important to try to discuss a solution to all the problem statements so that each problem statement is treated as an instantiation of a generic problem.

.. note::

    The solution **MUST NOT** be technical but merely conceptual. The problem statement exists only in the conceptual level (e.g.: a network graph to map a backlog is a concept, rendering the network graph with a pyhon lib in a jupyter notebook is a technical detail).
