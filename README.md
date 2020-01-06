# Installing Julia and Juno

If you are unfamiliar with setting up a programming environment 
I recommend following the installation instructions for the [Juno IDE](https://junolab.org/) 

1. These instructions will direct you to the [Julia Download Page](https://julialang.org/downloads/)
where you should download the current stable release for your specific platform.

2. Next it will direct you to install the [Atom](https://atom.io/) text editor.

3. Within Atom it will direct you to install the `uber-juno` plugin. 
This plugin will make the Atom text editor into a great environment for programming 
with Julia.

4. Finally, you will need to point Atom to the location where you installed Julia (in step 1).
Do this by going to `Packages > Juno > Settings` and in the first box `Julia Path` insert the path 
to your julia installation.

e.g. 
* Windows might have: `C:\Users\UserName\AppData\Local\Julia-1.2.0\bin\julia.exe`
* OSX might have: `/Applications/Julia-1.3.app/Contents/Resources/julia/bin/julia`

5. You're done the installation! Restart Atom to see the default setup.

6. Open this tutorial folder `File > Add Project Folder`

(if you are more comfortable, you may also want to add this to your `$PATH` variable so
you can open Julia from your terminal with the command `julia`. 
If you don't know how to do this, then you should be good to go!)

