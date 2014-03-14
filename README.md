This is test module:

1. Create a Drupal module:
a. Module should create new content type
b. Module must use own node templates
c. Create a block with last 3 nodes (in code)
d. Create a block with last 5 nodes (via Views) and export it to your module
e. Put block from c. into first sidebar by default
f. Create separate templates for nodes with odd and even node ids
g. Add link field to your content type in code (use Link module)
2. Integrate your module with Webform:
a. Webform module allows to create lists which can be used for Select/Checkboxes/Radios
elements. Create new predefined select list with a list of your nodes (check default
Countries or Day of week lists)
3. Integrate with REST services (https://drupal.org/sandbox/Taran2L/1807378):
a. create a new resource /api/my_node with only one method implemented (index)