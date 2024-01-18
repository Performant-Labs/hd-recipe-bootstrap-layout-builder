## HeroDevs Merucry Editor Recipe
Create a Mercury Editor Recipe.

This recipe is designed to:
- Call the HeroDevs - Base recipe.
- Install Mercury Editor (https://www.drupal.org/project/mercury_editor).

## Documentation

[Instructions on Google](https://docs.google.com/document/d/1OVe_jwPZNUWt7ovWD2XXcSPmCf0YrnypocMIVIrIqrQ/edit)

## Installation Instructions

- See the instructions for HeroDevs Base to get Drupal
  core able to apply recipes.

```shell
  php core/scripts/drupal recipe recipes/contrib/hd-recipe-mercury
```

You should see:
```
[OK] HD Base applied successfully
```
Clear the cache (`drush cr` or use the UI) and visit the site.
