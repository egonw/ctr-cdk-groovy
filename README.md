CDK/Groovy answers to the Chemistry Toolkit Rosetta
===================================================

The [Chemistry Toolkit Rosetta](http://ctr.wikia.com/wiki/Chemistry_Toolkit_Rosetta_Wiki) is a wiki initiative by 
[Andrew](http://ctr.wikia.com/wiki/User:Andrew_Dalke) to show how various common cheminformatics tasks can be
done in the various cheminformatics toolkits.

This Git repository holds the [CDK](http://cdk.sf.net/) solution written in [Groovy](http://groovy.codehaus.org/).

How to run a solution
---------------------

Linux commands:

$ cd lib/
$ wget http://heanet.dl.sourceforge.net/project/cdk/cdk/1.2.5/cdk-1.2.5.jar
$ ln -s cdk-1.2.5.jar cdk.jar
$ cd ..
$ export CLASSPATH=lib/cdk.jar
$ groovy canonicalSMILES/solution.groovy

License
-------

[CC-BY-SA](http://creativecommons.org/licenses/by-sa/2.0/)
