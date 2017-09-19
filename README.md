# About

JavaServer Faces technology simplifies building user interfaces for
JavaServer applications.  Developers can build web applications by
assembling reuseable UI components in a page; connecting these
components to an application data source; and wiring client-generated
events to server-side event handlers.  This project provides information
on the continued development of the JavaServer Faces specification.

JavaServer Faces (JSF) is a [JCP Standard](http://jcp.org) technology
for authoring component based user interfaces on the
[Java EE](https://github.com/javaee/) platform.  This particular GitHub
project hosts the
[official JSF specification issue tracker](https://github.com/javaee/javaserverfaces-spec/issues).
There are two implementations of the JSF specification, both of them
developed with OSI approved Open Source licenses.

* [Oracle Mojarra](http://javaserverfaces.java.net)
* [Apache MyFaces](http://myfaces.apache.org)

# Current Status

* JSF 2.3 is the designated user interface standard for
  [Java EE 8](http://jcp.org/en/jsr/detail?id=372).  It went final on 17
  April 2017.

* JSF 2.2 is the user interface standard for
  [Java EE 7](http://jcp.org/en/jsr/detail?id=342") The most recent
  major release of JSF is 2.2.  This release occurred on 21 May 2013.

# Downloads

## JSF 2.3

Though JSF 2.3 is complete, Java EE 8 is still under development.  The
executable implementations of the JSF 2.3 milestones as well as other
versions are available in the
[javax.faces repository](https://maven.java.net/content/repositories/releases/org/glassfish/javax.faces/2.3.0/).  This release is included in [GlssFish 5 Builds](https://javaee.github.io/glassfish/download).

The human readable specification may be downloaded from &lt;[http://jcp.org/](http://jcp.org/en/jsr/detail?id=372)&gt;.

The API is available at Maven Central at these coordinates.

    <dependency>
      <groupId>javax.faces</groupId>
      <artifactId>javax.faces-api</artifactId>
      <version>2.3</version>
      <scope>provided</scope>
    </dependency

The implementation is also available at these coordinates.

    <dependency>
      <groupId>org.glassfish</groupId>
      <artifactId>javax.faces</artifactId>
      <version>2.3.0</version>
      <scope>provided</scope>
    </dependency>

## JSF 2.2

The executable implementation of JSF 2.2 is included in
[GlassFish 4.0](https://javaee.github.io/glassfish/).

The human readable specification may be downloaded from
&lt;[http://jcp.org/](http://jcp.org/en/jsr/detail?id=344)&gt;.

The binary specification is available at maven central at these coordinates.

    <dependency>
      <groupId>javax.faces</groupId>
      <artifactId>javax.faces-api</artifactId>
      <version>2.2</version>
      <scope>provided</scope>
    </dependency>

For convenience, the binary specification is also provided in
[this zip file](downloads/JSF_2_2/javax.faces-api-2.2-FINAL.zip),
but by downloading it, you are agreeing to the terms and conditions
stated [here](downloads/JSF_2_2/000_AAA_eval-spec-license.odt).

## Miscellaneous Downloads

Additional project related downloads are available [here](./DOWNLOADS.md)


# Learning More

## JSF 2.3

Some of many JSF 2.3 related articles may be found in

* [JSF 2.3 Pre-Public Review EC Update](https://java.net/downloads/javaserverfaces-spec-public/JSF_2_3/Public%20Review/20170111-JSF_2_3_EC_MEETING.pdf)
  (Ed Burns)
* [JSF 2.3 new features](http://de.slideshare.net/ConstantinMAlin/jsf-23-new-features-56606253) (Alin Constantin)
* [What's new in JSF 2.3?](http://arjan-tijms.omnifaces.org/p/jsf-23.html) (Arjan Tjms)
* [Neues aus der Java-Welt: JavaServer Faces 2.3 (German)](http://arjan-tijms.omnifaces.org/p/jsf-23.html) (Michael Mueller)

## JSF 2.2

An overview of new features in JSF 2.2 may be found in this slideshare
presentation
&lt;[http://www.slideshare.net/edburns/jsf-22-26091922](http://www.slideshare.net/edburns/jsf-22-26091922)&gt;,
the video for which is from
[JavaZone 2013](http://vimeo.com/album/2525252/video/74409197).

# IMPORTANT!

* By contributing to this project, you are agreeing to the terms of use described in [CONTRIBUTING.md](./CONTRIBUTING.md)

