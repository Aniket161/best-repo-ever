# best-repo-ever
SELECT label, QualifiedApiName, EndPoint_URL__c, Username__c, Password__c, From_Name__c, From_Address__c,
                                               Template_Id__c, Scheme_Signatory__c, Scheme_Address__c,Scheme_Bank_Account_Number__c,
                                               Scheme_Sort_Code__c,Scheme_Bank_Name__c
                                               FROM API_Service__mdt
 
select id,QualifiedApiName,Tenant_Label__c,TenantLeadFalse_Label__c, Agent_Label__c from MailJetUtility__mdt
select id,isTable__c, Template_Id__c, Custom_Metadata_Label__c, Department__c, Var_Name__c, Object_Name__c, Field_API_Name__c, Where_Check_Field__c , Is_Chaser_Email__c, document__c, Redirect_Link__c, Date_Function__c, Scheme__c, Subject__c, text_body__c from Matching_Temp_Var__c 
