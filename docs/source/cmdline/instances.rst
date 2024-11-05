:program:`dandi instances`
==========================

::

    dandi [<global options>] instances

List known Dandi Archive instances that can be passed to the
``-i``/``--dandi-instance`` option of other subcommands for the CLI to
interact with.  Output is in YAML.

Example output:

.. code:: yaml

    dandi:
      api: https://api.dandiarchive.org/api
      gui: https://gui.dandiarchive.org
    dandi-api-local-docker-tests:
      api: http://localhost:8000/api
      gui: http://localhost:8085
    dandi-staging:
      api: https://api-staging.dandiarchive.org/api
      gui: https://gui-staging.dandiarchive.org
    linc-staging:
      api: https://staging-api.lincbrain.org/api
      gui: https://staging.lincbrain.org
    linc:
      api: https://api.lincbrain.org/api
      gui: https://lincbrain.org
