# The Morna design template for Voog
A simple template to learn development and tooling for the website building platform [Voog](https://www.voog.com).

## Set up the developing environment
To modify this template [Node Package Manager](https://www.npmjs.org/) (or [Node.js](http://www.nodejs.org/)), [Bower](http://www.bower.io/) and [Grunt](http://www.gruntjs.com/) must be installed.

To set up the local developing environment, clone this repository and run the following commands:

* Install Grunt dependencies: ```yarn install```
* Install Bower dependencies: ```bower install```
* Run Grunt tasks: ```grunt```

To sync the template with your **Voog** sites, set up the [Voog Developer Toolkit](http://www.voog.com/developers/kit)

## Watch and update modifications
* To watch (and synchronize) modified files in real time (**on the default site**) start the Grunt watcher task:
  * **Example:** ```grunt watch```
  * **Notes:**
    * Default site is the first site defined in the **.voog** configuration file.
    * If the **.voog** file is missing, the watcher will only update the output files on the local computer.
* To watch **specific site** start the Grunt watcher with **--site** parameter value.
  * **Example:** ```grunt watch --site=mysite.voog.com```
  * **Notes:**
    * Possible **--site** values are the site names defined in the **.voog** configuration file.
    * If the **.voog** file is missing, the watcher will ignore the **--site** parameter and updates the output files only on the local computer.

## What's with the name?
All of [Voog's own design templates](https://github.com/orgs/Voog/repositories?q=design) seem to be named after different cities and towns all around the world. Who am I to go against customs? Morna is a fictional town in Estonia. It is the setting for [Õnne 13](https://en.wikipedia.org/wiki/%C3%95nne_13), an Estonian dramatic TV series. The series first aired in '93 and is still going strong. It is the best.
