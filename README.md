RH-SSO BOMs
==========

The RH-SSO BOM's project provides Maven BOM files which manages the version of the dependencies you use in your project, ensuring you always get a compatible stack.

Usage
-----

To use the BOM, import into your dependency management. For example, if you're using EAP 7, use:

    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.redhat.bom.rh-sso</groupId>
                <artifactId>rh-sso-eap7-bom</artifactId>
                <version>7.1.1.CR2</version>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

If you're using EAP 6, use:

    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.redhat.bom.rh-sso</groupId>
                <artifactId>rh-sso-eap6-bom</artifactId>
                <version>7.1.1.CR2</version>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

