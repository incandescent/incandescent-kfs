KFS Maven War
=============

This project provides a reference KFS Maven overlay war illustrating how to use the Maven [war overlay](http://maven.apache.org/plugins/maven-war-plugin/overlays.html) process to customize an existing war artifact.

This project depends on the `kfs-generic-war` and `kfs-lib` artifacts built by the [KFS Maven bootstrap](https://github.com/incandescent/kuali-kfs-build/tree/kfs-3) project, as well as the `com.incandescent:rice-core` artifact, which illustrates using a separate Maven artifact to introduce customizations.

You can use this project as the basis for your own customized KFS war, using additional Maven dependencies as necessary.  Or you can use this project, and artifact generated from it, directly and help us consolidate community patches for submission upstream.
