<!--
 Copyright 2021 Amazon.com.
 SPDX-License-Identifier: MIT
-->

# Building the component

This component comes with a custom artifacts written in Java and uses Gradle build system.

To build this component we recommend to use the 
[gdk](https://docs.aws.amazon.com/greengrass/v2/developerguide/greengrass-development-kit-cli.html).

Also make sure to install [Corretto 
11](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/macos-install.html), which is 
Amazon's 
JDK. 

Once you have installed `gdk`, open a shell on the root folder of the project and do:

```bash
gdk component build
gdk component publish
```

Note: you can customize the publish configuration in `gdk-config.json` in order to select another bucket prefix or region.

