# ukd8-subtheme-boilerplate

Boilerplate sub theme based off of UKD8 Base Theme.

## Make subtheme boilerplate specific to your project
To make this subtheme boilerplate specific to your instance, you will need to change the subtheme machine name.

1. Rename 'subtheme_boilerplate' to your specific subtheme name starting with uky_ (example: uky_studentsuccess_theme)
2. Rename 'ukd8_subtheme.theme' to your specific subtheme name starting with uky_ (example: uky_studentsuccess_theme.theme)
3. Rename 'ukd8_subtheme.libraries.yml' to your specific subtheme name starting with uky_ (example: uky_studentsuccess_libraries.yml)
4. Rename 'ukd8_subtheme.info.yml' to your specific subtheme name starting with uky_ (example: uky_studentsuccess_info.yml)
5. In your info.yml file you will need to edit lines 1, 3 and 12 to rename the files to match.
    - Line 1 - Rename to a human readable name such as 'UKY Student Success'
    - Line 3 - update the name in the description to a human readable name such as 'UKY Student Success'
    - Line 12 - uncomment this line and change the machine name to your specific name starting with uky_ (example: uky_studentsuccess_theme/global)

You are now ready to start subtheming!

## Inheriting block layout
For a subtheme to inherit the block layout of a base theme, the base theme must be the current default theme at the time the sub-theme is installed and set as default. See [this issue](https://www.drupal.org/project/drupal/issues/2635978) for discussion. **NOTE:** If an uninstalled subtheme is required by feature modules (via dependencies defined in configuration), the subtheme will be installed with the module, but it may not inherit the block layout of the current default theme. This will cause the blocks to have no placement in the newly activated subtheme. 
