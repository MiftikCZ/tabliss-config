# Contributing guide
### How to contribute for begginers
- Fork this repo and create a new branch, (e.g. `my-improvement-01`)
- In that branch make some changes, when adding new config, follow the 🔗 ![adding new config section](./CONTRIBUTE.md#adding-new-config) bellow
- Make sure to save everything (still in the new branch) 
- Now on YOUR fork of this repo's main page there should be some green `Create a pull request` button, click on that and make sure inside commits tab everything is ok
- Then just confirm everything and make the pull request work
- **Congratulations! You just made a pull request**, now just wait till it gets accepted (*or rejected*)

### Adding new config
- In tabliss, export your config by clicking on the blue `export` in settings
- Create a file inside `files/` named `<name>.json`, for example `super_minimal.json` with the exported tabliss config
- Then inside `README.md` add info about the config based on the 🔗 ![format section](./CONTRIBUTE.md#right-format-to-put-into-readmemd) bellow

### Right format to put into README.md
```md
![Preview image](https://example.com/preview.png)
- **config_name.json**
```
- whereas `config_name` beiing the name of your config file you put into the `files/` folder
- *Dragging the screenshot and putting it inside the editing field works same as the first line*
