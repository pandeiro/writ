# Writ v0.0.1

A utility for publishing writing with Emacs and CouchDB

## Getting Started

Create a config file:

    ```bash
    $EDITOR ~/.writrc
    ```

Fill out the variables:

    ```bash
    username=myusername
    password=mypassword
    url=http://myusername.iriscouch.com/writ
    ```

Now you're ready to start:
    
    ```bash
    mkdir ~/writ && cd ~/writ
    writ An Idea I Want to Write About
    ```
	
Save your file and push it:

    ```bash
    writ-push An\ Idea\ I\ Want\ to\ Write\ About/
    ```


(c) Murphy McMahon 2012
