# ukd8-subtheme-boilerplate

Boilerplate sub theme based off of UKD8 Base Theme.


## Inheriting Block Layout
For a subtheme to inherit the block layout of a base theme, the base theme must be the current default theme at the time the sub-theme is installed and set as default. See [this issue](https://www.drupal.org/project/drupal/issues/2635978) for discussion. **NOTE:** If an uninstalled subtheme is required by feature modules (via dependencies defined in configuration), the subtheme will be installed with the module, but it may not inherit the block layout of the current default theme. This will cause the blocks to have no placement in the newly activated subtheme. 
