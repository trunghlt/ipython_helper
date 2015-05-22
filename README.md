# ipython_helper
My own helper tools to work with ipython and ipython notebook


## Redirect output to stdout/stderror to file:

    with redirect_output(“my_output.txt”):
        print ‘hello world’
