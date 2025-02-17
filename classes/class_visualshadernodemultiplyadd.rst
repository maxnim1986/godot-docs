:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualShaderNodeMultiplyAdd.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualShaderNodeMultiplyAdd:

VisualShaderNodeMultiplyAdd
===========================

**Inherits:** :ref:`VisualShaderNode<class_VisualShaderNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Performs a fused multiply-add operation within the visual shader graph.

Description
-----------

Uses three operands to compute ``(a * b + c)`` expression.

Properties
----------

+--------------------------------------------------------+--------------------------------------------------------------------+-------+
| :ref:`OpType<enum_VisualShaderNodeMultiplyAdd_OpType>` | :ref:`op_type<class_VisualShaderNodeMultiplyAdd_property_op_type>` | ``0`` |
+--------------------------------------------------------+--------------------------------------------------------------------+-------+

Enumerations
------------

.. _enum_VisualShaderNodeMultiplyAdd_OpType:

.. _class_VisualShaderNodeMultiplyAdd_constant_OP_TYPE_SCALAR:

.. _class_VisualShaderNodeMultiplyAdd_constant_OP_TYPE_VECTOR:

.. _class_VisualShaderNodeMultiplyAdd_constant_OP_TYPE_MAX:

enum **OpType**:

- **OP_TYPE_SCALAR** = **0** --- A scalar type.

- **OP_TYPE_VECTOR** = **1** --- A vector type.

- **OP_TYPE_MAX** = **2** --- Represents the size of the :ref:`OpType<enum_VisualShaderNodeMultiplyAdd_OpType>` enum.

Property Descriptions
---------------------

.. _class_VisualShaderNodeMultiplyAdd_property_op_type:

- :ref:`OpType<enum_VisualShaderNodeMultiplyAdd_OpType>` **op_type**

+-----------+--------------------+
| *Default* | ``0``              |
+-----------+--------------------+
| *Setter*  | set_op_type(value) |
+-----------+--------------------+
| *Getter*  | get_op_type()      |
+-----------+--------------------+

A type of operands and returned value.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
