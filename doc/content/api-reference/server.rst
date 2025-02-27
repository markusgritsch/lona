is_template: False
search_index_weight: 15


Server
------

Server.get_running_views_count()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.get_running_views_count


Server.view_is_already_running()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.view_is_already_running


Server.get_connection_count()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.get_connection_count


Server.get_connected_user_count()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.get_connected_user_count


Server.get_template()
~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.get_template


Server.render_string()
~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.render_string


Server.render_template()
~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.render_template


Server.get_view_class()
~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.get_view_class


Server.get_views()
~~~~~~~~~~~~~~~~~~

    .. note::

        Added in 1.9

    .. api-doc:: lona.server.Server.get_views


Server.reverse()
~~~~~~~~~~~~~~~~

    .. note::

        The argument ``name`` was renamed to ``route_name`` in 1.8

    .. api-doc:: lona.server.Server.reverse


Server.fire_view_event()
~~~~~~~~~~~~~~~~~~~~~~~~

    .. note::

        Added in 1.7.3

    .. api-doc:: lona.server.Server.fire_view_event


Server.run_coroutine_sync()
~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.run_coroutine_sync


Server.run_function_async()
~~~~~~~~~~~~~~~~~~~~~~~~~~~

    .. api-doc:: lona.server.Server.run_function_async


Server.embed_shell\(\)
~~~~~~~~~~~~~~~~~~~~~~

    .. note::

        Removed in 1.8. Use rlpython directly instead.

        .. code-block:: python

            import rlpython
            rlpython.embed()

    Embeds a `rlpython <https://pypi.org/project/rlpython/>`_ based shell in
    the server context.
    More info on shells:
    `Debugging </api-reference/debugging.html>`_.
