# F1_Query

Delete recored in json tabel :

    delete from jumio_app_v3_json_record where batch_id='V3BATCH001';

    delete from jumio_app_file_exception  where batch_ref ='V3BATCH001';

    delete from jumio_app_file_managements where batch_id='V3BATCH001';

    DELETE FROM jumio_app_v3_json_record;

-----------------------------------------------

Alter record :

    ALTER TABLE jumio_app_selectfordwn ADD COLUMN validation_required VARCHAR(255) NULL;

-----------------------


JUMIO APP V2 Mapping

    INSERT INTO jumio_app_new_v2_mapping (
      id, old_column_name, new_column_name, created_at, user_status, file_name_v2_v3, created_by_id
    ) VALUES
    (1, 'ScanCompletionDateINT', 'ScanCompletionDateINT', '2025-04-01 11:59:21.963+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (2, 'MerchantName', 'MerchantName', '2025-04-01 11:59:21.965+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (3, 'JumioCompany', 'JumioCompany', '2025-04-01 11:59:21.966+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (4, 'DataCenter', 'DataCenter', '2025-04-01 11:59:21.967+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (5, 'ScanMode', 'ScanMode', '2025-04-01 11:59:21.969+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (6, 'BackofficeSteps', 'BackofficeSteps', '2025-04-01 11:59:21.970+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (7, 'CallbackStatus', 'CallbackStatus', '2025-04-01 11:59:21.971+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (8, 'DocumentType', 'DocumentType', '2025-04-01 11:59:21.972+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (9, 'DocumentSubType', 'DocumentSubType', '2025-04-01 11:59:21.973+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (10, 'DocumentCountry', 'DocumentCountry', '2025-04-01 11:59:21.974+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (11, 'DocumentState', 'DocumentState', '2025-04-01 11:59:21.975+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (12, 'AddressExtraction', 'AddressExtraction', '2025-04-01 11:59:21.976+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (13, 'FaceMatch', 'FaceMatch', '2025-04-01 11:59:21.977+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (14, 'DDETasks', 'DDETasks', '2025-04-01 11:59:21.978+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (15, 'RejectReason', 'RejectReason', '2025-04-01 11:59:21.979+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (16, 'RejectInfo', 'RejectInfo', '2025-04-01 11:59:21.980+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (17, 'SLACategory', 'SLACategory', '2025-04-01 11:59:21.981+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (18, 'publicGUID', 'publicGUID', '2025-04-01 11:59:21.982+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (19, 'ScanCreationUTC', 'ScanCreationUTC', '2025-04-01 11:59:21.984+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (20, 'ScanStartDate2', 'ScanStartDate2', '2025-04-01 11:59:21.985+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (21, 'NVIDVerificationTime', 'NVIDVerificationTime', '2025-04-01 11:59:21.987+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (22, 'BODDEUser', 'BODDEUser', '2025-04-01 11:59:21.988+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (23, 'BODDEAgentTime', 'BODDEAgentTime', '2025-04-01 11:59:21.989+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (24, 'BODDEPicLoadingTime', 'BODDEPicLoadingTime', '2025-04-01 11:59:21.990+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (25, 'DataExtractionMethod', 'DataExtractionMethod', '2025-04-01 11:59:21.991+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (26, 'fmSimilarity', 'fmSimilarity', '2025-04-01 11:59:21.992+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (27, 'fmSimilarityScore', 'fmSimilarityScore', '2025-04-01 11:59:21.993+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (28, 'fmValidityReason', 'fmValidityReason', '2025-04-01 11:59:21.994+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (29, 'BOFacematchUser', 'BOFacematchUser', '2025-04-01 11:59:21.995+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (30, 'BOFacematchTime', 'BOFacematchTime', '2025-04-01 11:59:21.996+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (31, 'BOMaskingUser', 'BOMaskingUser', '2025-04-01 11:59:21.997+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (32, 'BOMaskingTime', 'BOMaskingTime', '2025-04-01 11:59:21.998+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (33, 'DDEDataEntryDetails', 'DDEDataEntryDetails', '2025-04-01 11:59:22.000+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (34, 'RiskLevelTriage', 'RiskLevelTriage', '2025-04-01 11:59:22.001+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (35, 'RiskModel', 'RiskModel', '2025-04-01 11:59:22.003+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (36, 'QueuePriority', 'QueuePriority', '2025-04-01 11:59:22.004+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (37, 'QueueGroup', 'queueGroup', '2025-04-01 11:59:22.004+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1);

------------------------------------------------------


JUMIO APP V3 Mapping

    INSERT INTO jumio_app_new_v3_mapping (
      id, old_column_name, new_column_name, created_at, user_status, file_name_v2_v3, created_by_id
    ) VALUES
    (1, 'CompletionDate', 'CompletionDate', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (2, 'Merchant', 'Merchant', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (3, 'DataCenter', 'DataCenter', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (4, 'JumioCompany', 'JumioCompany', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (5, 'SLACategory', 'SLACategory', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (6, 'Workflow', 'Workflow', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (7, 'workflowDefinition', 'workflowDefinition', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (8, 'ScanStatus', 'ScanStatus', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (9, 'DecisionSource', 'DecisionSource', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (10, 'DecisionType', 'DecisionType', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (11, 'scanMode', 'scanMode', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (12, 'DocCountry', 'DocCountry', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (13, 'DocState', 'DocState', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (14, 'Doctype', 'Doctype', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (15, 'DocSubType', 'DocSubType', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (16, 'CallbackStatus', 'CallbackStatus', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (17, 'RejectReason', 'RejectReason', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (18, 'RejectReasonCategory', 'RejectReasonCategory', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (19, 'WorkflowUID', 'WorkflowUID', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (20, 'WFDurationSec', 'WFDurationSec', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (21, 'wfStartedAt', 'wfStartedAt', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (22, 'QueueGroup', 'QueueGroup, queueGroup', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (23, 'QueuePriority', 'QueuePriority', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (24, 'Risk Level', 'Risk Level, bk_riskLevel', '2025-05-15 12:50:12.528+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (25, 'wfDDE_agent', 'wfDDE_agent', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (26, 'wfDDE_agentTime', 'wfDDE_agentTime', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (27, 'wfDDE_queue', 'wfDDE_queue', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (28, 'wfDocVagent', 'wfDocVagent, wfDocV_agent', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (29, 'wfDocVagenttime', 'wfDocVagenttime, wfDocV_agentTime', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (30, 'wfDocVqueue', 'wfDocVqueue, wfDocV_queue', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (31, 'wfMasking_agent', 'wfMasking_agent', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (32, 'wfMasking_agentTime', 'wfMasking_agentTime', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (33, 'wfMasking_queue', 'wfMasking_queue', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (34, 'wfLiveness_agent', 'wfLiveness_agent', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (35, 'wfLiveness_agentTime', 'wfLiveness_agentTime', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (36, 'wfLiveness_queue', 'wfLiveness_queue', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (37, 'wfSimilarity_agent', 'wfSimilarity_agent', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (38, 'wfSimilarity_agentTime', 'wfSimilarity_agentTime', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (39, 'wfSimilarity_queue', 'wfSimilarity_queue', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (40, 'CDATAC_addinfo1', 'CDATAC_addinfo1, CDATAC_addinfo', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (41, 'CEXT_addinfo1', 'CEXT_addinfo1, CEXT_addinfo', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (42, 'CIMGC_addinfo1', 'CIMGC_addinfo1, CIMGC_addinfo', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (43, 'CUSE_addinfo1', 'CUSE_addinfo1, CUSE_addinfo', '2025-05-15 12:50:12.529+05:30', 1, 'V3 Raw 20241228.xlsx', 1),
    (44, 'BackofficeSteps', 'BackofficeSteps', '2025-05-15 18:16:43.023+05:30', 1, 'Auto-generated from V2', 1),
    (45, 'AddressExtraction', 'AddressExtraction', '2025-05-15 18:17:55.065+05:30', 1, 'Auto-generated from V2', 1),
    (46, 'FaceMatch', 'FaceMatch', '2025-05-15 18:18:07.051+05:30', 1, 'Auto-generated from V2', 1),
    (47, 'DDETasks', 'DDETasks', '2025-05-15 18:18:17.380+05:30', 1, 'Auto-generated from V2', 1),
    (48, 'ScanCreationUTC', 'ScanCreationUTC', '2025-05-15 18:18:27.480+05:30', 1, 'Auto-generated from V2', 1),
    (49, 'BODDEPicLoadingTime', 'BODDEPicLoadingTime', '2025-05-15 18:18:47.030+05:30', 1, 'Auto-generated from V2', 1),
    (50, 'DataExtractionMethod', 'DataExtractionMethod', '2025-05-15 18:19:00.283+05:30', 1, 'Auto-generated from V2', 1),
    (51, 'fmSimilarity', 'fmSimilarity', '2025-05-15 18:19:16.709+05:30', 1, 'Auto-generated from V2', 1),
    (52, 'fmSimilarityScore', 'fmSimilarityScore', '2025-05-15 18:19:30.599+05:30', 1, 'Auto-generated from V2', 1),
    (53, 'fmValidityReason', 'fmValidityReason', '2025-05-15 18:20:11.760+05:30', 1, 'Auto-generated from V2', 1),
    (54, 'DDEDataEntryDetails', 'DDEDataEntryDetails', '2025-05-15 18:20:25.326+05:30', 1, 'Auto-generated from V2', 1),
    (55, 'RiskModel', 'RiskModel', '2025-05-15 18:20:36.060+05:30', 1, 'Auto-generated from V2', 1);

---------------------------------------------------


JUMIO APP SELECT FOR DOWNLOAD

 First execute this---1
    
    INSERT INTO jumio_app_selectfordwn (
      id, validation_required, created_at, user_status, created_by_id
    )
    VALUES
    (1, 'Not Required', '2025-05-15 12:57:33.656+0530', 1, 1),
    (2, 'Required', '2025-05-15 13:05:53.318+0530', 1, 1),
    (3, 'Not Required', '2025-05-15 14:34:25.062+0530', 1, 1),
    (4, 'Not Required', '2025-05-15 14:34:35.039+0530', 1, 1),
    (5, 'Not Required', '2025-05-15 14:34:41.889+0530', 1, 1),
    (6, 'Not Required', '2025-05-15 14:35:21.471+0530', 1, 1),
    (7, 'Not Required', '2025-05-15 14:35:53.321+0530', 1, 1),
    (8, 'Not Required', '2025-05-15 14:36:05.955+0530', 1, 1),
    (9, 'Not Required', '2025-05-15 14:52:05.384+0530', 1, 1),
    (10, 'Not Required', '2025-05-15 14:51:34.718+0530', 1, 1),
    (11, 'Not Required', '2025-05-15 14:51:18.071+0530', 1, 1),
    (12, 'Required', '2025-05-15 14:50:51.051+0530', 1, 1),
    (13, 'Required', '2025-05-15 14:47:22.045+0530', 1, 1),
    (14, 'Required', '2025-05-15 14:47:15.793+0530', 1, 1),
    (15, 'Required', '2025-05-15 14:47:06.996+0530', 1, 1),
    (16, 'Required', '2025-05-15 14:46:18.845+0530', 1, 1),
    (17, 'Not Required', '2025-05-15 14:46:11.462+0530', 1, 1),
    (18, 'Not Required', '2025-05-15 14:46:04.031+0530', 1, 1),
    (19, 'Not Required', '2025-05-15 14:44:57.312+0530', 1, 1),
    (20, 'Not Required', '2025-05-15 14:44:32.148+0530', 1, 1),
    (21, 'Not Required', '2025-05-15 14:44:21.783+0530', 1, 1),
    (22, 'Required', '2025-05-15 14:43:35.952+0530', 1, 1),
    (23, 'Required', '2025-05-15 14:43:24.902+0530', 1, 1),
    (24, 'Required', '2025-05-15 14:43:00.306+0530', 1, 1),
    (25, 'Not Required', '2025-05-15 14:42:47.256+0530', 1, 1),
    (26, 'Not Required', '2025-05-15 14:42:31.807+0530', 1, 1),
    (27, 'Not Required', '2025-05-15 14:42:16.406+0530', 1, 1),
    (28, 'Not Required', '2025-05-15 14:41:46.505+0530', 1, 1),
    (29, 'Not Required', '2025-05-15 14:41:29.682+0530', 1, 1),
    (30, 'Not Required', '2025-05-15 14:40:21.710+0530', 1, 1),
    (31, 'Not Required', '2025-05-15 14:39:55.827+0530', 1, 1),
    (32, 'Not Required', '2025-05-15 14:39:46.011+0530', 1, 1),
    (33, 'Not Required', '2025-05-15 14:39:36.361+0530', 1, 1),
    (34, 'Not Required', '2025-05-15 14:39:27.944+0530', 1, 1),
    (35, 'Not Required', '2025-05-15 14:39:05.562+0530', 1, 1),
    (36, 'Not Required', '2025-05-15 14:38:55.464+0530', 1, 1),
    (37, 'Not Required', '2025-05-15 14:38:29.584+0530', 1, 1),
    (38, 'Not Required', '2025-05-15 14:37:55.233+0530', 1, 1),
    (39, 'Not Required', '2025-05-15 14:37:44.569+0530', 1, 1),
    (40, 'Not Required', '2025-05-15 14:37:30.485+0530', 1, 1),
    (41, 'Not Required', '2025-05-15 14:37:12.086+0530', 1, 1),
    (42, 'Not Required', '2025-05-15 14:36:26.368+0530', 1, 1),
    (43, 'Not Required', '2025-05-15 14:36:11.919+0530', 1, 1),
    (44, 'Not Required', '2025-05-15 14:52:05.384+0530', 1, 1),
    (45, 'Not Required', '2025-05-15 14:51:18.071+0530', 1, 1),
    (46, 'Not Required', '2025-05-15 18:16:43.029+0530', 1, 1),
    (47, 'Not Required', '2025-05-15 18:17:55.070+0530', 1, 1),
    (48, 'Not Required', '2025-05-15 18:18:07.057+0530', 1, 1),
    (49, 'Not Required', '2025-05-15 18:18:17.386+0530', 1, 1),
    (50, 'Not Required', '2025-05-15 18:18:27.485+0530', 1, 1),
    (51, 'Not Required', '2025-05-15 18:18:47.035+0530', 1, 1),
    (52, 'Not Required', '2025-05-15 18:19:00.288+0530', 1, 1),
    (53, 'Not Required', '2025-05-15 18:19:16.713+0530', 1, 1),
    (54, 'Not Required', '2025-05-15 18:19:30.613+0530', 1, 1),
    (55, 'Not Required', '2025-05-15 18:20:11.765+0530', 1, 1);

--------------------------------------

Second execute this---1
--------------------------------------

    UPDATE jumio_app_selectfordwn
    SET
      v2_old_id = CASE id
        WHEN 1 THEN 'ScanCompletionDateINT'
        WHEN 2 THEN 'MerchantName'
        WHEN 3 THEN 'DataCenter'
        WHEN 4 THEN 'JumioCompany'
        WHEN 5 THEN 'SLACategory'
        WHEN 6 THEN NULL
        WHEN 7 THEN NULL
        WHEN 8 THEN NULL
        WHEN 9 THEN NULL
        WHEN 10 THEN NULL
        WHEN 11 THEN 'ScanMode'
        WHEN 12 THEN 'DocumentCountry'
        WHEN 13 THEN 'DocumentState'
        WHEN 14 THEN 'DocumentType'
        WHEN 15 THEN 'DocumentSubType'
        WHEN 16 THEN 'CallbackStatus'
        WHEN 17 THEN 'RejectReason'
        WHEN 18 THEN 'RejectInfo'
        WHEN 19 THEN 'publicGUID'
        WHEN 20 THEN 'NVIDVerificationTime'
        WHEN 21 THEN 'ScanStartDate2'
        WHEN 22 THEN 'QueueGroup'
        WHEN 23 THEN 'QueuePriority'
        WHEN 24 THEN 'RiskLevelTriage'
        WHEN 25 THEN 'BODDEUser'
        WHEN 26 THEN 'BODDEAgentTime'
        WHEN 27 THEN NULL
        WHEN 28 THEN 'BODDEUser'
        WHEN 29 THEN 'BODDEAgentTime'
        WHEN 30 THEN NULL
        WHEN 31 THEN 'BOMaskingUser'
        WHEN 32 THEN 'BOMaskingTime'
        WHEN 33 THEN NULL
        WHEN 34 THEN 'BOFacematchUser'
        WHEN 35 THEN 'BOFacematchTime'
        WHEN 36 THEN NULL
        WHEN 37 THEN NULL
        WHEN 38 THEN NULL
        WHEN 39 THEN NULL
        WHEN 40 THEN NULL
        WHEN 41 THEN NULL
        WHEN 42 THEN NULL
        WHEN 43 THEN NULL
        WHEN 44 THEN 'BackofficeSteps'
        WHEN 45 THEN 'AddressExtraction'
        WHEN 46 THEN 'FaceMatch'
        WHEN 47 THEN 'DDETasks'
        WHEN 48 THEN 'ScanCreationUTC'
        WHEN 49 THEN 'BODDEPicLoadingTime'
        WHEN 50 THEN 'DataExtractionMethod'
        WHEN 51 THEN 'fmSimilarity'
        WHEN 52 THEN 'fmSimilarityScore'
        WHEN 53 THEN 'fmValidityReason'
        WHEN 54 THEN 'DDEDataEntryDetails'
        WHEN 55 THEN 'RiskModel'
        ELSE v2_old_id
      END,
      
      v3_old_id = CASE id
        WHEN 1 THEN 'CompletionDate'
        WHEN 2 THEN 'Merchant'
        WHEN 3 THEN 'DataCenter'
        WHEN 4 THEN 'JumioCompany'
        WHEN 5 THEN 'SLACategory'
        WHEN 6 THEN 'Workflow'
        WHEN 7 THEN 'workflowDefinition'
        WHEN 8 THEN 'ScanStatus'
        WHEN 9 THEN 'DecisionSource'
        WHEN 10 THEN 'DecisionType'
        WHEN 11 THEN 'scanMode'
        WHEN 12 THEN 'DocCountry'
        WHEN 13 THEN 'DocState'
        WHEN 14 THEN 'Doctype'
        WHEN 15 THEN 'DocSubType'
        WHEN 16 THEN 'CallbackStatus'
        WHEN 17 THEN 'RejectReason'
        WHEN 18 THEN 'RejectReasonCategory'
        WHEN 19 THEN 'WorkflowUID'
        WHEN 20 THEN 'WFDurationSec'
        WHEN 21 THEN 'wfStartedAt'
        WHEN 22 THEN 'QueueGroup'
        WHEN 23 THEN 'QueuePriority'
        WHEN 24 THEN 'Risk Level'
        WHEN 25 THEN 'wfDDE_agent'
        WHEN 26 THEN 'wfDDE_agentTime'
        WHEN 27 THEN 'wfDDE_queue'
        WHEN 28 THEN 'wfDocVagent'
        WHEN 29 THEN 'wfDocVagenttime'
        WHEN 30 THEN 'wfDocVqueue'
        WHEN 31 THEN 'wfMasking_agent'
        WHEN 32 THEN 'wfMasking_agentTime'
        WHEN 33 THEN 'wfMasking_queue'
        WHEN 34 THEN 'wfLiveness_agent'
        WHEN 35 THEN 'wfLiveness_agentTime'
        WHEN 36 THEN 'wfLiveness_queue'
        WHEN 37 THEN 'wfSimilarity_agent'
        WHEN 38 THEN 'wfSimilarity_agentTime'
        WHEN 39 THEN 'wfSimilarity_queue'
        WHEN 40 THEN 'CDATAC_addinfo1'
        WHEN 41 THEN 'CEXT_addinfo1'
        WHEN 42 THEN 'CIMGC_addinfo1'
        WHEN 43 THEN 'CUSE_addinfo1'
        WHEN 44 THEN NULL
        WHEN 45 THEN NULL
        WHEN 46 THEN 'FaceMatch'
        WHEN 47 THEN 'DDETasks'
        WHEN 48 THEN 'ScanCreationUTC'
        WHEN 49 THEN 'BODDEPicLoadingTime'
        WHEN 50 THEN 'DataExtractionMethod'
        WHEN 51 THEN 'fmSimilarity'
        WHEN 52 THEN 'fmSimilarityScore'
        WHEN 53 THEN 'fmValidityReason'
        WHEN 54 THEN 'DDEDataEntryDetails'
        WHEN 55 THEN 'RiskModel'
        ELSE v3_old_id
      END
    WHERE id BETWEEN 1 AND 57;


-------------------

Check the Total count record in tabel based on batch id

    SELECT COUNT(*) AS total_count
    FROM jumio_app_v3_json_record
    WHERE batch_id = 'V3BATCH002';


-----------------

Select Query based on WorkflowUID

    SELECT *
    FROM yourapp_v3_json_record
    WHERE v3_columns ->> 'WorkflowUID' = '870F54D1-1A6A-44BF-9C71-004D01FF33D7'
