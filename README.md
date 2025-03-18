# &int; created
> Integration created

# Idempiere OpenAPI
> 

This is simple OpenApi implementation (version 3.22.2) for Idempiere OSGI platform.

This OpenApi application was created to work together with Idempiere WebStore / Portal API

[https://github.com/icreated/webstore-api](https://github.com/icreated/webstore-api)

[https://github.com/icreated/portal-api](https://github.com/icreated/portal-api)

It should point to following **openapi.xml** for WebStore:

[http://localhost:8080/services/openapi.yaml](http://localhost:8080/services/openapi.yaml)

or 

[http://localhost:8080/portal/openapi.yaml](http://localhost:8080/portal/openapi.yaml)

for Portal API


## Installing / Getting started

To build this plugin you need to get sources in your project directory:

```shell
git clone https://github.com/icreated/webstore-api.git
```

If used with others API plugins, modify path in pom.xml:

```yml
<openapi-value>http://localhost:8080/services/openapi.yaml</openapi-value>
```

Build it with Maven:

```shell
mvn install
```

Deploy plugin to Idempiere OSGI and navigate to OpenAPI URL:

[http://localhost:8080/openapi/app/](http://localhost:8080/openapi/app/)

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. 

Pull requests are warmly welcome


## Licensing

GNU General Public License
