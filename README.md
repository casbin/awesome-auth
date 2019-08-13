# Awesome Authentication & Authorization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Quality Authentication & Authorization software and libraries.

[Authentication (aka AuthN)](https://en.wikipedia.org/wiki/Authentication) and [authorization (aka AuthZ)](https://en.wikipedia.org/wiki/Authorization) are both security measures. Authentication is the process of verifying who you are. Authorization is the process of verifying that you have access to something. Authorization occurs after successful authentication.

## Contents

- [Authentication](#authentication)
	- [C#](#authN-cSharp)
	- [Golang](#authN-golang)
	- [Java](#authN-java)
	- [Node.js](#authN-node)
	- [Python](#authN-python)
	- [Ruby](#authN-ruby)

- [Authorization](#authorization)
	- [Android](#authZ-android)
	- [C#](#authZ-cSharp)
	- [Golang](#authZ-golang)
	- [iOS](#authZ-ios)
	- [Java](#authZ-java)
	- [Node.js](#authZ-node)
	- [PHP](#authZ-php)
	- [Python](#authZ-python)

- [Articles](#articles)

## Authentication

### <a name="authN-cSharp"></a>C#

- [Xamarin.Auth](https://github.com/xamarin/Xamarin.Auth) - Helps developers authenticate users via standard authentication mechanisms (e.g. OAuth 1.0 and 2.0), and store user credentials.
- [Kentor Authentication Services](https://github.com/KentorIT/authservices) - Saml2 authentication services for ASP.NET.
- [SimpleAuthentication](https://github.com/SimpleAuthentication/SimpleAuthentication) - ASP.NET library that makes it really easy and simple for developers to add social authentication to an ASP.NET application.
- [OwinOAuthProviders](https://github.com/TerribleDev/OwinOAuthProviders) - OAuth providers for Owin.
- [AspNet.Security.OAuth.Providers](https://github.com/aspnet-contrib/AspNet.Security.OAuth.Providers) - OAuth2 social authentication providers for ASP.NET Core.
- [IdentityServer4](https://github.com/IdentityServer/IdentityServer4) - OpenID Connect & OAuth 2.0 framework for ASP.NET Core.

### <a name="authN-golang"></a>Golang

- [ORY Hydra](https://github.com/ory/hydra) - OpenID Connect certified OAuth2 server.
- [ORY Oathkeeper](https://github.com/ory/oathkeeper) - Identity/Access proxy inspired by the BeyondCorp/Zero-Trust white paper.
- [ORY Fosite](https://github.com/ory/fosite) - Extensible OAuth 2.0 and OpenID Connect SDK for Golang.

### <a name="authN-java"></a>Java

- [Apache Shiro](https://github.com/apache/shiro) - Powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine for Java (authentication, authorization, multi frameworks): OAuth, CAS, SAML, OpenID Connect, LDAP, JWT.
- [Spring Security OAuth](https://github.com/spring-projects/spring-security-oauth) - Provides support for using Spring Security with OAuth (1a) and OAuth2.

### <a name="authN-node"></a>Node.js

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication for Node.js. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.
- [bell](https://github.com/hapijs/bell) - Third-party authentication plugin for hapi. Ships with built-in support for various well-known sites and simple configuration object will support other OAuth 1.0a and OAuth 2.0 sites.

### <a name="authN-python"></a>Python

- [Keystone](https://github.com/openstack/keystone) - Provides authentication, authorization and service discovery mechanisms via HTTP primarily for use by projects in the OpenStack family.
- [Authomatic](https://github.com/authomatic/authomatic) - Simple yet powerful authorization & authentication client library for Python web applications.
- [Python Social Auth](https://github.com/python-social-auth/social-core) - Easy to setup social authentication/registration mechanism with support for several frameworks and auth providers.

### <a name="authN-ruby"></a>Ruby

- [Authlogic](https://github.com/binarylogic/authlogic) - Clean, simple, and unobtrusive Ruby authentication solution.

## Authorization

### <a name="authZ-android"></a>Android

- [AndPermission](https://github.com/yanzhenjie/AndPermission) - Android runtime permission, support the right to apply for permission at any place.

### <a name="authZ-cSharp"></a>C#

- [Casbin.NET](https://github.com/casbin/Casbin.NET) - Authorization library that supports access control models like ACL, RBAC, ABAC in .NET (C#).
- [DotNetOpenAuth](https://github.com/DotNetOpenAuth/DotNetOpenAuth) - Implementation of the OpenID, OAuth protocols.
- [AuthorizationServer](https://github.com/IdentityModel/AuthorizationServer) - Sample implementation of an OAuth2 authorization server.

### <a name="authZ-golang"></a>Golang

- [Casbin](https://github.com/casbin/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC in Golang.
- [goRBAC](https://github.com/mikespook/gorbac) - Lightweight role-based access control implementation in Go.
- [Ladon](https://github.com/ory/ladon) - SDK for access control policies: authorization for the microservice and IoT age.
- [Foulkon](https://github.com/Tecsisa/foulkon) - Authorization server that allows or denies access to web resources.
- [Gocialite](https://github.com/danilopolani/gocialite) - Social OAuth login in Go with multiple providers has never been so easy.
- [ORY Keto](https://github.com/ory/keto) - Access control server capable of solving complex use cases (multi-tenant, attribute-based access control, etc.) with access control policies.

### <a name="authZ-ios"></a>iOS

- [Permission](https://github.com/delba/Permission) - Unified API to ask for permissions on iOS.

### <a name="authZ-java"></a>Java

- [jCasbin](https://github.com/casbin/jcasbin) - Authorization library that supports access control models like ACL, RBAC, ABAC in Java.
- [Apache Shiro](https://github.com/apache/shiro) - Powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine for Java (authentication, authorization, multi-frameworks): OAuth, CAS, SAML, OpenID Connect, LDAP, JWT.
- [AT&T XACML](https://github.com/att/XACML) - XACML 3.0 implementation from AT&T.
- [Apache Sentry](https://github.com/apache/sentry) - Highly modular system for providing fine grained role based authorization to both data and metadata stored on an Apache Hadoop cluster.
- [TOTP Server-Side Library](https://github.com/wstrange/GoogleAuth) - TOTP server-side library.

### <a name="authZ-node"></a>Node.js

- [Node-Casbin](https://github.com/casbin/node-casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC in Node.js.
- [RBAC](https://github.com/CherryProjects/rbac) - Hierarchical role-based access control for Node.js.
- [ABAC](https://github.com/vovantics/abac) - Attribute-based access control for Node.js.
- [accesscontrol](https://github.com/onury/accesscontrol) - Role and attribute-based access control for Node.js.

### <a name="authZ-php"></a>PHP

- [PHP-Casbin](https://github.com/php-casbin/php-casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC in PHP.
- [PHP-RBAC](https://github.com/OWASP/rbac) - Authorization library for PHP which provides developers with NIST Level 2 hierarchical role-based access control.
- [ezRbac](https://github.com/xiidea/ezRbac) - Simple yet easy to implement role-based access control library for popular PHP framework: [Codeigniter](https://github.com/bcit-ci/CodeIgniter).
- [php-abac](https://github.com/Kilix/php-abac) - Attribute-based access control library.
- [laravel-permission](https://github.com/spatie/laravel-permission) - Allows you to manage user permissions and roles in a database.
- [logical-permissions-php](https://github.com/ordermind/logical-permissions-php) - This is a generic library that provides support for array-based permissions with logic gates such as AND and OR.
- [symfony-logical-authorization-bundle](https://github.com/ordermind/symfony-logical-authorization-bundle) - This Symfony bundle provides a unifying solution for authorization that aims to be flexible, convenient and consistent.

### <a name="authZ-python"></a>Python

- [PyCasbin](https://github.com/casbin/pycasbin) - Authorization library that supports access control models like ACL, RBAC, ABAC in Python.
- [Simple RBAC](https://github.com/tonyseek/simple-rbac) - Simple role-based access control utility for Python.
- [Flask-RBAC](https://github.com/shonenada/flask-rbac) - Adds RBAC support to [Flask](https://github.com/pallets/flask).
- [Vakt](https://github.com/kolotaev/vakt) - Attribute-based access control (ABAC) SDK for Python.

## Articles

- [Modeling Authorization with PERM in Casbin](https://vicarie.in/posts/generalized-authz.html)
- [Basic Role-Based HTTP Authorization in Go with Casbin](https://zupzup.org/casbin-http-role-auth)
- [Policy enforcements on Kubernetes with Banzai Cloud's Pipeline and Casbin](https://banzaicloud.com/blog/policy-enforcement-k8s/)
- [Organizational RBAC in Argo CD with Casbin](https://argoproj.github.io/docs/argo-cd/docs/rbac.html)

## Contribute

PR is welcomed.

## License

This project is licensed under the [CC0-1.0 license](https://github.com/casbin/awesome-auth/blob/master/LICENSE).
