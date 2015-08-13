# RWD050

Repository for the Smart Home Device Template (SDT).

Note that this project runs under Apache 2.0 license. Read the [LICENSE](LICENSE) in this repository, or refer to [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Any contributions made to this project must comply with the forementioned license.

## Quick Links
- ['domain.xsd' Version 3.0](SDT/schema3.0/src/domain.xsd)
- [UML Diagram of the SDT 3.0](SDT/schema3.0/docs/images/SDT3.0_UML.png) ([source](SDT/schema3.0/docs/SDT_UML.uxf))


## Content

You can find further Information here:

- [SDT Components](SDT/schema3.0/docs/SDT_Components.md)
- [SDT Build System](SDT/schema3.0/docs/SDT%20Build%20System.md)
- [Examples](SDT/schema3.0/docs/Examples.md) 
- [FAQ](SDT/schema3.0/docs/FAQ.md)
- [Links & References](SDT/schema3.0/docs/Links.md)
- [Backlog & Issues](SDT/schema3.0/docs/Backlog.md)
- [LICENSE](LICENSE)

## Changes in 3.0
- Renamed RootDevice to Device; renamed Device to SubDevice

## Changes in 2.0.1
- Added missing "uri" data type.

## Changes in 2.0
- Introduced RootDevice to support hierarchical embedded devices.
- Added new data types (byte, float, array, enum, date, time, datetime, blob, uri)
- Added ``readable`` and ``eventable`` to data points.
- Added otional ``<SerialNumber>``, ``<VendorURL>`` and ``<FirmwareVersion>`` elements to DeviceInfo
- Added optional ``<Doc>`` element to Event
- Changed the optionality of the ``<DataPoint>``'s ``type`` attribute to "required".
- Added [UML diagram](SDT/schema2.0/docs/SDT_Components.md)
- Changed the namespace for the XSD from "hgi.org" to "homegatewayinitiative.org".

