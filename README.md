# vlingo-maven-plugin


[![Build Status](https://travis-ci.org/vlingo/vlingo-maven-plugin.svg?branch=master)](https://travis-ci.org/vlingo/vlingo-maven-plugin) [![Build Status](https://travis-ci.org/vlingo/vlingo-maven-plugin-test.svg?branch=master)](https://travis-ci.org/vlingo/vlingo-maven-plugin-test) [ ![Download](https://api.bintray.com/packages/vlingo/vlingo-platform-java/vlingo-maven-plugin/images/download.svg) ](https://bintray.com/vlingo/vlingo-platform-java/vlingo-maven-plugin/_latestVersion)

Maven plugin supporting the vlingo platform.

See vlingo-maven-plugin-test for examples.

### Bintray

```xml
  <repositories>
    <repository>
      <id>jcenter</id>
      <url>https://jcenter.bintray.com/</url>
    </repository>
  </repositories>
  <dependencies>
    <dependency>
      <groupId>io.vlingo</groupId>
      <artifactId>vlingo-maven-plugin</artifactId>
      <version>0.3.0</version>
      <scope>compile</scope>
    </dependency>
  </dependencies>
```

```gradle
dependencies {
    compile 'io.vlingo:vlingo-maven-plugin:0.3.0'
}

repositories {
    jcenter()
}
```

License (See LICENSE file for full license)
-------------------------------------------
Copyright © 2012-2018 Vaughn Vernon. All rights reserved.

This Source Code Form is subject to the terms of the
Mozilla Public License, v. 2.0. If a copy of the MPL
was not distributed with this file, You can obtain
one at https://mozilla.org/MPL/2.0/.
