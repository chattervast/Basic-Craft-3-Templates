# Basic Craft 3 Templates

Basic templates to use for starting a new Craft 3 based website.

## Composer Craft CMS Command

This command installs Craft at httpdocs and requires the document root for the webserver to be httpdocs/web. Use the remove directory command to remove httpdocs before installing Craft.
```
rm -rf httpdocs
```

```
composer create-project craftcms/craft httpdocs
```

## Composer Plugin Command

After Craft installation, cd into httpdocs and run either the Standard or Basic plugin installation command.

### All Standard Use Plugins
Copy/paste composer command to install all the standard use plugins:
```
composer require nystudio107/craft-seomatic solspace/craft-freeform verbb/navigation superbig/craft3-templateselect craftcms/redactor fruitstudios/linkit verbb/super-table
```

### Basic Plugins
Copy/paste composer command to install only necessary plugins for these templates:
```
composer require verbb/navigation superbig/craft3-templateselect
```

## Sections, Categories and Fields

These templates assume the following:

### Sections
Home
Pages
Blog

### Fields
Home Blocks => homeBlocks
Page Content => pageContent
Template Select => templateSelect (on Pages entries)

### Navigation
Main
Footer