# F1_Query

Delete recored in json tabel :

    delete from jumio_app_v3_json_record where batch_id='V3BATCH001';

-----------------------------------------------

Insert recored in select For Downlaoded :

      INSERT INTO dbviewer (
        id,
        old_column_name,
        new_column_name,
        created_at,
        user_status,
        file_name_v2_v3,
        created_by_id
    ) VALUES
    (75, 'MerchantName', 'MerchantName', '2025-04-01 11:59:21.965+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (76, 'JumioCompany', 'JumioCompany', '2025-04-01 11:59:21.966+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (77, 'DataCenter', 'DataCenter', '2025-04-01 11:59:21.967+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (78, 'ScanMode', 'ScanMode', '2025-04-01 11:59:21.969+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (79, 'BackofficeSteps', 'BackofficeSteps', '2025-04-01 11:59:21.970+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (80, 'CallbackStatus', 'CallbackStatus', '2025-04-01 11:59:21.971+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (81, 'DocumentType', 'DocumentType', '2025-04-01 11:59:21.972+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (82, 'DocumentSubType', 'DocumentSubType', '2025-04-01 11:59:21.973+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (83, 'DocumentCountry', 'DocumentCountry', '2025-04-01 11:59:21.974+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (84, 'DocumentState', 'DocumentState', '2025-04-01 11:59:21.975+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (85, 'AddressExtraction', 'AddressExtraction', '2025-04-01 11:59:21.976+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (86, 'FaceMatch', 'FaceMatch', '2025-04-01 11:59:21.977+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (87, 'DDETasks', 'DDETasks', '2025-04-01 11:59:21.978+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (88, 'RejectReason', 'RejectReason', '2025-04-01 11:59:21.979+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (89, 'RejectInfo', 'RejectInfo', '2025-04-01 11:59:21.980+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (90, 'SLACategory', 'SLACategory', '2025-04-01 11:59:21.981+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (91, 'publicGUID', 'publicGUID', '2025-04-01 11:59:21.982+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (92, 'ScanCreationUTC', 'ScanCreationUTC', '2025-04-01 11:59:21.984+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (93, 'ScanStartDate2', 'ScanStartDate2', '2025-04-01 11:59:21.985+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (94, 'NVIDVerificationTime', 'NVIDVerificationTime', '2025-04-01 11:59:21.987+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (95, 'BODDEUser', 'BODDEUser', '2025-04-01 11:59:21.988+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (96, 'BODDEAgentTime', 'BODDEAgentTime', '2025-04-01 11:59:21.989+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (97, 'BODDEPicLoadingTime', 'BODDEPicLoadingTime', '2025-04-01 11:59:21.990+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (98, 'DataExtractionMethod', 'DataExtractionMethod', '2025-04-01 11:59:21.991+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (99, 'fmSimilarity', 'fmSimilarity', '2025-04-01 11:59:21.992+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (100, 'fmSimilarityScore', 'fmSimilarityScore', '2025-04-01 11:59:21.993+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (101, 'fmValidityReason', 'fmValidityReason', '2025-04-01 11:59:21.994+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (102, 'BOFacematchUser', 'BOFacematchUser', '2025-04-01 11:59:21.995+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (103, 'BOFacematchTime', 'BOFacematchTime', '2025-04-01 11:59:21.996+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (104, 'BOMaskingUser', 'BOMaskingUser', '2025-04-01 11:59:21.997+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (105, 'BOMaskingTime', 'BOMaskingTime', '2025-04-01 11:59:21.998+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (106, 'DDEDataEntryDetails', 'DDEDataEntryDetails', '2025-04-01 11:59:22.000+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (107, 'RiskLevelTriage', 'RiskLevelTriage', '2025-04-01 11:59:22.001+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (108, 'RiskModel', 'RiskModel', '2025-04-01 11:59:22.003+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (109, 'QueuePriority', 'QueuePriority', '2025-04-01 11:59:22.004+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (110, 'QueueGroup', 'QueueGroup, queueGroup', '2025-04-01 11:59:22.004+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1),
    (74, 'ScanCompletionDateINT', 'ScanCompletionDateINT', '2025-04-01 11:59:21.963+05:30', 1, 'V2 Raw 20250315 (1).xlsx', 1);
-----------------------

Alter record :

    ALTER TABLE jumio_app_selectfordwn ADD COLUMN validation_required VARCHAR(255) NULL;

-----------------------

V2 record insert record :

    INSERT INTO dbviewer (id, old_column_name, new_column_name, created_at, user_status, file_name_v2_v3, created_by_id) VALUES
    (96, 'QueuePriority', 'QueuePriority', '2025-04-01 11:59:22.370+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (95, 'QueueGroup', 'QueueGroup,queueGroup', '2025-04-01 11:59:22.368+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (97, 'Risk Level', 'Risk Level, bk_riskLevel', '2025-04-01 11:59:22.371+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (75, 'Merchant', 'Merchant', '2025-04-01 11:59:22.343+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (76, 'DataCenter', 'DataCenter', '2025-04-01 11:59:22.344+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (77, 'JumioCompany', 'JumioCompany', '2025-04-01 11:59:22.345+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (78, 'SLACategory', 'SLACategory', '2025-04-01 11:59:22.346+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (79, 'Workflow', 'Workflow', '2025-04-01 11:59:22.348+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (80, 'workflowDefinition', 'workflowDefinition', '2025-04-01 11:59:22.349+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (81, 'ScanStatus', 'ScanStatus', '2025-04-01 11:59:22.350+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (82, 'DecisionSource', 'DecisionSource', '2025-04-01 11:59:22.351+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (83, 'DecisionType', 'DecisionType', '2025-04-01 11:59:22.353+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (84, 'scanMode', 'scanMode', '2025-04-01 11:59:22.355+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (85, 'DocCountry', 'DocCountry', '2025-04-01 11:59:22.356+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (86, 'DocState', 'DocState', '2025-04-01 11:59:22.357+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (87, 'Doctype', 'Doctype', '2025-04-01 11:59:22.358+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (88, 'DocSubType', 'DocSubType', '2025-04-01 11:59:22.359+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (90, 'RejectReason', 'RejectReason', '2025-04-01 11:59:22.362+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (91, 'RejectReasonCategory', 'RejectReasonCategory', '2025-04-01 11:59:22.363+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (92, 'WorkflowUID', 'WorkflowUID', '2025-04-01 11:59:22.364+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (93, 'WFDurationSec', 'WFDurationSec', '2025-04-01 11:59:22.365+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (94, 'wfStartedAt', 'wfStartedAt', '2025-04-01 11:59:22.367+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (98, 'wfDDE_agent', 'wfDDE_agent', '2025-04-01 11:59:22.372+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (99, 'wfDDE_agentTime', 'wfDDE_agentTime', '2025-04-01 11:59:22.374+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (100, 'wfDDE_queue', 'wfDDE_queue', '2025-04-01 11:59:22.375+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (101, 'wfDocVagent', 'wfDocVagent', '2025-04-01 11:59:22.376+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (103, 'wfDocVqueue', 'wfDocVqueue,wfDocV_queue', '2025-04-01 11:59:22.379+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (102, 'wfDocVagenttime', 'wfDocVagenttime,wfDocV_agentTime', '2025-04-01 11:59:22.377+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (104, 'wfMasking_agent', 'wfMasking_agent', '2025-04-01 11:59:22.380+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (105, 'wfMasking_agentTime', 'wfMasking_agentTime', '2025-04-01 11:59:22.381+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (106, 'wfMasking_queue', 'wfMasking_queue', '2025-04-01 11:59:22.382+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (74, 'CompletionDate', 'CompletionDate', '2025-04-01 11:59:22.341+05:30', 1, 'V3 Raw 20250315.xlsx', 1),
    (89, 'CallbackStatus', 'CallbackStatus', '2025-04-01 11:59:22.361+05:30', 1, 'V3 Raw 20250315.xlsx', 1);


-----------------------

V3 record insert record :

    INSERT INTO your_table_name (id, v2_old, v3_old, validation_required, created_at, user_status, created_by_id)
    VALUES
    (582, NULL, 'Workflow', 'Not Required', '2025-03-24 12:27:55.188 +0530', 1, 1),
    (611, 'BOFacematchTime', 'wfLiveness_agentTime', 'Not Required', '2025-03-24 12:59:55.241 +0530', 1, 1),
    (598, 'QueueGroup', 'QueueGroup', 'Required', '2025-03-24 12:31:28.378 +0530', 1, 1),
    (577, 'ScanCompletionDateINT', 'CompletionDate', 'Not Required', '2025-03-24 12:26:15.972 +0530', 1, 1),
    (578, 'MerchantName', 'Merchant', 'Required', '2025-03-24 12:26:42.523 +0530', 1, 1),
    (579, 'DataCenter', 'DataCenter', 'Not Required', '2025-03-24 12:26:46.641 +0530', 1, 1),
    (581, 'SLACategory', 'SLACategory', 'Not Required', '2025-03-24 12:27:01.388 +0530', 1, 1),
    (583, NULL, 'workflowDefinition', 'Not Required', '2025-03-24 12:28:12.887 +0530', 1, 1),
    (584, NULL, 'ScanStatus', 'Not Required', '2025-03-24 12:28:20.141 +0530', 1, 1),
    (585, NULL, 'DecisionSource', 'Not Required', '2025-03-24 12:28:27.131 +0530', 1, 1),
    (586, NULL, 'DecisionType', 'Not Required', '2025-03-24 12:28:35.176 +0530', 1, 1),
    (587, 'ScanMode', 'scanMode', 'Not Required', '2025-03-24 12:29:48.999 +0530', 1, 1),
    (588, 'DocumentCountry', 'DocCountry', 'Required', '2025-03-24 12:29:57.678 +0530', 1, 1),
    (589, 'DocumentState', 'DocState', 'Required', '2025-03-24 12:30:04.501 +0530', 1, 1),
    (590, 'DocumentType', 'Doctype', 'Required', '2025-03-24 12:30:11.997 +0530', 1, 1),
    (591, 'DocumentSubType', 'DocSubType', 'Required', '2025-03-24 12:30:21.810 +0530', 1, 1),
    (592, 'CallbackStatus', 'CallbackStatus', 'Required', '2025-03-24 12:30:28.483 +0530', 1, 1),
    (593, 'RejectReason', 'RejectReason', 'Not Required', '2025-03-24 12:30:34.934 +0530', 1, 1),
    (594, 'RejectInfo', 'RejectReasonCategory', 'Not Required', '2025-03-24 12:30:46.258 +0530', 1, 1),
    (595, 'publicGUID', 'WorkflowUID', 'Not Required', '2025-03-24 12:30:55.188 +0530', 1, 1),
    (596, 'NVIDVerificationTime', 'WFDurationSec', 'Not Required', '2025-03-24 12:31:06.628 +0530', 1, 1),
    (597, 'ScanStartDate2', 'wfStartedAt', 'Not Required', '2025-03-24 12:31:18.925 +0530', 1, 1),
    (599, 'QueuePriority', 'QueuePriority', 'Required', '2025-03-24 12:31:35.202 +0530', 1, 1),
    (601, 'BODDEUser', 'wfDDE_agent', 'Not Required', '2025-03-24 12:46:00.240 +0530', 1, 1),
    (602, 'BODDEAgentTime', 'wfDDE_agentTime', 'Not Required', '2025-03-24 12:56:23.647 +0530', 1, 1),
    (603, NULL, 'wfDDE_queue', 'Not Required', '2025-03-24 12:57:22.161 +0530', 1, 1),
    (604, 'BODDEUser', 'wfDocVagent', 'Not Required', '2025-03-24 12:57:36.846 +0530', 1, 1),
    (605, 'BODDEAgentTime', 'wfDocVagenttime', 'Not Required', '2025-03-24 12:57:48.857 +0530', 1, 1),
    (606, NULL, 'wfDocVqueue', 'Not Required', '2025-03-24 12:58:02.082 +0530', 1, 1),
    (607, 'BOMaskingUser', 'wfMasking_agent', 'Not Required', '2025-03-24 12:58:47.121 +0530', 1, 1),
    (608, 'BOMaskingTime', 'wfMasking_agentTime', 'Not Required', '2025-03-24 12:59:14.564 +0530', 1, 1),
    (609, NULL, 'wfMasking_queue', 'Not Required', '2025-03-24 12:59:31.873 +0530', 1, 1),
    (610, 'BOFacematchUser', 'wfLiveness_agent', 'Not Required', '2025-03-24 12:59:48.201 +0530', 1, 1),
    (612, NULL, 'wfLiveness_queue', 'Not Required', '2025-03-24 13:00:02.132 +0530', 1, 1),
    (613, NULL, 'wfLiveness_agent', 'Not Required', '2025-03-24 13:48:29.217 +0530', 1, 1),
    (614, NULL, 'wfSimilarity_agent', 'Not Required', '2025-03-24 13:49:00.405 +0530', 1, 1),
    (615, NULL, 'wfSimilarity_agentTime', 'Not Required', '2025-03-24 13:49:11.619 +0530', 1, 1),
    (616, NULL, 'wfSimilarity_queue', 'Not Required', '2025-03-24 13:49:26.191 +0530', 1, 1),
    (620, NULL, 'CUSE_addinfo1', 'Not Required', '2025-03-24 13:50:36.932 +0530', 1, 1),
    (619, NULL, 'CIMGC_addinfo1', 'Not Required', '2025-03-24 13:50:04.992 +0530', 1, 1),
    (618, NULL, 'CEXT_addinfo1', 'Not Required', '2025-03-24 13:49:55.743 +0530', 1, 1),
    (617, NULL, 'CDATAC_addinfo1', 'Not Required', '2025-03-24 13:49:44.237 +0530', 1, 1),
    (621, 'BackofficeSteps', 'BackofficeSteps', 'Not Required', '2025-03-24 13:50:49.591 +0530', 1, 1),
    (622, 'AddressExtraction', 'AddressExtraction', 'Not Required', '2025-03-24 13:51:01.029 +0530', 1, 1),
    (623, 'FaceMatch', 'FaceMatch', 'Not Required', '2025-03-24 13:51:13.576 +0530', 1, 1),
    (624, 'DDETasks', 'DDETasks', 'Not Required', '2025-03-24 13:51:25.496 +0530', 1, 1),
    (625, 'ScanCreationUTC', 'ScanCreationUTC', 'Not Required', '2025-03-24 13:51:39.246 +0530', 1, 1),
    (626, 'BODDEPicLoadingTime', 'BODDEPicLoadingTime', 'Not Required', '2025-03-24 13:51:59.695 +0530', 1, 1),
    (627, 'DataExtractionMethod', 'DataExtractionMethod', 'Not Required', '2025-03-24 13:52:16.938 +0530', 1, 1),
    (628, 'fmSimilarity', 'fmSimilarity', 'Not Required', '2025-03-24 13:53:28.683 +0530', 1, 1),
    (629, 'fmSimilarityScore', 'fmSimilarityScore', 'Not Required', '2025-03-24 13:53:37.430 +0530', 1, 1),
    (630, 'fmValidityReason', 'fmValidityReason', 'Not Required', '2025-03-24 13:53:46.148 +0530', 1, 1),
    (631, 'DDEDataEntryDetails', 'DDEDataEntryDetails', 'Not Required', '2025-03-24 13:54:06.895 +0530', 1, 1),
    (632, 'RiskModel', 'RiskModel', 'Not Required', '2025-03-24 13:54:37.584 +0530', 1, 1),
    (633, 'BODDEUser', 'wfDocV_agent', 'Not Required', '2025-04-04 14:06:56.919 +0530', 1, 1),
    (634, 'BODDEAgentTime', 'wfDocV_agentTime', 'Not Required', '2025-04-04 14:07:11.229 +0530', 1, 1),
    (580, 'JumioCompany', 'JumioCompany', 'Not Required', '2025-03-24 12:26:52.026 +0530', 1, 1),
    (600, 'RiskLevelTriage', 'Risk Level', 'Required', '2025-03-24 12:45:41.611 +0530', 1, 1);

-------------------

Check the Total count record in tabel based on batch id

    SELECT COUNT(*) AS total_count
    FROM jumio_app_v3_json_record
    WHERE batch_id = 'V3BATCH002';
