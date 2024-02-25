# Introduction

Mastercard's platform and APIs evolve and change over time. Our team is constantly adding new capabilities to expand the set of supported use cases. Usually, these new capabilities are added as new component versions. Changing technology and market conditions also call for the replacement of out-of-date features, APIs, and client libraries. When it comes to releasing new versions and sunsetting any of our offerings, we aim to establish a customer-centric approach with minimal disruption.

# Versioning
## Open source components

To keep up with the new versions of languages, Mastercard follows the policy mentioned in the "Tools and Release Cadence" section of the page.

The languages are going to adhere to the release cycle and LTS(Long Term Support) and STS(Short Term Support) release provided. Our team will usually support the latest LTS release and the latest STS release minus 1.

We will update to the latest minor release in the supported version to ensure that we get all critical fixes, including critical security problems. As soon as the updated version of a language is released, we support it once the first minor release has been deployed. At the same time, we will deprecate the oldest supported version.

# Tools and Release Cadence
## Open API (Application Programming Interface) Generator

OpenAPI Generator v6.x.x

We are supporting the latest release minus 1. Please note that the Open API generator is introducing breaking changes in major releases with no fallback.

Please follow on communication about breaking changes.

The release information and the latest version of Open API Generator are available here https://github.com/OpenAPITools/openapi-generator

## Java

We support Java 8 and above.

The release information and the latest version of Java are available here: https://www.java.com/releases/

## NodeJS

NodeJS 19+

The latest maintenance LTS release and latest release minus 1. Versions that are not getting maintenance support are not supported.

The release information and the latest version of NodeJS are available here: https://nodejs.org/en/about/previous-releases

## Python

Python 3.9+

Only Python versions that are getting security releases are supported.

The release information and the latest version of Python is available here: https://devguide.python.org/versions

## Golang

Golang 1.20+

The release information and the latest version of Go are available here: https://go.dev/doc/devel/release

Each major Go release is supported until there are two newer major releases. For example, Go 1.5 was supported until the Go 1.7 release, and Go 1.6 was supported until the Go 1.8 release. We fix critical problems, including critical security problems, in supported releases as needed by issuing minor revisions (for example, Go 1.6.1, Go 1.6.2, and so on).

## C#

C# .NET6 and .NET7

Latest LTS and STS(Standard Term Support) minus 1 release supported

The release information and the latest version of C# available here https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core

# Deprecation
## Libraries

The notice is issued at least three months before the end-of-life date. Notice is given in Github by adding a label “maintenance | deprecated” to the repository. The label is used to inform library users that a specific facility is now considered obsolete and, thus, no longer advised for use in applications. During this time, the version and language will not be updated, and we may only add critical bug fixes if required. At the end of three months, we will remove the repository in which the depreciating version of the library resides.

## Services

Services onboarded on Mastercard Developers are rarely decommissioned, as each product undergoes a rigorous Product-Market fit process. However, due to changing market demand and technology, there are times when Mastercard does decide to off-board a product from the Developers portal. As with all the processes within Mastercard, to off-board a service, we take a customer-centric approach by making every effort to reach out to the customers and communicate the impact, end of date, and related contractual terms. The timeline is often product and customer-impact dependent, so it varies from product to product.

# Conclusion

Our versioning and deprecation policy is designed to make it easier to bring you the most recent technology with minimal disruption to your business. While we make every effort to inform our customers in advance about changes to the Mastercard platform, there could be a few unavoidable instances when functionality may be changed without prior warning to patch a security vulnerability or correct the existing incorrect behavior.
