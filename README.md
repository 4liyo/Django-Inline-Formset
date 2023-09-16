# Django-Inline-Formset
Inline Formsets allow you to edit multiple instances of the child model that are related to a parent model, such as creating, updating, or deleting them together in a single form.<br>

Inline formsets are designed for scenarios where you have a parent model and a child model with a one-to-many relationship.

Inline formsets are created using the inlineformset_factory function provided by Django.

This function generates a formset class that includes forms for both the parent and child models.

The formset class is based on the parent model's form and includes additional form fields for the child model.

The child model (the "many" side of the relationship) should have a foreign key field that establishes the relationship with the parent model((the "one" side of the relationship).The parent can have more than one child.
