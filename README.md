# Editorial starter

## Introduction

The "Editorial Starter" package offers a pre-selected set of Lutece plugins focused on editorial content publishing, providing the following features:

 
* Blog 
* Document management
* Simple HTML
* Newsletter
* workflow management
* All basic Lutece features (user management, permissions, roles, profiles, etc.)
* etc.

The "Editorial Starter" package can be used directly or as a starting point for building a more complete Lutece site by adding other necessary plugins related to:

 
* authentication type
* statistical tracking
* specific business functionalities
* etc.

## Configuration

Declare the Editorial Starter as a dependency in the lutece site pom.xml

```

<dependency>
	<groupId>fr.paris.lutece.starters</groupId>
	<artifactId>editorial-starter</artifactId>
	<version>[x.y.z]</version>
	<type>jar</type>
</dependency>

```

## Usage

 **DB generation** 

To create Database automatically, activate the liquibase engine by overriding the property :

```

liquibase.enabled.at.startup=true

```


[Maven documentation and reports](https://dev.lutece.paris.fr/plugins/forms-starter/)




