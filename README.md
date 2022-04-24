# Gastronomic guide

<p>Build fast, responsive sites with Bootstrap</p>
<p>Next, I share the technologies that I applied
    <ul>
    <li>Node.js</li>
    <li>npm</li>
    <li>lite-server</li>
    </ul>
</p>

### To set up the server

<p>To start, we will execute `npm init` command. This utility will walk you through creating a package.json file. It only covers the most common items, and tries to guess sensible defaults.</p>

<p>We will use lite-server which is a simple customized wrapper around BrowserSync to make it easy to serve SINGLE PAGE APPS (SPAs).
For installation follow the Installation and Usage recommendations given in this link https://github.com/johnpapa/lite-server.
After that, the package.json file is modified adding "devDependencies", and download libraries which are saved into node_modules dir.</p>

<p>Use `npm install <pkg>` afterwards to install a package and save it as a dependency in the package.json file.</p>

### To set up the Bootstrap

<p>To install bootstrap: Use `npm install bootstrap --save`</p>
<p>
    <ul>
        <li>Use `npm install jquery --save`</li>
        <li>Use `npm install @popperjs/core --save`</li>
    </ul>
</p>


### To set up index.html

<p>Inclusion of bootstrap css references and js files.</p>