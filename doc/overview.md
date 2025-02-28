# Documentation of the Behavior-Semantic Scenery Description (BSSD)

The Behavior-Semantic Scenery Description (BSSD) framework provides a comprehensive method to link behavioral demands directly to elements of a traffic environment, supporting the development, safety validation and operation of Automated Vehicles (AVs). The framework focuses on the explicit representation of behavior-relevant information extracted from the static traffic environment - the scenery - which is usually represented in some kind of map. BSSD has a generic structure that fits every map format, ensuring broad applicability and ease of integration.

<img src="images/overview.png" width ="100%"/>

<br>

If you are not yet familiar with the BSSD at all we recommend to get startet with the [introduction](introduction.md) from the beginning. Otherwise, choose a chapter of your interest from the table of contents below.

### Table of contents
- [Introducing Behavioral Demand, Behavior Space and Behavioral Attributes](introduction.md)
  - [Behavioral Demand](introduction.md#behavioral-demand)
  - [Behavior Space](introduction.md#behavior-space)
  - [Behavioral Attributes](introduction.md#behavioral-attributes)
  - [Visual Summary](introduction.md#visual-summary)
- [Map Representation for BSSD](map_representation.md)
  - [Elements for the Road Network Representation](map_representation.md#elements-for-the-road-network-representation)
  - [Elements for the Behavior Space Representation](map_representation.md#elements-for-the-behavior-space-representation)
- [Specification of the Behavioral Attributes](specification.md)
  - [Speed](specification.md#speed)
  - [Boundary](specification.md#boundary)
  - [Reservation](specification.md#reservation)
  - [Overtake](specification.md#overtake)
- [Application Example](application_example.md)
  - [Example A: T-Junction](application_example.md#example-a-t-junction)
  - [Example B: Crosswalk](application_example.md#example-b-crosswalk)
- [BSSD Extension for Lanelet2](extension_lanelet2.md)
  - [Why Lanelets Can Be Used as a Basis for Behavior Spaces](extension_lanelet2.md#why-lanelets-can-be-used-as-a-basis-for-behavior-spaces)
  - [Data Structure](extension_lanelet2.md#data-structure)
  - [Linkage of BSSD Objects to Scenery Elements](extension_lanelet2.md#linkage-of-bssd-objects-to-scenery-elements)
  - [Map Format Code Example](extension_lanelet2.md#map-format-code-example)
- [BSSD Extension for OpenDRIVE](extension_OpenDRIVE.md)
  - [Integration in the OpenDRIVE Data Structure](extension_OpenDRIVE.md#integration-in-the-opendrive-data-structure)
  - [Data Structure](extension_OpenDRIVE.md#data-structure)
  - [Map Format Code Example](extension_OpenDRIVE.md#map-format-code-example)