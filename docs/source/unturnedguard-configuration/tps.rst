TPS
===

.. admonition:: **Understanding TPS**
   :class: seealso

   **TPS**, short for **Ticks Per Second**, is a critical configuration parameter used for optimizing server performance.

Overview
********

**TPS** prevents micro-lags by maintaining a specific TPS threshold. If TPS falls below the threshold, certain server features may temporarily stop working. It's similar to FPS (Frames Per Second) for clients, where low TPS results in server-wide lag.

**Configuration**
***************

.. admonition:: **Configuration**
   :class: important
   
   Configuring **TPS** in your server setup is essential for optimal performance. You can adjust the TPS value to meet the specific needs of your server. Here are examples of how to set TPS:


   RocketMod ``UnturnedGuard.RocketMod.configuration.xml``
   
   .. code-block:: xml

      <ReportAnomalyTPS>true</ReportAnomalyTPS>
      <TPS>47</TPS>

   OpenMod ``config.yaml``

   .. code-block:: yaml

      ReportAnomalyTPS: true
      TPS: 47

   By playing and configuring the **TPS** value and other related settings, you can ensure a smoother gaming experience for all players.
