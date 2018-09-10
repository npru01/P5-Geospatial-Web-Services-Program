<b><h2>Parameters Necessary for...</h2></b>
 
<b><h3>Roads</h3></b>

><b>Path</b>
>>_The path parameter accepts a list of latitude/longitude pairs._

><b>Key</b>
>>_Must identify itself every time it sends a request to the Roads._

><b>interpolate</b>
>>_To interpolate a path to include all points forming the full road-geometry._

><b>snappedPoints</b>
>>_An array of snapped points. Each point consists of the following fields_
>>><b>Location</b>
>>>>_Contains a latitude and longitude_

>>><b>originalIndex</b>
>>>>_An integer that indicates the corresponding value in the original request_

>>><b>interpolate=true</b>
>>>>_The response will contain more coordinates than the request._

>>><b>originalIndex</b>
>>>>_These values are indexed from 0, so a point with an originalIndex of 4 will be the snapped value of the 5th latitude/longitude passed to the path parameter_

>>><b>placeId</b>
>>>>_A unique identifier for a place_

><b>speedlimits</b>
>>_An array of road metadata_

><b>Units</b>
>>_KPH or MPH or KNOTS_

><b>nearestRoads</b>
>>_Indicates roads near to present location_

><b>Condition</b>
>>_What is the condition of the road. 'Intact / Not intact'_

><b>Surface</b>
>>_Indicates the surface material. 'Hard / Loose'_

><b>Lanes</b>
>>_Indicates the number of lanes '1,2,3,4.....'_

><b>Climate</b>
>>_Indicates the climatic conditions. 'all weather / fair weather'_
