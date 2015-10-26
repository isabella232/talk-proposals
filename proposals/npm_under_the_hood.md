# npm under the hood

## abstract

npm is an extremely powerful tool that enables millions of users
to rely on other people's code to build increasingly complex
systems. but have you ever really looked at how npm actually 
*manages* your dependencies? dependencies are a way to outsource
understanding, and, for many javascript developers, that
outsourcing begins at `npm install`. let's recover a bit of that 
understanding by taking a dive below the surface of npm's
command line interface to explore exactly what happens when we
depend on code that depends on code that depends on ... in the
hopes that we can become more informed and responsible 
producers and consumers of modules.
