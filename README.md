# FOSSA Capturing License Changes of a Package

This is an example of scanning a package, ElasticSearch, in which its declared license changed in a later version. 
To test this scanning, use the `fossa cli` and scan the older commit first. 
The recommendation is to switch to the older commit and then utlilise `--revision` flag to define the revision as the older commit, and then run a scan via `fossa analyze --revision <revision>`. 
Then do the same for the latest commit of the version change of the package.
