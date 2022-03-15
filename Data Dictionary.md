### Data Dictionary

This data dictionary provides an overview of features/variables/columns, alongside data types and descriptions. 

#### STILL NEED TO ADD DATA TYPES ONCE DATA HAS BEEN PAIRED DOWN

<table>
  <tr>
   <td><strong>Attribute</strong>
   </td>
   <td><strong>Definition</strong>
   </td>
   <td><strong>Source</strong>
   </td>
  </tr>
  <tr>
   <td>ABCD Misc
   </td>
   <td>A FireCode used by USDA FS to track and compile cost information for emergency initial attack fire suppression expenditures. for A, B, C & D size class fires on FS lands.
   </td>
   <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>ADS Permission State
   </td>
   <td>Indicates the permission hierarchy that is currently being applied when a system utilizes the UpdateIncident operation.
   </td>
   <td>IRWIN
   </td>   
  </tr>
  <tr>
   <td>Archived On
   </td>
   <td>A date set by IRWIN that indicates when an incident's data has met the rules defined for the record to become part of the historical fire records rather than an operational incident record. The value will be set the current date/time if any of the following criteria are met:
<p>
1. ContainmentDataTime or ControlDateTime or FireOutDateTime or ModifiedOnDateTime > 12 months from the current DateTime
<p>
2. FinalFireReportDate is not null and ADSPermissionState is 'certified'.
   </td>
   <td>IRWIN
   </td>   
  </tr>
  <tr>
   <td>Calculated Acres
   </td>
   <td>A measure of acres calculated (i.e., infrared) from a geospatial perimeter of a fire. More specifically, the number of acres within the current perimeter of a specific, individual incident, including unburned and unburnable islands. The minimum size must be 0.1.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Containment Date Time
   </td>
   <td>The date and time a wildfire was declared contained.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Control Date Time
   </td>
   <td>The date and time a wildfire was declared under control.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Created By System
   </td>
   <td>ArcGIS Server Username of system that created the IRWIN Incident record.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Created On Date Time
   </td>
   <td>Date/time that the IRWIN Incident record was created.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Daily Acres
   </td>
   <td>A measure of acres reported for a fire. More specifically, the number of acres within the current perimeter of a specific, individual incident, including unburned and unburnable islands. The minimum size must be 0.1.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Discovery Acres
   </td>
   <td>An estimate of acres burning upon the discovery of the fire. More specifically when the fire is first reported by the first person that calls in the fire. The estimate should include number of acres within the current perimeter of a specific, individual incident, including unburned and unburnable islands.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Dispatch Center ID
   </td>
   <td>A unique identifier for a dispatch center responsible for supporting the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Final Fire Report Approved By Title
   </td>
   <td>The title of the person that approved the final fire report for the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Final Fire Report Approved By Unit
   </td>
   <td>NWCG Unit ID associated with the individual who approved the final report for the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Final Fire Report Approved Date
   </td>
   <td>The date that the final fire report was approved for the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Behavior General
   </td>
   <td>A general category describing the manner in which the fire is currently reacting to the influences of fuel, weather, and topography.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Behavior General 1
   </td>
   <td>A more specific category further describing the general fire behavior (manner in which the fire is currently reacting to the influences of fuel, weather, and topography).
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Behavior General 2
   </td>
   <td>A more specific category further describing the general fire behavior (manner in which the fire is currently reacting to the influences of fuel, weather, and topography).
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Behavior General 3
   </td>
   <td>A more specific category further describing the general fire behavior (manner in which the fire is currently reacting to the influences of fuel, weather, and topography).
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Cause
   </td>
   <td>Broad classification of the reason the fire occurred identified as human, natural or unknown.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Cause General
   </td>
   <td>Agency or circumstance which started a fire or set the stage for its occurrence; source of a fire's ignition. For statistical purposes, fire causes are further broken into specific causes.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Cause Specific
   </td>
   <td>A further categorization of each General Fire Cause to indicate more specifically the agency or circumstance which started a fire or set the stage for its occurrence; source of a fire's ignition.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Code
   </td>
   <td>A code used within the interagency wildland fire community to track and compile cost information for emergency fire suppression expenditures for the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Department ID
   </td>
   <td>The U.S. Fire Administration (USFA) has created a national database of Fire Departments. Most Fire Departments do not have an NWCG Unit ID and so it is the intent of the IRWIN team to create a new field that includes this data element to assist the National Association of State Foresters (NASF) with data collection.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Discovery Date Time
   </td>
   <td>The date and time a fire was reported as discovered or confirmed to exist. May also be the start date for reporting purposes.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Mgmt Complexity
   </td>
   <td>The highest management level utilized to manage a wildland fire event.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Out Date Time
   </td>
   <td>The date and time when a fire is declared out.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Strategy Confine Percent
   </td>
   <td>Indicates the percentage of the incident area where the fire suppression strategy of "Confine" is being implemented.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Strategy Full Supp Percent
   </td>
   <td>Indicates the percentage of the incident area where the fire suppression strategy of "Full Suppression" is being implemented.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Strategy Monitor Percent
   </td>
   <td>Indicates the percentage of the incident area where the fire suppression strategy of "Monitor" is being implemented.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Fire Strategy Point Zone Percent
   </td>
   <td>Indicates the percentage of the incident area where the fire suppression strategy of "Point Zone Protection" is being implemented.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>FS Job Code
   </td>
   <td>A code use to indicate the Forest Service job accounting code for the incident. This is specific to the Forest Service. Usually displayed as 2 char prefix on FireCode.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>FS Override Code
   </td>
   <td>A code used to indicate the Forest Service override code for the incident. This is specific to the Forest Service. Usually displayed as a 4 char suffix on FireCode. For example, if the FS is assisting DOI, an override of 1502 will be used.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>GACC
   </td>
   <td>A code that identifies one of the wildland fire geographic area coordination center at the point of origin for the incident.
