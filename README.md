# &int; created
> Integration created

# Idempiere Swagger
> 

This is simple Swagger implementation (version 3.22.2) for Idempiere OSGI platform.

This Swagger application was created to work together with Idempiere WebStore API

[https://github.com/icreated/webstore-api](https://github.com/icreated/webstore-api)

It points to following **openapi.xml**:

[http://localhost:8080/services/api-docs/openapi.xml](http://localhost:8080/services/api-docs/openapi.xml)


## Installing / Getting started

To build this plugin you need to get sources in your project directory:

```shell
git clone https://github.com/icreated/webstore-api.git
```

If used with others API plugins, modify path in pom.xml:

```xml
<openapi-value>http://localhost:8080/services/api-docs/openapi.xml</openapi-value>
```

Build it with Maven:

```shell
mvn install
```

Deploy plugin to Idempiere OSGI and navigate to Swagger URL:

[http://localhost:8080/swagger/app/](http://localhost:8080/swagger/app/)

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. 

Pull requests are warmly welcome


## Licensing

GNU General Public License
