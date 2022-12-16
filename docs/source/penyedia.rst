Penyedia
=====

.. _installation:

Pendaftaran
------------

Untuk menjadi penyedia layanan K3 dalam aplikasi ini anda harus memiliki akun wasnaker.id:

.. code-block:: console

   (.venv) $ pip install lumache

Profil
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

