UI Permission
=============
UI Permission

.. tabularcolumns:: |p{4cm}|l|p{8cm}|
.. csv-table:: UI Permission Attributes (LDAP Object: dcmUiPermission)
    :header: Name, Type, Description (LDAP Attribute)
    :widths: 23, 7, 70

    "
    .. _dcmuiPermissionName:

    :ref:`UI Permission Name <dcmuiPermissionName>`",string,"Name of Permission for UI Action

    (dcmuiPermissionName)"
    "
    .. _dcmuiAction:

    :ref:`UI Action <dcmuiAction>`",string,"UI Action Enumerated values: menu-studies, menu-dashboard, menu-correct_data, menu-lifecycle_management, menu-audit_record_repository, menu-configuration, menu-move_data, menu-statistics, menu-monitoring, tab-monitoring->queues, tab-monitoring->export, tab-monitoring->external_retrieve, tab-monitoring->control, tab-monitoring->associations, tab-monitoring->storage_commitments, tab-monitoring->storage_systems, tab-monitoring->diff, tab-statistics->statistics, tab-statistics->studies-stored, tab-configuration->devices, tab-configuration->ae_list, tab-configuration->hl7_applications, tab-correct_data->diff, tab-correct_data->patient_data, tab-move_data->retrieve, tab-move_data->export, tab-audit-record-repository->all, tab-audit-record-repository->audit_errors, tab-audit-record-repository->app_errors, action-devicelist-device_configuration, action-studies-patient, action-studies-mwl, action-studies-study, action-studies-serie, action-studies-instance, action-studies-copy_merge_move, action-studies-more_function, action-studies-diff, action-studies-count, action-studies-size, action-studies-viewer, action-studies-verify_storage_commitment, action-studies-download, action-monitoring->queues-all_action, action-monitoring->export-all_action, action-monitoring->external_retrieve-all_action, action-monitoring->queues-single_action, action-monitoring->export-single_action, action-monitoring->diff_monitor-all_action or action-monitoring->external_retrieve-single_action.

    (dcmuiAction)"
    "
    .. _dcmuiActionParam:

    :ref:`UI Action Parameter(s) <dcmuiActionParam>`",string,"UI Action Parameter Enumerated values: edit, create, delete, export, accessible, visible, merge, upload, reject or restore.

    (dcmuiActionParam)"
    "
    .. _dcmAcceptedUserRole:

    :ref:`Accepted User Role(s) <dcmAcceptedUserRole>`",string,"Accepted User Role

    (dcmAcceptedUserRole)"
