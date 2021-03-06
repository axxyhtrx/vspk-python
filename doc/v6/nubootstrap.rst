.. _nubootstrap:

nubootstrap
===========================================

.. class:: nubootstrap.NUBootstrap(bambou.nurest_object.NUMetaRESTObject,):

Gateway bootstrap details.


Attributes
----------


- ``zfb_info``: Base64 Encoded JSON String of NSG ZFB Attribute Value Pairs

- ``zfb_match_attribute``: Attribute to auto match on

- ``zfb_match_value``: Attribute value to auto match on

- ``last_updated_by``: ID of the user who last updated the object.

- ``last_updated_date``: Time stamp when this object was last updated.

- ``activation_url``: The activation URL used for bootstrapping this instance of the NSG. If the current configuration of the NSG is incomplete, no link will be returned.

- ``embedded_metadata``: Metadata objects associated with this entity. This will contain a list of Metadata objects if the API request is made using the special flag to enable the embedded Metadata feature. Only a maximum of Metadata objects is returned based on the value set in the system configuration.

- ``installer_id``: The Installer ID

- ``entity_scope``: Specify if scope of entity is Data center or Enterprise level

- ``creation_date``: Time stamp when this object was created.

- ``associated_entity_type``: Object type of the associated entity.

- ``status``: Value showing the bootstrapping or activation status of an NSG or eVDF instance.

- ``owner``: Identifies the user that has created this object.

- ``external_id``: External object ID. Used for integration with third party systems




Children
--------

================================================================================================================================================               ==========================================================================================
**class**                                                                                                                                                      **fetcher**

:ref:`nupermission.NUPermission<nupermission>`                                                                                                                   ``permissions`` 
:ref:`numetadata.NUMetadata<numetadata>`                                                                                                                         ``metadatas`` 
:ref:`nuglobalmetadata.NUGlobalMetadata<nuglobalmetadata>`                                                                                                       ``global_metadatas`` 
================================================================================================================================================               ==========================================================================================



Parents
--------


- :ref:`nunetconfgateway.NUNetconfGateway<nunetconfgateway>`

- :ref:`nugateway.NUGateway<nugateway>`

- :ref:`nunsgateway.NUNSGateway<nunsgateway>`

