# My First SASS

This repository is an example of using SASS. This example is my first attempt using SASS for the first time. I learned about how to use variables, inheritance, and mixins. If you're on Linux, the way to get SASS working on your device is by running this command in Terminal:

````sh
sudo apt-get install ruby ruby-dev
sudo gem install sass --no-user-install
````

After you installed the tools you needed, all you need is to run this command in Terminal:

````sh
# (In case you're not in the directory)
cd my-first-sass
# Run
sass --watch input.scss:input.css
````

And you're good to go. Edit your input.scss and the input.css will be compiled automatically when you save the SCSS file. If you want to create the minified CSS, run this command in Terminal:

````sh
# (In case you're not in the directory)
cd my-first-sass
# Run
sass --watch input.scss:input.css --style compressed
````

And there you have it. You should be able to play along with SASS right now.

---

Learn more or read their documentation about SASS in their website [here.](https://sass-lang.com/)
