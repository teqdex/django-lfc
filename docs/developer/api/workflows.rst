=========
Workflows
=========

Utils
=====

.. automodule:: workflows.utils

Workflow
--------
 .. autofunction:: set_workflow
 .. autofunction:: set_workflow_for_object
 .. autofunction:: set_workflow_for_model

 .. autofunction:: remove_workflow
 .. autofunction:: remove_workflow_from_object
 .. autofunction:: remove_workflow_from_model

 .. autofunction:: get_workflow
 .. autofunction:: get_workflow_for_object
 .. autofunction:: get_workflow_for_model

 .. autofunction:: get_objects_for_workflow

States
------
  .. autofunction:: get_state
  .. autofunction:: set_state
  .. autofunction:: set_initial_state

Transitions
-----------
  .. autofunction:: get_allowed_transitions
  .. autofunction:: do_transition
  
Permissions
-----------
  .. autofunction:: update_permissions

Classes
=======

.. automodule:: workflows

  .. autoclass:: WorkflowBase
     :members:

.. automodule:: workflows.models

  .. autoclass:: Workflow
     :members:

  .. autoclass:: State
     :members:

  .. autoclass:: Transition
     :members:
  
  .. autoclass:: StateObjectRelation
     :members:
  
  .. autoclass:: WorkflowPermissionRelation
     :members:
  
  .. autoclass:: StatePermissionRelation
     :members: