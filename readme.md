Business process to test FEEL expression
=======================

Import project and open FEELProcess.bpmn. Sequence flow from the `Gateway` to the task with label `True Task` has configured FEEL expression example.

To test just build, deploy and execute the process. Provide integer value to initial form. If value will be 20 or more `True Task` will be executed. If less than 20, `False Task` will be executed.
