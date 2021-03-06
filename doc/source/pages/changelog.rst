Change Log
------------

soaplib-2.0
===========

* Enum factory can be passed a '__doc__' keyword argument.
* Serializers renamed to Models.
* Annotations added for primitive types.
* Hard dependency on WSGI removed
* Per model stand alone XSD generation added
* @soap() added to be more SOAP specific.
* @doc() added to support document literal style/use.
* @rpc() modified to default to rpc literal style/use.
* Standalone WSDL added.
* Support for multiple services and portType bindings added.
* Utilities added for exporting Model instances as XML.


soaplib-1.0
===========
* Standards-compliant Soap Faults
* Allow multiple return values and return types

soaplib-0.9.4
===============

* primitive.Array -> clazz.Array
* Support for SimpleType restrictions (pattern, length, etc.)

soaplib-0.9.3
===============

* Soap header support
* Tried the WS-I Test first time. Many bug fixes.

soaplib-0.9.2
===============

* Support for inheritance.

soaplib-0.9.1
===============

* ValidiatingApplication added.
* Support for publishing multiple service classes

soaplib-0.9
===============

* Soap server logic almost completely rewritten.
* Soap client removed in favor of suds.
* Object definition api no longer needs a class types: under class definition.
* XML Schema validation is supported.
* Support for publishing multiple namespaces. (multiple <schema> tags in the wsdl)
* Support for enumerations.
* Application and Service Definition are separated. Application is instantiated on server start, and Service Definition is instantiated for each new request.
* @soapmethod -> @rpc


soaplib-0.8
===============

* Switched to lxml for proper xml namespace support.
* In this version, soaplib is a stable soap server not without its glitches
  and quirks
