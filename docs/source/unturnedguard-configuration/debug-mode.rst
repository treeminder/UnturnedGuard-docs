DebugMode
==========


.. admonition:: **Understanding DebugMode**
   :class: seealso

   **DebugMode** is a crucial configuration parameter provided by UnturnedGuard, designed to manage detailed information in logs.

Overview
********

**DebugMode** is specifically designed for testing. It enables additional logging in the console and provides useful information for UnturnedGuard developers. Do not change this option unless instructed by developers.


**Configuration**
***************

.. admonition:: **Configuration**
   :class: important

   Configuring **DebugMode** in UnturnedGuard is straightforward. You have two options to set DebugMode:

   - ``true`` (to enable this option)
   - ``false`` (to disable this option)

   **For RocketMod Configuration (UnturnedGuard.RocketMod.configuration.xml):**

   .. code-block:: xml

       <DebugMode>false</DebugMode>

   **For OpenMod Configuration (config.yaml):**

   .. code-block:: yaml

       DebugMode: false

