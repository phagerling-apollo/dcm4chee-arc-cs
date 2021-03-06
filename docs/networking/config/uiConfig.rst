UI Configuration
================
UI Configuration

.. tabularcolumns:: |p{4cm}|l|p{8cm}|
.. csv-table:: UI Configuration Attributes (LDAP Object: dcmUiConfig)
    :header: Name, Type, Description (LDAP Attribute)
    :widths: 23, 7, 70

    "
    .. _dcmuiConfigName:

    :ref:`UI Configuration Name <dcmuiConfigName>`",string,"UI Configuration Name

    (dcmuiConfigName)"
    ":doc:`uiPermission` (s)",object,"Permission"
    ":doc:`uiFilterTemplate` (s)",object,"Defined filter template"
    ":doc:`uiDiffConfig` (s)",object,"Study Diff Configuration"
    ":doc:`uiDashboard` (s)",object,"UI Dashboard Configuration"
    ":doc:`uiElasticsearch` (s)",object,"Elasticsearch Configuration for the pro version"
    ":doc:`uiDeviceURL` (s)",object,"Other UI Device URLs"
    ":doc:`uiDeviceCluster` (s)",object,"Group Devices in Clusters"

.. toctree::

    uiPermission
    uiFilterTemplate
    uiDiffConfig
    uiDashboard
    uiElasticsearch
    uiDeviceURL
    uiDeviceCluster
