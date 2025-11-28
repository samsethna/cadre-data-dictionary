| Table Name | Description |
|-------------|-------------|
| [Care_Plan_Interventions](#Care_Plan_Interventions) |This table records any care plan interventions for a client.|
| [Care_Plan_Problems](#Care_Plan_Problems) |This table contains details of all care plan problems associated with a client.|
| [CarePlanProblemValidation](#CarePlanProblemValidation) |This table details Care Plan validation status for problems.|
| [Client_Address_History](#Client_Address_History) |This table is no longer used.|
| [Client_CPA](#Client_CPA) |This table stores the details of a CPA episode including any changes in CPA level (and who made the changes).|
| [Client_Demographic_Details](#Client_Demographic_Details) ||
| [Client_Family](#Client_Family) |This table stores the client family comment for a client.|
| [Client_GP_History](#Client_GP_History) |This table stored details of merged clients GP history.|
| [Client_School](#Client_School) |This table stores the school history for a client.|
| [ClientAlert](#ClientAlert) |This table holds any alerts that have been recorded against a client.|
| [ClientDocumentPersonalContact](#ClientDocumentPersonalContact) ||
| [CPAParticipants](#CPAParticipants) |This table store details of additional shared documents for an organisation.|
| [Deceased](#Deceased) ||
| [Diagnosis](#Diagnosis) |Details of diagnosis for a client.|
| [diagnosiscodeupdate](#diagnosiscodeupdate) |This table contains a list of all possible diagnoses. Each diagnosis is associated with a particular diagnosis coding scheme. (DiagnosisCode).|
| [DiagnosisConfirmedUFCE](#DiagnosisConfirmedUFCE) |This table contains details of any Diagnosis for Unfinished (i.e. Current) inpatient events.|
| [ImsBayClosure](#ImsBayClosure) |This table contains details of the dates during which a bay may be closed.|
| [ImsBed](#ImsBed) |This table contains information about beds including the bed type. Beds are stored within bays.|
| [ImsBedClosure](#ImsBedClosure) |This table contains details of dates during which a bed will not be available.|
| [ImsPlannedEventApproval](#ImsPlannedEventApproval) |This table stored details of approval of planned events.|
| [ImsWardBedAvailability](#ImsWardBedAvailability) |This table contains details about the bed availability of a ward.|
| [ImsWardClosure](#ImsWardClosure) |This table contains information about the closure of a ward.|
| [MntClientCTOConditionDetails](#MntClientCTOConditionDetails) |This table contains details for clients CTO conditions.|
| [mntClientSectionCTORecallDetails](#mntClientSectionCTORecallDetails) |This table contains details of any CTO recalls for a mental health section.|
| [mntClientSectionDetailRights](#mntClientSectionDetailRights) |Retrieving data. Wait a few seconds and try to cut or copy again.|
| [MntClientSectionExpiryExtension](#MntClientSectionExpiryExtension) |This table contains details of any extensions to an expiry date for a mental health section.|
| [mntClientSectionObjectionDetail](#mntClientSectionObjectionDetail) |This table contains details of any objections to a mental health Section.|
| [mntClientSectionTreatmentDetails](#mntClientSectionTreatmentDetails) |This table contains details of any treatment details for a mental health section.|
| [ParentGuardianImport](#ParentGuardianImport) ||
| [PrgProblemTypes](#PrgProblemTypes) |Associates progress notes with care plan problems.|
| [Referral](#Referral) |This table contains details of clients' referrals including the HCP/Team/Specialty referred to, reason for referral and the referrer.|
| [Referral_Team_History](#Referral_Team_History) |This table keeps a history of the teams assigned to a client's referral.|
| [RskRelatedIncidents](#RskRelatedIncidents) |Contains all risk incidents for clients, complete with all addendums, together with other details about the entry.|
| [RskRelatedIncidentsRiskType](#RskRelatedIncidentsRiskType) |This table details information on Client Risks as recorded in the Progress Note functionality.|
| [SNOMED_Client](#SNOMED_Client) |Table contains information about SNOMED entries recorded for a client.|
| [SNOMED_Element](#SNOMED_Element) |This table stores all SNOMED entries entered in the system via assessment forms.|


## Care_Plan_Interventions
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Care_Plan_Interventions|Box_1                      |Free text box                                        |
|Care_Plan_Interventions|Box_2                      |Free text box                                        |
|Care_Plan_Interventions|Box_3                      |Free text box                                        |
|Care_Plan_Interventions|Box_4                      |Free text box                                        |
|Care_Plan_Interventions|Box_5                      |Free text box                                        |
|Care_Plan_Interventions|Box_6                      |Free text box                                        |
|Care_Plan_Interventions|Check_Box_1                |Value of the 1st checkbox                            |
|Care_Plan_Interventions|Check_Box_2                |Value of the 2nd checkbox                            |
|Care_Plan_Interventions|Date_Field_1               |Date entered in date field 1                         |
|Care_Plan_Interventions|Date_Field_2               |Date ented in date field 2                           |
|Care_Plan_Interventions|End_Date                   |End date of intervention                             |
|Care_Plan_Interventions|Entry_Date                 |Date entry entered                                   |
|Care_Plan_Interventions|Intervention_Category_Code |Intervention category                                |
|Care_Plan_Interventions|Intervention_Category_Description|Description                                          |
|Care_Plan_Interventions|Intervention_Key           |Key                                                  |
|Care_Plan_Interventions|Intervention_Type_Code     |Intervention type code, chosen from pick list        |
|Care_Plan_Interventions|Intervention_Type_Description|Description                                          |
|Care_Plan_Interventions|Intervention_Type_National_Code|National code                                        |
|Care_Plan_Interventions|Library_Edited             |Set to 1 if library entry was used and changed       |
|Care_Plan_Interventions|Library_ID                 |If entry was based upon a library entry, the ID of the library entry|
|Care_Plan_Interventions|Outcome_Code               |Intervention outcome, chosen on Intervention close   |
|Care_Plan_Interventions|Outcome_Description        |Outcome description                                  |
|Care_Plan_Interventions|Picklist_1_Code            |Code of item chosen for pick list 1                  |
|Care_Plan_Interventions|Picklist_1_Description     |Description of item chosen for pick list 1           |
|Care_Plan_Interventions|Picklist_2_Code            |Code of item chosen for pick list 2                  |
|Care_Plan_Interventions|Picklist_2_Description     |Description of item chosen for pick list 2           |
|Care_Plan_Interventions|Picklist_3_Code            |Code of item chosen for pick list 3                  |
|Care_Plan_Interventions|Picklist_3_Description     |Description of item chosen for pick list 3           |
|Care_Plan_Interventions|Problem_FK_Care_Plan_Problems|                                                     |
|Care_Plan_Interventions|Start_Date                 |Start date of intervention                           |
|Care_Plan_Interventions|Unique_Key                 |Key                                                  |
|Care_Plan_Interventions|User_Code                  |Code                                                 |
|Care_Plan_Interventions|User_Consultant_Flag       |consultant indicator                                 |
|Care_Plan_Interventions|User_Email                 |Email                                                |
|Care_Plan_Interventions|User_First_Name            |First name                                           |
|Care_Plan_Interventions|User_Main_Specialty_Code   |Code                                                 |
|Care_Plan_Interventions|User_Main_Specialty_Description|Description                                          |
|Care_Plan_Interventions|User_Main_Specialty_National_Code|National code                                        |
|Care_Plan_Interventions|User_Organisation_Type_Code|Code                                                 |
|Care_Plan_Interventions|User_Organisation_Type_Description|Description                                          |
|Care_Plan_Interventions|User_Primary_Team_Code     |Code                                                 |
|Care_Plan_Interventions|User_Primary_Team_Description|Description                                          |
|Care_Plan_Interventions|User_Professional_Group_Code|Code                                                 |
|Care_Plan_Interventions|User_Professional_Group_Description|Description                                          |
|Care_Plan_Interventions|User_Resp_Clinician_Profession_Code|Code                                                 |
|Care_Plan_Interventions|User_Resp_Clinician_Profession_Description|Description                                          |
|Care_Plan_Interventions|User_Surname               |Surname                                              |
|Care_Plan_Interventions|User_Title                 |Title                                                |
|Care_Plan_Interventions|crate_pk                   |crate primary key                                    |
## Care_Plan_Problems
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Care_Plan_Problems|Care_Plan_ID_FK_Care_Plan_Index|Care plan ID of the care plan this problem belongs to|
|Care_Plan_Problems|End_Date                   |End date of problem                                  |
|Care_Plan_Problems|Entry_Date                 |Date of entry                                        |
|Care_Plan_Problems|Library_Edited             |Set to 1 if library entry was used and changed       |
|Care_Plan_Problems|Library_ID                 |If entry was based upon a library entry, the ID of the library entry|
|Care_Plan_Problems|Outcome_Code               |Outcome code of outcome entered on problem close     |
|Care_Plan_Problems|Outcome_Description        |Outcome description                                  |
|Care_Plan_Problems|Problem_Category_Code      |Care plan problem category                           |
|Care_Plan_Problems|Problem_Category_Description|Description                                          |
|Care_Plan_Problems|Problem_Date               |Date                                                 |
|Care_Plan_Problems|Problem_ID                 |ID of this problem                                   |
|Care_Plan_Problems|Problem_Type_Code          |Problem type code, from pick list                    |
|Care_Plan_Problems|Problem_Type_Description   |Description                                          |
|Care_Plan_Problems|Start_Date                 |Start date of problem                                |
|Care_Plan_Problems|Text                       |Free text comment                                    |
|Care_Plan_Problems|Unique_Key                 |Key                                                  |
|Care_Plan_Problems|User_Code                  |Code                                                 |
|Care_Plan_Problems|User_Consultant_Flag       |consultant indicator                                 |
|Care_Plan_Problems|User_Email                 |Email                                                |
|Care_Plan_Problems|User_First_Name            |First name                                           |
|Care_Plan_Problems|User_Main_Specialty_Code   |Code                                                 |
|Care_Plan_Problems|User_Main_Specialty_Description|Description                                          |
|Care_Plan_Problems|User_Main_Specialty_National_Code|National Code                                        |
|Care_Plan_Problems|User_Organisation_Type_Code|Code                                                 |
|Care_Plan_Problems|User_Organisation_Type_Description|Description                                          |
|Care_Plan_Problems|User_Primary_Team_Code     |Code                                                 |
|Care_Plan_Problems|User_Primary_Team_Description|Description                                          |
|Care_Plan_Problems|User_Professional_Group_Code|Code                                                 |
|Care_Plan_Problems|User_Professional_Group_Description|Description                                          |
|Care_Plan_Problems|User_Resp_Clinician_Profession_Code|Code                                                 |
|Care_Plan_Problems|User_Resp_Clinician_Profession_Description|Description                                          |
|Care_Plan_Problems|User_Surname               |Surname                                              |
|Care_Plan_Problems|User_Title                 |Title                                                |
|Care_Plan_Problems|crate_pk                   |crate primary key                                    |
## CarePlanProblemValidation
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|CarePlanProblemValidation|Action                     |Care plan action                                     |
|CarePlanProblemValidation|InterventionSequenceID     |Care plan intervention sequence                      |
|CarePlanProblemValidation|ProblemID                  |Care plan problem ID                                 |
|CarePlanProblemValidation|ProblemSequenceID          |Care plan sequence                                   |
|CarePlanProblemValidation|SequenceID                 |Unique sequence ID                                   |
|CarePlanProblemValidation|ShowIcon                   |Set to 1 to show validated icon                      |
|CarePlanProblemValidation|ValidationStatus           |Current validation status, 1 = Validated             |
|CarePlanProblemValidation|crate_pk                   |crate primary key                                    |
## Client_Address_History
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_Address_History|Accommodation_Type_Code    |Code                                                 |
|Client_Address_History|Accommodation_Type_Description|Description                                          |
|Client_Address_History|Accommodation_Type_National_Code|National Code                                        |
|Client_Address_History|Address_From_Date          |The date the client moved to this address            |
|Client_Address_History|Address_Group              |Address group code                                   |
|Client_Address_History|Address_To_Date            |The date the client left this address                |
|Client_Address_History|Address_Type_Code          |Address type                                         |
|Client_Address_History|Address_Type_Description   |Description                                          |
|Client_Address_History|Electoral_Ward_Code        |The electoral ward of the address                    |
|Client_Address_History|Electoral_Ward_Description |Description                                          |
|Client_Address_History|Health_Authority_Code      |The health authority of this address                 |
|Client_Address_History|Health_Authority_Description|Description                                          |
|Client_Address_History|Last_Updated               |The date and time when this record was last updated  |
|Client_Address_History|Mailsort_Code              |The mail sort code of this address                   |
|Client_Address_History|Primary_Care_Group_Code    |The PCT of this address                              |
|Client_Address_History|Primary_Care_Group_Description|Description                                          |
|Client_Address_History|Unique_Key                 |Key                                                  |
|Client_Address_History|bua11                      |Built-up area code 2011                              |
|Client_Address_History|buasd11                    |Built-up are subdivision code 2011                   |
|Client_Address_History|casward                    |Census area statistics ward                          |
|Client_Address_History|crate_pk                   |crate primary key                                    |
|Client_Address_History|imd                        |indices of multiple deprivation                      |
|Client_Address_History|lea                        |Local educational authority                          |
|Client_Address_History|lsoa01                     |local super output area 2001                         |
|Client_Address_History|lsoa11                     |local super output area 2011                         |
|Client_Address_History|msoa01                     |middle layer super output area 2001                  |
|Client_Address_History|msoa11                     |middle layer super output area 2011                  |
|Client_Address_History|nuts                       |Nomenclature of Territorial Units for Statistics     |
|Client_Address_History|oac01                      |census output area 2001                              |
|Client_Address_History|oac11                      |census output area 2011                              |
|Client_Address_History|parish                     |parish                                               |
|Client_Address_History|pcon                       |Westminster parliamentray constituancy code          |
|Client_Address_History|pct                        |primary care trust                                   |
|Client_Address_History|ru11ind                    |rural area 2011 indicator                            |
|Client_Address_History|statsward                  |                                                     |
|Client_Address_History|ur01ind                    |urban area 2001 indicator                            |
## Client_CPA
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_CPA       |CPA_Level_Code             |Internal RiO identifier for the level of CPA         |
|Client_CPA       |CPA_Level_Description      |Description                                          |
|Client_CPA       |CPA_Level_National_Code    |National code                                        |
|Client_CPA       |Changed_By_Code            |Internal RiO identifier for who made the change      |
|Client_CPA       |Changed_By_Consultant_Flag |consultant indicator                                 |
|Client_CPA       |Changed_By_Email           |Email                                                |
|Client_CPA       |Changed_By_First_Name      |First name                                           |
|Client_CPA       |Changed_By_Main_Specialty_Code|Code                                                 |
|Client_CPA       |Changed_By_Main_Specialty_Description|Description                                          |
|Client_CPA       |Changed_By_Main_Specialty_National_Code|National code                                        |
|Client_CPA       |Changed_By_Organisation_Type_Code|Code                                                 |
|Client_CPA       |Changed_By_Organisation_Type_Description|Description                                          |
|Client_CPA       |Changed_By_Primary_Team_Code|Code                                                 |
|Client_CPA       |Changed_By_Primary_Team_Description|Description                                          |
|Client_CPA       |Changed_By_Professional_Group_Code|Code                                                 |
|Client_CPA       |Changed_By_Professional_Group_Description|Description                                          |
|Client_CPA       |Changed_By_Resp_Clinician_Profession_Code|Code                                                 |
|Client_CPA       |Changed_By_Resp_Clinician_Profession_Description|Description                                          |
|Client_CPA       |Changed_By_Surname         |Surname                                              |
|Client_CPA       |Changed_By_Title           |Title                                                |
|Client_CPA       |End_Date                   |Date CPA ended                                       |
|Client_CPA       |End_Reason_Code            |Code                                                 |
|Client_CPA       |End_Reason_Description     |description                                          |
|Client_CPA       |End_Reason_Is_Discharge    |Discharge flag                                       |
|Client_CPA       |End_Reason_National_Code   |Code                                                 |
|Client_CPA       |Next_CPA_Review_Date       |Date of next review                                  |
|Client_CPA       |Start_Date                 |Date CPA started                                     |
|Client_CPA       |Unique_Key                 |Key                                                  |
|Client_CPA       |crate_pk                   |crate primary key                                    |
## Client_Demographic_Details
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_Demographic_Details|Alternative_RiO_Number     |Alternative ID                                       |
|Client_Demographic_Details|Date_Of_Birth              |Date of birth                                        |
|Client_Demographic_Details|Date_Of_Death              |Date of death                                        |
|Client_Demographic_Details|Date_Of_First_Mental_Health_Care|Date of first mental health care                     |
|Client_Demographic_Details|Date_Registered            |Date client registered                               |
|Client_Demographic_Details|Death_Date_National        |Spine Death date                                     |
|Client_Demographic_Details|Death_Date_Status          |Spine Death date status                              |
|Client_Demographic_Details|Death_Flag                 |Set to 1 for client death                            |
|Client_Demographic_Details|Deleted_Flag               |0 - Undeleted, 1 - Deleted by RiO, 2 - Deleted by PDS|
|Client_Demographic_Details|Died_In_Hospital           |Set to 1 if client died in hospital                  |
|Client_Demographic_Details|Estimated_Date_Of_Birth    |Flag that indicates if DOB is estimated              |
|Client_Demographic_Details|Ethnicity_Code             |Ethnicity code                                       |
|Client_Demographic_Details|Ethnicity_Description      |Ethnicity description                                |
|Client_Demographic_Details|Ethnicity_National_Code    |Ethnicity national code                              |
|Client_Demographic_Details|Exited_NHS_Care            |Exited NHS care flag                                 |
|Client_Demographic_Details|First_Language_Code        |First language code                                  |
|Client_Demographic_Details|First_Language_Description |First language description                           |
|Client_Demographic_Details|First_Language_National_Code|First language national code                         |
|Client_Demographic_Details|Gender_Code                |Gender code                                          |
|Client_Demographic_Details|Gender_Description         |Gender description                                   |
|Client_Demographic_Details|Interpreter_Required       |Interpreter required                                 |
|Client_Demographic_Details|Last_Updated               |Last updated                                         |
|Client_Demographic_Details|MainCarerRelationship      |Main Carer Relationship                              |
|Client_Demographic_Details|Marital_Status_Code        |Marital status code                                  |
|Client_Demographic_Details|Marital_Status_Description |Marital status description                           |
|Client_Demographic_Details|Marital_Status_National_Code|Marital status national code                         |
|Client_Demographic_Details|NNN_Status_Code            |National NHS Number status code                      |
|Client_Demographic_Details|NNN_Status_Description     |National NHS Number status description               |
|Client_Demographic_Details|Nationality_Code           |Nationality code                                     |
|Client_Demographic_Details|Nationality_Description    |Nationality description                              |
|Client_Demographic_Details|Nationality_National_Code  |Nationality national code                            |
|Client_Demographic_Details|Non_Client                 |Indicator to show if client or other                 |
|Client_Demographic_Details|Occupation                 |Occupation                                           |
|Client_Demographic_Details|Outpatient_Medical_Admin_Record|Set to 1 if there is a outpatient medical admin record|
|Client_Demographic_Details|Partner_Occupation         |Partner occupation                                   |
|Client_Demographic_Details|Person_Role_Code           |Person role code                                     |
|Client_Demographic_Details|Person_Role_Description    |Person role description                              |
|Client_Demographic_Details|Religion_Code              |Religion code                                        |
|Client_Demographic_Details|Religion_Description       |Religion description                                 |
|Client_Demographic_Details|Religion_National_Code     |Religion national code                               |
|Client_Demographic_Details|Reports_File               |Reports file flag                                    |
|Client_Demographic_Details|SEN_File                   |Special Education Needs file                         |
|Client_Demographic_Details|Sensitive_Flag             |Is information sensitive                             |
|Client_Demographic_Details|SequenceID                 |Unique identifier for the row                        |
|Client_Demographic_Details|crate_pk                   |crate primary key                                    |
## Client_Family
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_Family    |Legal_Status_Code          |Legal status of the relationship                     |
|Client_Family    |Legal_Status_Description   |Legal status description                             |
|Client_Family    |Parental_Responsibility_Code|Details of parental relations                        |
|Client_Family    |Parental_Responsibility_Description|Parental responsibility description                  |
|Client_Family    |Relationship_Code          |Relationship to client                               |
|Client_Family    |Relationship_Description   |Relationship description                             |
|Client_Family    |Relationship_National_Code |Relationship national code                           |
|Client_Family    |crate_pk                   |crate primary key                                    |
## Client_GP_History
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_GP_History|Allocation                 |Allocation of GP                                     |
|Client_GP_History|GP_Code                    |The National Code of the client's GP                 |
|Client_GP_History|GP_Description             |GP description                                       |
|Client_GP_History|GP_Forename                |GP forename                                          |
|Client_GP_History|GP_From_Date               |The date the client was first registered with this GP|
|Client_GP_History|GP_National_Code           |GP national code                                     |
|Client_GP_History|GP_Practice_Address_Line_1 |GP practice address line 1                           |
|Client_GP_History|GP_Practice_Address_Line_2 |GP practice address line 2                           |
|Client_GP_History|GP_Practice_Address_Line_3 |GP practice address line 3                           |
|Client_GP_History|GP_Practice_Address_Line_4 |GP practice address line 4                           |
|Client_GP_History|GP_Practice_Address_Line_5 |GP practice address line 5                           |
|Client_GP_History|GP_Practice_Code           |The National Code of the client's GP practice        |
|Client_GP_History|GP_Practice_Description    |GP practice description                              |
|Client_GP_History|GP_Practice_National_Code  |GP practice national code                            |
|Client_GP_History|GP_Practice_Post_Code      |GP practice post code                                |
|Client_GP_History|GP_Surname                 |GP surname                                           |
|Client_GP_History|GP_Title                   |GP title                                             |
|Client_GP_History|GP_To_Date                 |The date the client ceased to be registered with this GP|
|Client_GP_History|HCProviderID               |HCProviderID                                         |
|Client_GP_History|Last_Updated               |Date last updated                                    |
|Client_GP_History|Person_HCP_Provider_ID     |Person hcp provider id                               |
|Client_GP_History|Provider_Type_Code         |Provider type code                                   |
|Client_GP_History|Provider_Type_Description  |Provider type description                            |
|Client_GP_History|crate_pk                   |crate primary key                                    |
## Client_School
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Client_School    |Deleted                    |Deleted                                              |
|Client_School    |School_Address             |School address                                       |
|Client_School    |School_Code                |The school attended by the client                    |
|Client_School    |School_From_Date           |The date the client started attending this school    |
|Client_School    |School_Name                |School name                                          |
|Client_School    |School_To_Date             |The date the client finished attending this school   |
|Client_School    |Unique_Key                 |Unique key                                           |
|Client_School    |crate_pk                   |crate primary key                                    |
## ClientAlert
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ClientAlert      |AlertDate                  |The date the alert was first noted                   |
|ClientAlert      |AlertPriority              |Thepriority of the alert                             |
|ClientAlert      |AlertType                  |The type of this alert                               |
|ClientAlert      |Deleted                    |Logically deleted flag                               |
|ClientAlert      |EnteredBy                  |User alert was entered by                            |
|ClientAlert      |NextReviewDate             |Date when the alert is needed to be reviewed         |
|ClientAlert      |RemovalDate                |Date that the alert is no longer applicable          |
|ClientAlert      |RemovalReason              |Removal reason for the alert                         |
|ClientAlert      |RemovalSystemDate          |The system time stamp of the removal                 |
|ClientAlert      |RemovalUserID              |The RiO user who removed the alert                   |
|ClientAlert      |SequenceID                 |Unique identifier for the row                        |
|ClientAlert      |Significant                |Clients alert is a significant alert - for use in the significant events screen|
|ClientAlert      |SubmitDate                 |The date the alert was recorded on RiO               |
|ClientAlert      |crate_pk                   |crate primary key                                    |
## ClientDocumentPersonalContact
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ClientDocumentPersonalContact|ContactID                  |ContactID                                            |
|ClientDocumentPersonalContact|DocumentID                 |Identifier of the associated document                |
|ClientDocumentPersonalContact|crate_pk                   |crate primary key                                    |
## CPAParticipants
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|CPAParticipants  |Attended                   |Set to 1 if attended                                 |
|CPAParticipants  |Code                       |CPA participant type code                            |
|CPAParticipants  |Contributed                |Set to 1 if contributed                              |
|CPAParticipants  |ID                         |CPA participant's ID                                 |
|CPAParticipants  |Invited                    |Set to 1 if invited                                  |
|CPAParticipants  |InvitedToContribute        |Set to 1 if invited to contribute                    |
|CPAParticipants  |Relationship               |CPA participant's relationship                       |
|CPAParticipants  |ReviewID                   |Identifier for CPA review                            |
|CPAParticipants  |ReviewParentID             |Review Parent ID code                                |
|CPAParticipants  |SequenceId                 |Unique sequence ID                                   |
|CPAParticipants  |crate_pk                   |crate primary key                                    |
## Deceased
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Deceased         |DateofDeath                |Date of Death                                        |
|Deceased         |crate_pk                   |crate primary key                                    |
## Diagnosis
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Diagnosis        |Coding_Scheme              |Coding scheme that 'diagnosis' is from               |
|Diagnosis        |Diagnosis                  |Diagnosis                                            |
|Diagnosis        |Diagnosis_Code             |Diagnosis code                                       |
|Diagnosis        |Diagnosis_End_Date         |Date diagnosis ended for client                      |
|Diagnosis        |Diagnosis_Start_Date       |Date diagnosis made on client                        |
|Diagnosis        |Entered_By_Code            |Entered by code                                      |
|Diagnosis        |Entered_By_Consultant_Flag |Entered by consultant flag                           |
|Diagnosis        |Entered_By_Email           |Entered by email                                     |
|Diagnosis        |Entered_By_First_Name      |Entered by first name                                |
|Diagnosis        |Entered_By_Main_Specialty_Code|Entered by main specialty code                       |
|Diagnosis        |Entered_By_Main_Specialty_Description|Entered by main specialty description                |
|Diagnosis        |Entered_By_Main_Specialty_National_Code|Entered by main specialty national code              |
|Diagnosis        |Entered_By_Organisation_Type_Code|Entered by organisation type code                    |
|Diagnosis        |Entered_By_Organisation_Type_Description|Entered by organisation type description             |
|Diagnosis        |Entered_By_Primary_Team_Code|Entered by primary team code                         |
|Diagnosis        |Entered_By_Primary_Team_Description|Entered by primary team description                  |
|Diagnosis        |Entered_By_Professional_Group_Code|Entered by professional group code                   |
|Diagnosis        |Entered_By_Professional_Group_Description|Entered by professional group description            |
|Diagnosis        |Entered_By_Resp_Clinician_Profession_Code|Entered by resp clinician profession code            |
|Diagnosis        |Entered_By_Resp_Clinician_Profession_Description|Entered by resp clinician profession description     |
|Diagnosis        |Entered_By_Surname         |Entered by surname                                   |
|Diagnosis        |Entered_By_Title           |Entered by title                                     |
|Diagnosis        |Entry_Date                 |Date diagnosis was entered                           |
|Diagnosis        |Removal_By_Code            |Removal by code                                      |
|Diagnosis        |Removal_By_Consultant_Flag |Removal by consultant flag                           |
|Diagnosis        |Removal_By_Email           |Removal by email                                     |
|Diagnosis        |Removal_By_First_Name      |Removal by first name                                |
|Diagnosis        |Removal_By_Main_Specialty_Code|Removal by main specialty code                       |
|Diagnosis        |Removal_By_Main_Specialty_Description|Removal by main specialty description                |
|Diagnosis        |Removal_By_Main_Specialty_National_Code|Removal by main specialty national code              |
|Diagnosis        |Removal_By_Organisation_Type_Code|Removal by organisation type code                    |
|Diagnosis        |Removal_By_Organisation_Type_Description|Removal by organisation type description             |
|Diagnosis        |Removal_By_Primary_Team_Code|Removal by primary team code                         |
|Diagnosis        |Removal_By_Primary_Team_Description|Removal by primary team description                  |
|Diagnosis        |Removal_By_Professional_Group_Code|Removal by professional group code                   |
|Diagnosis        |Removal_By_Professional_Group_Description|Removal by professional group description            |
|Diagnosis        |Removal_By_Resp_Clinician_Profession_Code|Removal by resp clinician profession code            |
|Diagnosis        |Removal_By_Resp_Clinician_Profession_Description|Removal by resp clinician profession description     |
|Diagnosis        |Removal_By_Surname         |Removal by surname                                   |
|Diagnosis        |Removal_By_Title           |Removal by title                                     |
|Diagnosis        |Removal_Date               |Removal date                                         |
|Diagnosis        |Removal_Reason_Code        |Reason for removing the diagnosis                    |
|Diagnosis        |Removal_Reason_Description |Removal reason description                           |
|Diagnosis        |SequenceID                 |Unique identifier for the row                        |
|Diagnosis        |crate_pk                   |crate primary key                                    |
## diagnosiscodeupdate
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|diagnosiscodeupdate|CODE                       |Diagnosis code                                       |
|diagnosiscodeupdate|DESCRIPTION                |Description of the diagnosis                         |
|diagnosiscodeupdate|NationalCode               |National Code for the diagnosis                      |
|diagnosiscodeupdate|codingscheme               |Coding scheme that the code belongs to               |
|diagnosiscodeupdate|crate_pk                   |crate primary key                                    |
|diagnosiscodeupdate|deleted                    |Logically deleted flag                               |
## DiagnosisConfirmedUFCE
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|DiagnosisConfirmedUFCE|ConfirmationDate           |For UFCE and Referrals, this date come from the confirmation date in the front end. For FCE and CPA it will be current date time|
|DiagnosisConfirmedUFCE|Diagnosis1                 |Primary diagnosis                                    |
|DiagnosisConfirmedUFCE|Diagnosis10                |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis11                |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis12                |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis13                |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis14                |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis2                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis3                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis4                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis5                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis6                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis7                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis8                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|Diagnosis9                 |Secondary diagnosis                                  |
|DiagnosisConfirmedUFCE|DiagnosisBy                |Internal RiO identifier of the user who perfomed the diagnosis|
|DiagnosisConfirmedUFCE|DiagnosisConfirmed         |Date time the diagnosis is confirmed                 |
|DiagnosisConfirmedUFCE|EventNumber                |Event number from the IMS event                      |
|DiagnosisConfirmedUFCE|SequenceID                 |Unique identifier for the row                        |
|DiagnosisConfirmedUFCE|crate_pk                   |crate primary key                                    |
## ImsBayClosure
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsBayClosure    |BayCode                    |The bay code of this bay                             |
|ImsBayClosure    |ClosureDate                |The date that this ward closure commenced            |
|ImsBayClosure    |ClosureReason              |Reason for bay closure                               |
|ImsBayClosure    |ReopenDate                 |Reopen date                                          |
|ImsBayClosure    |ReopenReason               |Reason for bay reopen                                |
|ImsBayClosure    |SequenceID                 |Unique sequence ID                                   |
|ImsBayClosure    |WardCode                   |The ward code of this ward                           |
|ImsBayClosure    |crate_pk                   |crate primary key                                    |
## ImsBed
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsBed           |BayCode                    |Bay code                                             |
|ImsBed           |BedCreatedDate             |The date the bed was created within the bay          |
|ImsBed           |BedDeletedDate             |The date the bed was deleted from the bay            |
|ImsBed           |BedNumber                  |The number of the bed. Beds are numbered sequentially from 1 per bay|
|ImsBed           |BedType                    |They type of the bed as defined in the master table ImsBedType|
|ImsBed           |CloseFlag                  |When set (1) indicates that this bed is not available for use|
|ImsBed           |SequenceID                 |Unique sequence ID                                   |
|ImsBed           |Virtual                    |If set (1) indicates that the bed is virtual         |
|ImsBed           |WardCode                   |Ward code                                            |
|ImsBed           |crate_pk                   |crate primary key                                    |
## ImsBedClosure
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsBedClosure    |BayCode                    |Bay code                                             |
|ImsBedClosure    |BedNUmber                  |Bed number                                           |
|ImsBedClosure    |ClosureDate                |The date that this bed closure commenced             |
|ImsBedClosure    |ClosureReason              |Closure reason                                       |
|ImsBedClosure    |ReopenDate                 |Reopen date                                          |
|ImsBedClosure    |ReopenReason               |Reopen Reason                                        |
|ImsBedClosure    |SequenceID                 |Unique sequence ID                                   |
|ImsBedClosure    |WardCode                   |Ward Code                                            |
|ImsBedClosure    |crate_pk                   |crate primary key                                    |
## ImsPlannedEventApproval
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsPlannedEventApproval|ApprovalDate               |Event approval date                                  |
|ImsPlannedEventApproval|ApprovedBy                 |Person event approved by                             |
|ImsPlannedEventApproval|CreatedOnDischarge         |This is flagged as 1 if the planned event in question was approved automatically due to the client being dischaged via the bed layout view|
|ImsPlannedEventApproval|EventSeqID                 |Event Sequence ID                                    |
|ImsPlannedEventApproval|EventType                  |Event Type: L = Leave, T = Transfer, D = Discharge, S = Sleepover|
|ImsPlannedEventApproval|SequenceID                 |Unique identifier for the row                        |
|ImsPlannedEventApproval|WithdrawnBy                |Withdrawn By                                         |
|ImsPlannedEventApproval|WithdrawnDate              |Withdrawn Date                                       |
|ImsPlannedEventApproval|crate_pk                   |crate primary key                                    |
## ImsWardBedAvailability
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsWardBedAvailability|AvailableBeds              |Available Beds                                       |
|ImsWardBedAvailability|BudgetedBeds               |Budgeted Beds                                        |
|ImsWardBedAvailability|EndDate                    |End Date                                             |
|ImsWardBedAvailability|RegisteredBeds             |Registered Beds                                      |
|ImsWardBedAvailability|SequenceID                 |Unique identifier for the row                        |
|ImsWardBedAvailability|StartDate                  |Start Date                                           |
|ImsWardBedAvailability|WardCode                   |Ward Code for bed availability                       |
|ImsWardBedAvailability|crate_pk                   |crate primary key                                    |
## ImsWardClosure
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ImsWardClosure   |ClosureDate                |The date the ward was closed                         |
|ImsWardClosure   |ClosureReason              |The reason the ward was closed                       |
|ImsWardClosure   |ReopenDate                 |Reopen Date                                          |
|ImsWardClosure   |ReopenReason               |Reopen Reason                                        |
|ImsWardClosure   |SequenceID                 |Unique Sequence ID                                   |
|ImsWardClosure   |WardCode                   |The Ward Code of the closed ward                     |
|ImsWardClosure   |crate_pk                   |crate primary key                                    |
## MntClientCTOConditionDetails
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|MntClientCTOConditionDetails|CTOConditionDateTime       |Used internally by RiO to control concurrent record access|
|MntClientCTOConditionDetails|CTOConditionDetail         |Free text details of the CTO conditions              |
|MntClientCTOConditionDetails|Deleted                    |Record deletion flag                                 |
|MntClientCTOConditionDetails|DeletedReason              |Reason for record deletion                           |
|MntClientCTOConditionDetails|MntSequenceId              |The associated MHA  section detail record            |
|MntClientCTOConditionDetails|SequenceId                 |Unique identifier for the row                        |
|MntClientCTOConditionDetails|UserId                     |The RiO user who created the record                  |
|MntClientCTOConditionDetails|crate_pk                   |crate primary key                                    |
## mntClientSectionCTORecallDetails
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|mntClientSectionCTORecallDetails|ApplicationMadeBy          |Application made by                                  |
|mntClientSectionCTORecallDetails|DecisionDate               |Date recall Decision made                            |
|mntClientSectionCTORecallDetails|Deleted                    |Logically Deleted flag                               |
|mntClientSectionCTORecallDetails|EventNum                   |Client section Event number                          |
|mntClientSectionCTORecallDetails|InpatientFlg               |Flag indicates if event relates to an inpatient      |
|mntClientSectionCTORecallDetails|Location                   |Location client Is recalled from                     |
|mntClientSectionCTORecallDetails|MntSequenceId              |Client section sequence ID                           |
|mntClientSectionCTORecallDetails|Outcome                    |Recall Outcome                                       |
|mntClientSectionCTORecallDetails|RecallDate                 |Date of recall                                       |
|mntClientSectionCTORecallDetails|RecallMethod               |Recall method code                                   |
|mntClientSectionCTORecallDetails|RecallNoticeDateTime       |Date and time notice was sent/delivered              |
|mntClientSectionCTORecallDetails|SequenceID                 |Unique Sequence ID                                   |
|mntClientSectionCTORecallDetails|crate_pk                   |crate primary key                                    |
## mntClientSectionDetailRights
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|mntClientSectionDetailRights|Deleted                    |Logically Deleted flag                               |
|mntClientSectionDetailRights|IMHA                       |Flag variable                                        |
|mntClientSectionDetailRights|LevelOfUnderstanding       |Comments on level of understanding                   |
|mntClientSectionDetailRights|MntSequenceId              |Client section sequence ID                           |
|mntClientSectionDetailRights|RightsReadDateTime         |Date Rights read to Client                           |
|mntClientSectionDetailRights|RightsReadHCP              |HCP who read rights to the client                    |
|mntClientSectionDetailRights|RightsReadNonHCP           |Clients rights have been read by a non HCP           |
|mntClientSectionDetailRights|SequenceID                 |Unique Sequence ID                                   |
|mntClientSectionDetailRights|crate_pk                   |crate primary key                                    |
## MntClientSectionExpiryExtension
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|MntClientSectionExpiryExtension|ExtendedByDays             |Number of days the section has been extended by      |
|MntClientSectionExpiryExtension|ExtensionReason            |Reason for Expiry extension                          |
|MntClientSectionExpiryExtension|ExtensionReasonSequenceID  |Expiry Reason sequence ID                            |
|MntClientSectionExpiryExtension|NewExpiryDateTime          |Revised expiry Date/Time                             |
|MntClientSectionExpiryExtension|NewReviewDateTime          |Revised review Date/Time                             |
|MntClientSectionExpiryExtension|OriginalExpiryDateTime     |Original expiry Date/Time                            |
|MntClientSectionExpiryExtension|OriginalReviewDateTime     |Original review Date/Time                            |
|MntClientSectionExpiryExtension|ReversalDate               |Date/Time of any reversal                            |
|MntClientSectionExpiryExtension|SectionDetailSequenceID    |Section Detail sequence ID                           |
|MntClientSectionExpiryExtension|SequenceID                 |Unique Sequence ID                                   |
|MntClientSectionExpiryExtension|crate_pk                   |crate primary key                                    |
## mntClientSectionObjectionDetail
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|mntClientSectionObjectionDetail|CourtDecisionDt            |Date of courts decision                              |
|mntClientSectionObjectionDetail|CourtOutcome               |Court Decision                                       |
|mntClientSectionObjectionDetail|Deleted                    |Logical Delete flag                                  |
|mntClientSectionObjectionDetail|DispApplicant              |Indicates who raised the objection. The available values are|
|                 |                           | - Client                                            |
|                 |                           | - AMHCP                                             |
|mntClientSectionObjectionDetail|DispDate                   |Date & Time of objection                             |
|mntClientSectionObjectionDetail|ExpiryDateExtended         |Set to 1 to allow section to be extended             |
|mntClientSectionObjectionDetail|MntSequenceId              |Client section sequence ID                           |
|mntClientSectionObjectionDetail|SequenceID                 |Unique Sequence ID                                   |
|mntClientSectionObjectionDetail|crate_pk                   |crate primary key                                    |
## mntClientSectionTreatmentDetails
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|mntClientSectionTreatmentDetails|Deleted                    |Logically Deleted flag                               |
|mntClientSectionTreatmentDetails|EventNum                   |Client section Event number                          |
|mntClientSectionTreatmentDetails|SequenceID                 |Unique Sequence ID                                   |
|mntClientSectionTreatmentDetails|TreatmentDate              |Date/Time of treatment                               |
|mntClientSectionTreatmentDetails|TreatmentEndDate           |Date/Time of the end of treatment                    |
|mntClientSectionTreatmentDetails|TreatmentReceivedFlg       |Flag to indicate if treatment has been received      |
|mntClientSectionTreatmentDetails|crate_pk                   |crate primary key                                    |
## ParentGuardianImport
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|ParentGuardianImport|AGE                        |AGE                                                  |
|ParentGuardianImport|AssessmentDate             |Assessment Date                                      |
|ParentGuardianImport|ScCond                     |Subscore: Conduct Problems                           |
|ParentGuardianImport|ScEmot                     |Subscore: Emotional Symptoms                         |
|ParentGuardianImport|ScHyper                    |Subscore: Hyperactivity/Inattention                  |
|ParentGuardianImport|ScPeer                     |Subscore: Peer Problems                              |
|ParentGuardianImport|ScProsoc                   |Subscore: Prosocial Behaviour                        |
|ParentGuardianImport|ScTotaldiff                |Total Difficulties Score                             |
|ParentGuardianImport|crate_pk                   |crate primary key                                    |
|ParentGuardianImport|q1                         |Question 1                                           |
|ParentGuardianImport|q10                        |Question 10                                          |
|ParentGuardianImport|q11                        |Question 11                                          |
|ParentGuardianImport|q12                        |Question 12                                          |
|ParentGuardianImport|q13                        |Question 13                                          |
|ParentGuardianImport|q14                        |Question 14                                          |
|ParentGuardianImport|q15                        |Question 15                                          |
|ParentGuardianImport|q16                        |Question 16                                          |
|ParentGuardianImport|q17                        |Question 17                                          |
|ParentGuardianImport|q18                        |Question 18                                          |
|ParentGuardianImport|q19                        |Question 19                                          |
|ParentGuardianImport|q2                         |Question 2                                           |
|ParentGuardianImport|q20                        |Question 20                                          |
|ParentGuardianImport|q21                        |Question 21                                          |
|ParentGuardianImport|q22                        |Question 22                                          |
|ParentGuardianImport|q23                        |Question 23                                          |
|ParentGuardianImport|q24                        |Question 24                                          |
|ParentGuardianImport|q25                        |Question 25                                          |
|ParentGuardianImport|q3                         |Question 3                                           |
|ParentGuardianImport|q30A                       |Question 30A                                         |
|ParentGuardianImport|q30B                       |Question 30B                                         |
|ParentGuardianImport|q30C                       |Question 30C                                         |
|ParentGuardianImport|q30D                       |Question 30D                                         |
|ParentGuardianImport|q31                        |Question 31                                          |
|ParentGuardianImport|q4                         |Question 4                                           |
|ParentGuardianImport|q5                         |Question 5                                           |
|ParentGuardianImport|q6                         |Question 6                                           |
|ParentGuardianImport|q7                         |Question 7                                           |
|ParentGuardianImport|q8                         |Question 8                                           |
|ParentGuardianImport|q9                         |Question 9                                           |
|ParentGuardianImport|Q27                        |Question 27                                          |
|ParentGuardianImport|Q28                        |Question 28                                          |
|ParentGuardianImport|Q29                        |Question 29                                          |
|ParentGuardianImport|type12_NoteID              |ID                                                   |
|ParentGuardianImport|type12_UpdatedBy           |Person/System who entered the data                   |
|ParentGuardianImport|type12_UpdatedDate         |                                                     |
## PrgProblemTypes
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|PrgProblemTypes  |EntryDate                  |Date/time entry was made                             |
|PrgProblemTypes  |PrgSequenceID              |Pointer to the main progress note record             |
|PrgProblemTypes  |ProblemCategoryCode        |Associated Care Plan category                        |
|PrgProblemTypes  |ProblemTypeCode            |Care plan problem Code                               |
|PrgProblemTypes  |SequenceID                 |Unique sequence ID                                   |
|PrgProblemTypes  |UserID                     |RiO User who made the entry                          |
|PrgProblemTypes  |crate_pk                   |crate primary key                                    |
## Referral
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Referral         |Administrative_Category_Code|Administrative category Code from drop down          |
|Referral         |Administrative_Category_Description|Administrative category description                  |
|Referral         |CAB_Referral               |Set to 1 if CAB Referral (referral to the Cambridge Centre for Paediatric Neuropsychological Rehabilitation)|
|Referral         |CAMHSServiceTier           |CAMHSServiceTier                                     |
|Referral         |CareProfessionalStaffGroup |CareProfessionalStaffGroup                           |
|Referral         |Care_Spell_End_Date        |Care spell end date                                  |
|Referral         |Care_Spell_Mental_Health   |Care spell mental health (It's a structured program designed to address a specific health need, often one that has been nationally prioritized. A Care Spell can involve various health and social care agencies working together to provide the necessary support.)|
|Referral         |Care_Spell_Number          |Care spell number                                    |
|Referral         |Care_Spell_Specialty_Code  |Care spell specialty code                            |
|Referral         |Care_Spell_Specialty_Description|Care spell specialty description                     |
|Referral         |Care_Spell_Specialty_National_Code|Care spell specialty national code                   |
|Referral         |Care_Spell_Start_Date      |Care spell start date                                |
|Referral         |Discharge_Allocation       |PCT Code of client at time of discharge              |
|Referral         |Discharge_DateTime         |Discharge Date Time                                  |
|Referral         |Discharge_HCP_Code         |HCP Code of HCP who discharged referral              |
|Referral         |Discharge_HCP_Consultant_Flag|Discharge hcp consultant flag                        |
|Referral         |Discharge_HCP_Email        |Discharge hcp email                                  |
|Referral         |Discharge_HCP_First_Name   |Discharge hcp first name                             |
|Referral         |Discharge_HCP_Main_Specialty_Code|Discharge hcp main specialty code                    |
|Referral         |Discharge_HCP_Main_Specialty_Description|Discharge hcp main specialty description             |
|Referral         |Discharge_HCP_Main_Specialty_National_Code|Discharge hcp main specialty national code           |
|Referral         |Discharge_HCP_Organisation_Type_Code|Discharge hcp organisation type code                 |
|Referral         |Discharge_HCP_Organisation_Type_Description|Discharge hcp organisation type description          |
|Referral         |Discharge_HCP_Primary_Team_Code|Discharge hcp primary team code                      |
|Referral         |Discharge_HCP_Primary_Team_Description|Discharge hcp primary team description               |
|Referral         |Discharge_HCP_Professional_Group_Code|Discharge hcp professional group code                |
|Referral         |Discharge_HCP_Professional_Group_Description|Discharge hcp professional group description         |
|Referral         |Discharge_HCP_Resp_Clinician_Profession_Code|Discharge hcp resp clinician profession code         |
|Referral         |Discharge_HCP_Resp_Clinician_Profession_Description|Discharge hcp resp clinician profession description  |
|Referral         |Discharge_HCP_Surname      |Discharge hcp surname                                |
|Referral         |Discharge_HCP_Title        |Discharge hcp title                                  |
|Referral         |Discharge_Reason           |Discharge Reason Code                                |
|Referral         |Discharged_On_Admission    |Set to 1 if patient discharged on admission          |
|Referral         |EnquiryNumber              |Identifier for initial enquiry                       |
|Referral         |External_Referral_Id       |External referral for Contacts module                |
|Referral         |GenOverseasStatus          |GenOverseasStatus                                    |
|Referral         |HCP_Referred_To_Code       |Deprecated field – join onto AmsReferralAllocation for correct HCP allocation.|
|Referral         |HCP_Referred_To_Consultant_Flag|HCP referred to consultant flag                      |
|Referral         |HCP_Referred_To_Email      |HCP referred to email                                |
|Referral         |HCP_Referred_To_First_Name |HCP referred to first name                           |
|Referral         |HCP_Referred_To_Main_Specialty_Code|HCP referred to main specialty code                  |
|Referral         |HCP_Referred_To_Main_Specialty_Description|HCP referred to main specialty description           |
|Referral         |HCP_Referred_To_Main_Specialty_National_Code|HCP referred to main specialty national code         |
|Referral         |HCP_Referred_To_Organisation_Type_Code|HCP referred to organisation type code               |
|Referral         |HCP_Referred_To_Organisation_Type_Description|HCP referred to organisation type description        |
|Referral         |HCP_Referred_To_Primary_Team_Code|HCP referred to primary team code                    |
|Referral         |HCP_Referred_To_Primary_Team_Description|HCP referred to primary team description             |
|Referral         |HCP_Referred_To_Professional_Group_Code|HCP referred to professional group code              |
|Referral         |HCP_Referred_To_Professional_Group_Description|HCP referred to professional group description       |
|Referral         |HCP_Referred_To_Resp_Clinician_Profession_Code|HCP referred to resp clinician profession code       |
|Referral         |HCP_Referred_To_Resp_Clinician_Profession_Description|HCP referred to resp clinician profession description|
|Referral         |HCP_Referred_To_Surname    |HCP referred to surname                              |
|Referral         |HCP_Referred_To_Title      |HCP referred to title                                |
|Referral         |HcpAllocationDate          |Deprecated. See AmsReferralAllocation                |
|Referral         |IWS_Held                   |Date referral was placed on hold on Interactive Worksheet|
|Referral         |Likely_Funder              |Private funding indicator                            |
|Referral         |Likely_Legal_Status        |Client Likely Legal Status                           |
|Referral         |OtherReferralReason        |OtherReferralReason                                  |
|Referral         |Patient_Area_Code          |Patient Area Code                                    |
|Referral         |Patient_Area_Description   |Patient area description                             |
|Referral         |RTT_Code                   |Associated RTT Waiting List                          |
|Referral         |Referral_Accepted_Date     |Date of referral acceptance                          |
|Referral         |Referral_ActionDate        |Referral Action Date                                 |
|Referral         |Referral_Allocation        |PCT Code of client at time of referral               |
|Referral         |Referral_DateTime          |Referral Date Time                                   |
|Referral         |Referral_Number            |Referral Number                                      |
|Referral         |Referral_Reason_Code       |Referral Reason Code from drop down                  |
|Referral         |Referral_Reason_Description|Referral reason description                          |
|Referral         |Referral_Reason_National_Code_CAMHS|Referral reason national code camhs                  |
|Referral         |Referral_Reason_National_Code_CIDS|Referral reason national code cids                   |
|Referral         |Referral_Received_Date     |Date referral was received                           |
|Referral         |Referral_Source            |Referral source                                      |
|Referral         |Referred_Consultant_Code   |Consultant Referred from                             |
|Referral         |Referred_Consultant_Consultant_Flag|Referred consultant consultant flag                  |
|Referral         |Referred_Consultant_Email  |Referred consultant email                            |
|Referral         |Referred_Consultant_First_Name|Referred consultant first name                       |
|Referral         |Referred_Consultant_Main_Specialty_Code|Referred consultant main specialty code              |
|Referral         |Referred_Consultant_Main_Specialty_Description|Referred consultant main specialty description       |
|Referral         |Referred_Consultant_Main_Specialty_National_Code|Referred consultant main specialty national code     |
|Referral         |Referred_Consultant_Organisation_Type_Code|Referred consultant organisation type code           |
|Referral         |Referred_Consultant_Organisation_Type_Description|Referred consultant organisation type description    |
|Referral         |Referred_Consultant_Primary_Team_Code|Referred consultant primary team code                |
|Referral         |Referred_Consultant_Primary_Team_Description|Referred consultant primary team description         |
|Referral         |Referred_Consultant_Professional_Group_Code|Referred consultant professional group code          |
|Referral         |Referred_Consultant_Professional_Group_Description|Referred consultant professional group description   |
|Referral         |Referred_Consultant_Resp_Clinician_Profession_Code|Referred consultant resp clinician profession code   |
|Referral         |Referred_Consultant_Resp_Clinician_Profession_Description|Referred consultant resp clinician profession description|
|Referral         |Referred_Consultant_Surname|Referred consultant surname                          |
|Referral         |Referred_Consultant_Title  |Referred consultant title                            |
|Referral         |Referred_Ward_Code         |Ward referred from                                   |
|Referral         |Referred_Ward_Description  |Referred ward description                            |
|Referral         |Referrer                   |Free Text referrer, for when other source is used    |
|Referral         |Referrer_Other             |Free Text field for other referrer                   |
|Referral         |ReferringOrganisationCode  |ReferringOrganisationCode                            |
|Referral         |Referring_Consultant_Cons_Code|Code of HCP if referred by consultant. The link used is dependant on the behaviour of the referral source. If AmsReferralSource.Behaviour is set to CS then the ReferringConsultant column is derived from GenHospitalConsultant.ConsultantID. Otherwise if AmsReferralSource.Behaviour is set to CH then the column is GenHCP.GenHCPCode.|
|Referral         |Referring_Consultant_Cons_Consultant_Flag|Referring consultant cons consultant flag            |
|Referral         |Referring_Consultant_Cons_Email|Referring consultant cons email                      |
|Referral         |Referring_Consultant_Cons_First_Name|Referring consultant cons first name                 |
|Referral         |Referring_Consultant_Cons_Main_Specialty_Code|Referring consultant cons main specialty code        |
|Referral         |Referring_Consultant_Cons_Main_Specialty_Description|Referring consultant cons main specialty description |
|Referral         |Referring_Consultant_Cons_Main_Specialty_National_Code|Referring consultant cons main specialty national code|
|Referral         |Referring_Consultant_Cons_Organisation_Type_Code|Referring consultant cons organisation type code     |
|Referral         |Referring_Consultant_Cons_Organisation_Type_Description|Referring consultant cons organisation type description|
|Referral         |Referring_Consultant_Cons_Primary_Team_Code|Referring consultant cons primary team code          |
|Referral         |Referring_Consultant_Cons_Primary_Team_Description|Referring consultant cons primary team description   |
|Referral         |Referring_Consultant_Cons_Professional_Group_Code|Referring consultant cons professional group code    |
|Referral         |Referring_Consultant_Cons_Professional_Group_Description|Referring consultant cons professional group description|
|Referral         |Referring_Consultant_Cons_Resp_Clinician_Profession_Code|Referring consultant cons resp clinician profession code|
|Referral         |Referring_Consultant_Cons_Resp_Clinician_Profession_Description|Referring consultant cons resp clinician profession description|
|Referral         |Referring_Consultant_Cons_Surname|Referring consultant cons surname                    |
|Referral         |Referring_Consultant_Cons_Title|Referring consultant cons title                      |
|Referral         |Referring_Consultant_HCP_First_Name|Referring consultant hcp first name                  |
|Referral         |Referring_Consultant_HCP_ID|Referring consultant hcp id                          |
|Referral         |Referring_Consultant_HCP_Specialty_Code|Referring consultant hcp specialty code              |
|Referral         |Referring_Consultant_HCP_Specialty_Description|Referring consultant hcp specialty description       |
|Referral         |Referring_Consultant_HCP_Surname|Referring consultant hcp surname                     |
|Referral         |Referring_GP_Code          |Code of GP if referred by a GP                       |
|Referral         |Referring_GP_Practice_Code |Practice Code of referring GP                        |
|Referral         |Removal_Code               |Method of removal: ‘AmsDisc’ or ‘Outcome’            |
|Referral         |Removal_DateTime           |Date referral was removed                            |
|Referral         |Removal_User_Code          |User referral was removed by                         |
|Referral         |Removal_User_Consultant_Flag|Removal user consultant flag                         |
|Referral         |Removal_User_Email         |Removal user email                                   |
|Referral         |Removal_User_First_Name    |Removal user first name                              |
|Referral         |Removal_User_Main_Specialty_Code|Removal user main specialty code                     |
|Referral         |Removal_User_Main_Specialty_Description|Removal user main specialty description              |
|Referral         |Removal_User_Main_Specialty_National_Code|Removal user main specialty national code            |
|Referral         |Removal_User_Organisation_Type_Code|Removal user organisation type code                  |
|Referral         |Removal_User_Organisation_Type_Description|Removal user organisation type description           |
|Referral         |Removal_User_Primary_Team_Code|Removal user primary team code                       |
|Referral         |Removal_User_Primary_Team_Description|Removal user primary team description                |
|Referral         |Removal_User_Professional_Group_Code|Removal user professional group code                 |
|Referral         |Removal_User_Professional_Group_Description|Removal user professional group description          |
|Referral         |Removal_User_Resp_Clinician_Profession_Code|Removal user resp clinician profession code          |
|Referral         |Removal_User_Resp_Clinician_Profession_Description|Removal user resp clinician profession description   |
|Referral         |Removal_User_Surname       |Removal user surname                                 |
|Referral         |Removal_User_Title         |Removal user title                                   |
|Referral         |SequenceID                 |Unique identifier for the row                        |
|Referral         |Service_Referred_To_Code   |Code of any Service the referral is linked to        |
|Referral         |Service_Referred_To_Description|Service referred to description                      |
|Referral         |Specialty_Referred_To_Code |Specialty Code of Specialty referred to              |
|Referral         |Specialty_Referred_To_Description|Specialty referred to description                    |
|Referral         |Team_Referred_To_Classification_Group_Code|Team referred to classification group code           |
|Referral         |Team_Referred_To_Classification_Group_Description|Team referred to classification group description    |
|Referral         |Team_Referred_To_Code      |Code of team referred to if Team Referral            |
|Referral         |Team_Referred_To_Description|Team referred to description                         |
|Referral         |Urgency_Code               |Urgency Code of referral                             |
|Referral         |Urgency_Description        |Urgency description                                  |
|Referral         |Waiting_List_ID            |Associated Waiting list                              |
|Referral         |crate_pk                   |crate pk                                             |
## Referral_Team_History
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|Referral_Team_History|Current_At_Discharge       |Set to 1 if this was the allocated team when the referral was discharged.|
|Referral_Team_History|End_Date                   |End date of team allocation                          |
|Referral_Team_History|Referral_Key               |Referral key                                         |
|Referral_Team_History|SequenceID                 |Unique identifier for the row                        |
|Referral_Team_History|Start_Date                 |Start date of team allocation                        |
|Referral_Team_History|Team_Classification_Group_Code|Team classification group code                       |
|Referral_Team_History|Team_Classification_Group_Description|Team classification group description                |
|Referral_Team_History|Team_Code                  |Code of team allocated to referral                   |
|Referral_Team_History|Team_Description           |Team description                                     |
|Referral_Team_History|crate_pk                   |crate primary key                                    |
## RskRelatedIncidents
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|RskRelatedIncidents|AddendumNum                |                                                     |
|RskRelatedIncidents|Approximate                |                                                     |
|RskRelatedIncidents|EnteredInError             |                                                     |
|RskRelatedIncidents|EntryDate                  |                                                     |
|RskRelatedIncidents|IncidentDate               |                                                     |
|RskRelatedIncidents|IncidentID                 |                                                     |
|RskRelatedIncidents|RiskType                   |                                                     |
|RskRelatedIncidents|SequenceID                 |                                                     |
|RskRelatedIncidents|UserID                     |                                                     |
|RskRelatedIncidents|crate_pk                   |                                                     |
## RskRelatedIncidentsRiskType
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|RskRelatedIncidentsRiskType|IncidentID                 |                                                     |
|RskRelatedIncidentsRiskType|RiskType                   |                                                     |
|RskRelatedIncidentsRiskType|SequenceID                 |                                                     |
|RskRelatedIncidentsRiskType|crate_pk                   |                                                     |
## SNOMED_Client
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|SNOMED_Client    |SC_Added                   |Date record added                                    |
|SNOMED_Client    |SC_Ass_AssDate             |Assessment Date Type (if relevant)                   |
|SNOMED_Client    |SC_Ass_CopiedRow           |Number of records copied from previous version       |
|SNOMED_Client    |SC_Ass_ElementID           |Name of SNOMED element relating to the record        |
|SNOMED_Client    |SC_Ass_FormName            |Name of assessment form where record was entered (if required)|
|SNOMED_Client    |SC_Ass_OrigNoteID          |Type 12 Original Note ID is record entered in assessment form|
|SNOMED_Client    |SC_Ass_PrevSCID            |ID of previous SNOMED_Client record – used for updates|
|SNOMED_Client    |SC_Ass_SubTabRowID         |Note ID of any Assessment Form Sub table where the record is entered (if relevant)|
|SNOMED_Client    |SC_ConceptID               |SNOMED Concept Item ID                               |
|SNOMED_Client    |SC_Deleted                 |Logically Deleted flag                               |
|SNOMED_Client    |SC_DeletedDate             |Date the record was Deleted                          |
|SNOMED_Client    |SC_DescriptionID           |SNOMED Description                                   |
|SNOMED_Client    |SC_ID                      |Unique identifier for the row                        |
|SNOMED_Client    |SC_IDNew                   |SC idnew                                             |
|SNOMED_Client    |SC_ReferringID             |Referral ID                                          |
|SNOMED_Client    |SC_ReferringPageTypeID     |Referral Page Type                                   |
|SNOMED_Client    |SC_SD_ID                   |SC sd id                                             |
|SNOMED_Client    |SC_SD_UserID               |RiO User ID                                          |
|SNOMED_Client    |SC_UserID                  |User who added record                                |
|SNOMED_Client    |crate_pk                   |crate primary key                                    |
## SNOMED_Element
|Table            |Field                      |Description                                          |
|-----------------|---------------------------|-----------------------------------------------------|
|SNOMED_Element   |SE_Deleted                 |Logical Delete Flag                                  |
|SNOMED_Element   |SE_ElementID               |SNOMED Item ID                                       |
|SNOMED_Element   |SE_ElementText             |SNOMED element text                                  |
|SNOMED_Element   |SE_ElementTextSearch       |SNOMED search text                                   |
|SNOMED_Element   |SE_ReferringID             |Sequence ID of target record e.g. Type12_NoteID      |
|SNOMED_Element   |SE_ReferringPageTypeID     |SNOMED functional area                               |
|SNOMED_Element   |SE_ReferringUnsavedID      |Sequence ID of unsaved SNOMED record                 |
|SNOMED_Element   |SE_SC_ID                   |SNOMED Original Element (points to original version) |
|SNOMED_Element   |crate_pk                   |crate primary key                                    |