<p>
A geographic area coordination center is a facility that is used for the coordination of agency or jurisdictional resources in support of one or more incidents within a geographic coordination area.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>ICS 209 Report Date Time
   </td>
   <td>The date and time of the latest approved ICS-209 report.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>ICS 209 Report For Time Period From
   </td>
   <td>The date and time of the beginning of the time period for the current ICS-209 submission.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>ICS 209 Report For Time Period To
   </td>
   <td>The date and time of the end of the time period for the current ICS-209 submission.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>ICS 209 Report Status
   </td>
   <td>The version of the ICS-209 report (initial, update, or final). There should never be more than one initial report, but there can be numerous updates, and even multiple finals (as determined by business rules).
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Incident Management Organization
   </td>
   <td>The incident management organization for the incident, which may be a Type 1, 2, or 3 Incident Management Team (IMT), a Unified Command, a Unified Command with an IMT, National Incident Management Organization (NIMO), etc. This field is null if no team is assigned.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Incident Name
   </td>
   <td>The name assigned to an incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Incident Short Description
   </td>
   <td>General descriptive location of the incident such as the number of miles from an identifiable town.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Incident Type Category
   </td>
   <td>The Event Category is a sub-group of the Event Kind code and description. The Event Category further breaks down the Event Kind into more specific event categories.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Incident Type Kind
   </td>
   <td>A general, high-level code and description of the types of incidents and planned events to which the interagency wildland fire community responds.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Initial Latitude
   </td>
   <td>The latitude location of the initial reported point of origin specified in decimal degrees.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Initial Longitude
   </td>
   <td>The longitude location of the initial reported point of origin specified in decimal degrees.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Initial Response Acres
   </td>
   <td>An estimate of acres burning at the time of initial response. More specifically when the IC arrives and performs initial size up. The minimum size must be 0.1. The estimate should include number of acres within the current perimeter of a specific, individual incident, including unburned and unburnable islands.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Initial Response Date Time
   </td>
   <td>The date/time of the initial response to the incident. More specifically when the IC arrives and performs initial size up.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>IRWIN ID
   </td>
   <td>Unique identifier assigned to each incident record in IRWIN.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Dispatch Complete
   </td>
   <td>An indicator used by external systems to indicate if the criteria has been met to close an incident in their system.
