![](https://img.shields.io/badge/Foundry-v0.7.9-informational)
<!--- Downloads @ Latest Badge -->
<!--- replace <user>/<repo> with your username/repository -->
<!--- ![Latest Release Download Count](https://img.shields.io/github/downloads/<user>/<repo>/latest/module.zip) -->

<!--- Forge Bazaar Install % Badge -->
<!--- replace <your-module-name> with the `name` in your manifest -->
<!--- ![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2F<your-module-name>&colorB=4aa94a) -->

# Changelog
*Please for the love of all that you hold dear, do everyone a favor and include a changelog here rather than making people guess at the capabilities of your module since last release*

# Description
This is a typescript template to get you started. This is not intended for beginners.

Please use the javascript template as necessary for your stuff.


## Manifest Plus
Adds the following fields to the manifest for package browsers to pick up and show information better:

```
- includes: [] # list of files to include in the zip
- icon: "" # link to icon img
- cover: "" #link to cover img
- screenshots: [] #links to screenshot images
- video: ""
- authors: [
  {
    "name": "name",
    "email": "email",
    "discord": "discord"
  }
]

```


## Versioned Releases

The Github Actions script will automatically create a Latest release which will always have a module.json that points to the latest release, and a versioned release whenever you update the version in your module.json. 

This allows people who depend on a specific version of your module to just install that and be version locked. The versioned releases will *not* auto update. 


# License
MIT License. Do what you will. PRs welcome. 
