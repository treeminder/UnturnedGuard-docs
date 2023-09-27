Is Moderation2 Supported?
=========================

UnturnedGuard offers built-in support for Moderation2, a powerful moderation plugin. By default, this integration is disabled to give you control over your configuration.

.. admonition:: **Moderation2 Integration**

    **For RocketMod** ``UnturnedGuard.RocketMod.configuration.xml:``

    In your plugin configuration file, locate the following setting and set it to true:

    .. code-block:: xml

        <Moderation2Integration>true</Moderation2Integration>

    **For OpenMod** ``config.yaml:``

    In your OpenMod configuration file, set the following option to true:

    .. code-block:: yaml

        Moderation2Integration: true

    Once you've made this change, remember to reload your plugin or restart the server.

    With Moderation2 support enabled, you can boost your server's moderation capabilities.