# schema configuration reference

The following pages show all the configuration properties [^2] with XML Config [^1] as an example.  For other configurations, please reference: [Properties Configuration](../../configuration/properties.md), [Annotation Configuration](../../configuration/annotation.md), [API Configuration](../../configuration/api.md).

All configuration properties fall into three categories, see the "Function" in the table below.

* Service discovery: used for service registration and discovery in order to find providers for consumers.
* Service governance: used for service management and governance, such as to provide conveninence for dev or test.
* Performance optinize: used for optimizing performance. Diffenent properties may has different performance impact.
* All properties will transform into URL [^3]  which is generated by provider. The url will be subscribed by consumers through registry. Please see the `Corresponding URL parameter` in the table below for each property.


[^1]: XML Schema: http://dubbo.apache.org/schema/dubbo/dubbo.xsd
[^2]: Notice: These three properties, group, interface, and version determine a service. All other properties are used for service governance or performance optimize.
[^3]: URL format：`protocol://username:password@host:port/path?key=value&key=value`

