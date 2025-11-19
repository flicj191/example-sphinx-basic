Usage
=====

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']



Some kind of other text to give more information.
So let's cook, everything is a recipe and cookbok based analogy. Generally eeveryone eats.
People must always have food on their minds. 
See `this example`_ for more details.

.. _this example:https://mykitchen101en.com/pandan-rice-cooker-sponge-cake/

Or Here is `a link <http://www.examplenot.com>`_ to somewhere.