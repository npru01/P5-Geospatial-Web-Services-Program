# Parameters for Geocoding process - _Draft_

Request types
 - by POI
 
 [source,xml]
----
<Request requestID="1" version="1.2" methodName="LocationUtilityService">
  <GeocodeRequest returnFreeForm="false">
    <Address countryCode="PositionOfInterest">
      <freeFormAddress>rennes</freeFormAddress>
    </Address>
  </GeocodeRequest>
</Request>
----
<1> Sample POI request .

 
 - by administrative unit
 - by adress
 - other filter criteria
 - by casdastral parcel
><b> * Code
>>     * HTTP status of the response.

><b> * Message
>>     * short description of the error

><b> * Status
>>     * status code indicating the nature of the error
