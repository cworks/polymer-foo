##Installing with Bower
The recommended way to install Polymer 1.0 is through Bower. To install Bower, see the Bower web site.

Bower removes the hassle of dependency management when developing or consuming elements. When you install a component, Bower makes sure any dependencies are installed as well.

###Project setup
If you haven’t created a bower.json file for your application, run this command from the root of your project:

bower init
This generates a basic bower.json file. Some of the questions, like “What kind of modules do you expose,” can be ignored by pressing Enter.

###The next step is to install Polymer:

bower install --save Polymer/polymer#^1.2.0
Bower adds a bower_components/ folder in the root of your project and fills it with Polymer and its dependencies.

Tip: --save adds the item as a dependency in your app’s bower.json:
{
  "name": "my-project",
  "version": "0.0.0",
  "dependencies": {
    "polymer": "Polymer/polymer#^1.2.0"
  }
}
