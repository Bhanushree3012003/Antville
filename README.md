# Antville
Antville is an open source project providing a high performance, feature-rich blog hosting software. Antville can host tens of thousands of blogs. Server power is the only limit. Installation and use is easy.

Antville is written in server-side JavaScript and developed with Helma Object Publisher. Antville works with a relational database in the back-end.

Status Antville’s codebase is of stable quality and ready for production deployment. Try out Antville.org for a demonstration.

There still could be bugs hidden in Antville’s source code. If you find one please let us know. The creators of Antville do not take any responsibility for what the software might do.

System Requirements To run Antville you need Helma Object Publisher and a relational database software. We tested Antville with PostgreSQL and MySQL – MariaDB should work, too.

To enable Antville sending notification e-mails you need access to an SMTP server.

Helma comes with an embedded webserver (Jetty) so you do not need to install one. Yet, you can also use the webserver of your choice.

For details please refer to the installation instructions of Helma Object Publisher and the corresponding software packages.

The INSTALL.md file contains detailed instructions to install Antville.

Define HopObjects and map them to a relational database table. Create, change and delete HopObjects at your whim using a comfortable object-container model. Manual fiddling around with database code is not necessary.

HopObjects extend the native JavaScript object. They got all the common features you know – and more. One highlight are the special templating features to ease the rendering of objects for the Web.

Combine HopObjects to create a hierarchical structure. A URL in Helma mirrors this structure. Each part of the URL path corresponds to a relational database mapping, similar to the document tree of static websites. Helma’s URL space is an analogy to the Document Object Model implemented in client-side JavaScript.