<p>
OR
<p>
Value of true indicates that the incident record is ready for a fire reporting system to complete and certify the final fire report. This field can be set by a CAD or Ordering system.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Fire Cause Investigated
   </td>
   <td>Indicates if an investigation is underway or was completed to determine the cause of a fire.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is FS Assisted
   </td>
   <td>Indicates if the Forest Service provided assistance on an incident outside their jurisdiction.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Multi Jurisdictional
   </td>
   <td>Indicates if the incident covers multiple jurisdictions.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Reimbursable
   </td>
   <td>Indicates the cost of an incident may be another agency’s responsibility.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Trespass
   </td>
   <td>Indicates if the incident is a trespass claim or if a bill will be pursued.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Unified Command
   </td>
   <td>Indicates whether the incident is being managed under Unified Command. Unified Command is an application of the Incident Command System used when there is more than one agency with incident jurisdiction or when incidents cross political jurisdictions. Under Unified Command, agencies work together through their designated Incident Commanders at a single incident command post to establish common objectives and issue a single Incident Action Plan.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Local Incident Identifier
   </td>
   <td>A number or code that uniquely identifies an incident for a particular local fire management organization within a particular calendar year.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Modified By System
   </td>
   <td>ArcGIS Server username of system that last modified the IRWIN Incident record.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Modified On Date Time
   </td>
   <td>Date/time that the IRWIN Incident record was last modified.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Organizational Assessment
   </td>
   <td>The Organizational Assessment is part of the Wildland Fire Risk and Complexity Assessment (RCA) that was implemented by NWCG in January 2014, which guides Agency Administrators in their management organization selection, both in escalating and moderating situations.  The Organizational Assessment can be compared with the current Incident Management Organization and many other incident level data elements over the life of the fire. It may not always match the current Incident Management Organization value. The authority for producing the Organizational Assessment lies with the incident commander (NWCG PMS-210), thus, the Organizational Assessment can change independent of the published decision. 
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Percent Contained
   </td>
   <td>Indicates the percent of incident area that is no longer active.  Reference definition in fire line handbook when developing standard.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Percent Perimeter To Be Contained
   </td>
   <td>Indicates the percent of perimeter left to be completed. This entry is appropriate for full suppression, point/zone protection, and confine fires, or any combination of these strategies. This entry is not used for wildfires managed entirely under a monitor strategy.  (Note: Value is not currently being passed by ICS-209)
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO City
   </td>
   <td>The closest city to the incident point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO County
   </td>
   <td>The County Name identifying the county or equivalent entity at point of origin designated at the time of collection.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Dispatch Center ID
   </td>
   <td>A unique identifier for the dispatch center that intersects with the incident point of origin. 
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Fips
   </td>
   <td>The code which uniquely identifies counties and county equivalents.  The first two digits are the FIPS State code and the last three are the county code within the state.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Jurisdictional Agency
   </td>
   <td>The agency having land and resource management responsibility for a incident as provided by federal, state or local law. 
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Jurisdictional Unit
   </td>
   <td>NWCG Unit Identifier to identify the unit with jurisdiction for the land where the point of origin of a fire falls.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Jurisdictional Unit Parent Unit
   </td>
   <td>The unit ID for the parent entity, such as a BLM State Office or USFS Regional Office, that resides over the Jurisdictional Unit.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Landowner Category
   </td>
   <td>More specific classification of land ownership within land owner kinds identifying the deeded owner at the point of origin at the time of the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Landowner Kind
   </td>
   <td>Broad classification of land ownership identifying the deeded owner at the point of origin at the time of the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Principal Meridian
   </td>
   <td>The principal meridian of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Qtr
   </td>
   <td>The quarter section of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Qtr Qtr
   </td>
   <td>The quarter/quarter section of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Range
   </td>
   <td>The range of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Section
   </td>
   <td>The section of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Legal Desc Township
   </td>
   <td>The township of the legal description (section, township, range) of the incident at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Predictive Service Area ID
   </td>
   <td>The predictive service area ID where the incidents point of origin is location.  Predictive Service Areas (PSAs) are geographic areas of similar climate based on statistical correlation of Remote Automated Weather Stations (RAWS) data.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Protecting Agency
   </td>
   <td>Indicates the agency that has protection responsibility at the point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO Protecting Unit
   </td>
   <td>NWCG Unit responsible for providing direct incident management and services to a an incident pursuant to its jurisdictional responsibility or as specified by law, contract or agreement.                                                                                                           	Definition Extension:
<p>
 - Protection can be re-assigned by agreement.
<p>
 - The nature and extent of the incident determines protection (for example Wildfire vs. All Hazard.)
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>POO State
   </td>
   <td>The State alpha code identifying the state or equivalent entity at point of origin.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Predominant Fuel Group
   </td>
   <td>The fuel majority fuel model type that best represents fire behavior in the incident area, grouped into one of seven categories.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Predominant Fuel Model
   </td>
   <td>Describes the type of fuels found within the  majority of the incident area.  
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Primary Fuel Model
   </td>
   <td>The fuel model which best represents the primary carrier of the fire for the reporting period.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Secondary Fuel Model
   </td>
   <td>The fuel model which best represents the secondary carrier of the fire for the reporting period.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Strategic Decision Publish Date
   </td>
   <td>The Decision Publish Date represents the date Agency Administrators published (approved) the Strategic Decision document. New decisions can be created and published at any time until the incident has been called out.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Total Incident Personnel
   </td>
   <td>The total number of personnel assigned. Includes overhead, crewmembers, helicopter crewmember, engine crewmembers, camp crew people, etc.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Unique Fire Identifier
   </td>
   <td>Unique identifier assigned to each wildland fire.  yyyy = calendar year, SSUUUU = POO protecting unit identifier (5 or 6 characters), xxxxxx = local incident identifier (6 to 10 characters) 
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>WFDSS Decision Status
   </td>
   <td>Indicates the state of the WFDSS decision and/or if a WFDSS decision has been approved for the incident.  This information is helpful in resolving conflicts between incident records.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Is Part of Complex
   </td>
   <td>Indicates whether the incident is part of a Complex or not. "0" for no, "1" for yes.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Complex Name
   </td>
   <td>The Incident Name of the Complex that is the parent of the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
  <tr>
   <td>Complex ID
   </td>
   <td>The IRWIN ID for the Complex record that is the parent of the incident.
   </td>
      <td>IRWIN
   </td>
  </tr>
</table>

