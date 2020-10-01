# Drupal Twig Cheat Sheet (of stuff I figured out after Googling didn't help)

## Accessing Entities

### Accessing referenced nodes from a _block_ template

`elements.content.field_entity_reference_field_foo['#items'].0.entity`
