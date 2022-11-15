.. raw:: html

   <a href="https://github.com/lifespline/agile.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork me on GitHub" data-recalc-dims="1"></a>

==================
Behaviour Analysis
==================

With the conceptual solution from the problem analysis, specify the behaviours that will satisfy each problem statement.

.. code-block:: rst

   Behaviours: <Problem Statement 1>
   ┃
   ┣╸ BEHAVIOUR 1
   ┃  ┃
   ┃  ┣╸SPEC
   ┃  ┗╸TEST SPEC
   ┣╸ ...
   ┗╸ BEHAVIOUR N
      ┃
      ┣╸SPEC
      ┗╸TEST SPEC

   ...

   Behaviours: <Problem Statement M>
   ┃
   ┣╸ BEHAVIOUR N + 1
   ┃  ┃
   ┃  ┣╸SPEC
   ┃  ┗╸TEST SPEC
   ┣╸ ...
   ┗╸ BEHAVIOUR P
      ┃
      ┣╸SPEC
      ┗╸TEST SPEC

The problem statement maps to **behaviour specifications** and the corresponding **behaviour verification tests**. The behaviours and the behaviour verification tests should be written in a mid-level language for automation purposes. These tests are not to be mistaken with the implementation unit tests, these are behavioural tests and specify what the behaviour must guarantee.

Typically the behaviour specifications aren't all necessary, it's crucial to identify which behaviours are closest to the problem statement so that the **value throughput** is always high. Add the unnecessary behaviour specs to tackle them at a later point in time.

Each problem statement maps to a ``product feature`` and each behaviour maps to a ``product feature behaviour`` or a ``user story``.

.. note::

    It's important to **finish the behaviour and behaviour test specifications for all the problem statements (features)** before starting to think of the architecture for the overall solution. This approach protects from having to redesign the architecture from feature to feature (as these may vary in what they require from the architecture).
    
    This is nevertheless bound to happen, the approach simply tries to minimize it and maximizing value throughput.

.. note::

    The behaviours hierarchy establish a correspondence between the behaviour and the problem statement. It's important to visualize which behaviour satisfy which problem statement, and which technical requirements satisfy which behaviours, *etc.*, all the way down to **who wrote which line of code when: 100% transparency**.

    TODO: automate
