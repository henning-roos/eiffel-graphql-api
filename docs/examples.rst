========
Examples
========

Initialize terminal
-------------------

.. code-block:: bash

    export RABBITMQ_HOST=
    export RABBITMQ_EXCHANGE=
    export RABBITMQ_USERNAME=
    export RABBITMQ_PASSWORD=
    export RABBITMQ_PORT=
    export RABBITMQ_VHOST=
    export RABBITMQ_QUEUE=
    export MONGODB_HOST=
    export MONGODB_PORT=
    export MONGODB_USERNAME=
    export MONGODB_PASSWORD=
    export MONGODB_REPLICASET=
    export DATABASE_NAME=

Start DB storage (development)
------------------------------

.. code-block:: bash

    python -m eiffel_graphql_api.storage

Start DB storage (docker)
-------------------------

.. code-block:: bash

    # TBD

Start API (development server)
------------------------------

.. code-block:: bash

    ./entry_debug

Start API (docker)
------------------

.. code-block:: bash

    TBD

Run tests
---------

.. code-block:: bash

    tox
