# QuPath Scripting Tools

[QuPath](https://github.com/qupath/qupath) is an open-source (GPLv3) bioimage analysis and annotation toolkit written in Java.
One of it's core features is its scriptability via the Java Scripting Engine using Groovy.
However, QuPath only allows running scripts edited via its own rudimentary editing interface.
This project provides a way to develop and run scripts from Eclipse, a real Groovy IDE.

## Demo

![](demo.gif)

The bottom left window is the QuPath scripting window. It is used to run [RemoteCodeServer.groovy](../tools/RemoteCodeServer.groovy). The right window is Eclipse, which uses [RemoteCodeClient.groovy](../tools/RemoteCodeClient.groovy) to run the open script.