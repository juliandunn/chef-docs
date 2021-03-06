.. THIS PAGE DOCUMENTS chef-client version 12.2

=====================================================
dsc_script
=====================================================

.. include:: ../../includes_resources_common/includes_resources_common_generic.rst

.. include:: ../../includes_resources_common/includes_resources_common_powershell.rst

.. include:: ../../includes_resources_common/includes_resources_common_powershell_dsc.rst

.. include:: ../../includes_resources/includes_resource_dsc_script.rst

.. note:: .. include:: ../../includes_notes/includes_notes_dsc_script_required_powershell_version.rst

.. note:: .. include:: ../../includes_notes/includes_notes_dsc_script_enable_winrm.rst

.. warning:: .. include:: ../../includes_notes/includes_notes_dsc_script_vs_dsc_resource.rst

Syntax
=====================================================
.. include:: ../../includes_resources/includes_resource_dsc_script_syntax.rst

Actions
=====================================================
.. include:: ../../includes_resources/includes_resource_dsc_script_actions.rst

Properties
=====================================================
.. include:: ../../includes_resources/includes_resource_dsc_script_attributes.rst

Examples
=====================================================
|generic resource statement|

**Specify DSC code directly**

.. include:: ../../step_resource/step_resource_dsc_script_code.rst

**Specify DSC code using a Windows Powershell data file**

.. include:: ../../step_resource/step_resource_dsc_script_command.rst

**Pass parameters to DSC configurations**

.. include:: ../../step_resource/step_resource_dsc_script_flags.rst

**Use custom configuration data**

.. include:: ../../includes_resources/includes_resource_dsc_script_custom_config_data.rst

.. include:: ../../step_resource/step_resource_dsc_script_configuration_data.rst

.. include:: ../../step_resource/step_resource_dsc_script_configuration_name.rst

**Using DSC with other Chef resources**

.. include:: ../../step_resource/step_resource_dsc_script_remote_files.rst

