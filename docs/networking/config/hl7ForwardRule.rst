HL7 Forward Rule
================
HL7 Forward Rule

.. tabularcolumns:: |p{4cm}|l|p{8cm}|
.. csv-table:: HL7 Forward Rule Attributes (LDAP Object: hl7ForwardRule)
    :header: Name, Type, Description (LDAP Attribute)
    :widths: 23, 7, 70

    "
    .. _cn:

    :ref:`Name <cn>`",string,"Arbitrary/Meaningful name of the HL7 Forward Rule

    (cn)"
    "
    .. _hl7FwdApplicationName:

    :ref:`HL7 Forward Application Name(s) <hl7FwdApplicationName>`",string,"HL7 Forward Destination Application and Facility name (Application|Facility)

    (hl7FwdApplicationName)"
    "
    .. _dcmProperty:

    :ref:`Conditions(s) <dcmProperty>`",string,"Conditions in format {attributeID}[!]={regEx} or MSH-#[!]={regEx} Examples: MSH-3=FORWARD or MSH-8=ADT\^A28\^ADT_A05

    (dcmProperty)"
