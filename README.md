# TiddlyWiki Plugin Skeleton for ThirdFlow

Use this plugin skeleton to easily develop TiddlyWiki5 plugins using the
_[ThirdFlow](https://github.com/TheDiveO/ThirdFlow)_ plugin. For an easy
introduction, you may want to [watch the demo video](https://youtu.be/BFE6PFZ_uWQ).

# How To (Set Up and Release)

1. Set Up...

    0. clone this repository:
       `$ git clone https://github.com/kookma/TiddlyWikiPluginSkeleton.git`.
       Optionally specify a different directory to clone into other than
       `TiddlyWikiPluginSkeleton`, by simply appending the new directory name to the
       git clone command. For instance:
       `$ git clone https://github.com/kookma/TiddlyWikiPluginSkeleton.git NewPlugin`,
       where `NewPlugin` is the directory to clone the plugin skeleton into.

    1. optionally edit `package.json` and fill in necessary data, such as `name`,
       `version`, `author`, `homepage`, `license`, et cetera; the impatient can skip
        this step for the moment.
		
    2. run `$ npm run develop`.

    3. next, navigate to http://localhost:8080 in your web browser.

    4. follow the instructions given in the "Plugin Kickstarter" to create your
      plugin.

2. Develop...

    * work on your plugin ... you can freely mix developing things inside the
      web browser as well as outside the browser using a standalone editor.

    * Don't forget to stop and then restart `$ npm run develop` after you've
      made changes to TiddlyWiki files outside your web browser.

3. Release...

    7. to control which files to release, visit your TiddlyWiki's `$:/ControlPanel`
       and go to the `ThirdFlow` tab. Then click on the subtab named `Release`.
       Follow the instructions given there. Please note that you can develop
       multiple plugins simultaneously from the same development TiddlyWiki.

    8. when you're ready to release, simply run `$ npm run release` to create the
       release file(s) in `editions/release/output`. Rinse, then repeat as
       necessary.
