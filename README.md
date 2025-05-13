# F1_bug_test



Delete recored in json tabel

                      DELETE FROM jumio_app_v3_json_record WHERE batch_id = 'BATCH002';
                      DELETE FROM jumio_app_v2_json_record WHERE batch_id = 'BATCH002';
-----------------------------------------------
Insert recored in v2_old and v3_old

      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('ScanCompletionDateINT', 'CompletionDate', '2025-03-24 12:26:15.972+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('MerchantName', 'Merchant', '2025-03-24 12:26:42.523+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DataCenter', 'DataCenter', '2025-03-24 12:26:46.641+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('JumioCompany', 'JumioCompany', '2025-03-24 12:26:52.026+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('SLACategory', 'SLACategory', '2025-03-24 12:27:01.388+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'Workflow', '2025-03-24 12:27:55.188+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'workflowDefinition', '2025-03-24 12:28:12.887+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'ScanStatus', '2025-03-24 12:28:20.141+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'DecisionSource', '2025-03-24 12:28:27.131+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'DecisionType', '2025-03-24 12:28:35.176+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('ScanMode', 'scanMode', '2025-03-24 12:29:48.999+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DocumentCountry', 'DocCountry', '2025-03-24 12:29:57.678+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DocumentState', 'DocState', '2025-03-24 12:30:04.501+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DocumentType', 'Doctype', '2025-03-24 12:30:11.997+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DocumentSubType', 'DocSubType', '2025-03-24 12:30:21.810+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('CallbackStatus', 'CallbackStatus', '2025-03-24 12:30:28.483+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('RejectReason', 'RejectReason', '2025-03-24 12:30:34.934+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('RejectInfo', 'RejectReasonCategory', '2025-03-24 12:30:46.258+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('publicGUID', 'WorkflowUID', '2025-03-24 12:30:55.188+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('NVIDVerificationTime', 'WFDurationSec', '2025-03-24 12:31:06.628+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('ScanStartDate2', 'wfStartedAt', '2025-03-24 12:31:18.925+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('QueueGroup', 'QueueGroup', '2025-03-24 12:31:28.378+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('QueuePriority', 'QueuePriority', '2025-03-24 12:31:35.202+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('RiskLevelTriage', 'Risk Level', '2025-03-24 12:45:41.611+05:30', 1, 1, 'Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BODDEUser', 'wfDDE_agent', '2025-03-24 12:46:00.240+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BODDEAgentTime', 'wfDDE_agentTime', '2025-03-24 12:56:23.647+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfDDE_queue', '2025-03-24 12:57:22.161+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BODDEUser', 'wfDocVagent', '2025-03-24 12:57:36.846+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BODDEAgentTime', 'wfDocVagenttime', '2025-03-24 12:57:48.857+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfDocVqueue', '2025-03-24 12:58:02.082+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BOMaskingUser', 'wfMasking_agent', '2025-03-24 12:58:47.121+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BOMaskingTime', 'wfMasking_agentTime', '2025-03-24 12:59:14.564+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfMasking_queue', '2025-03-24 12:59:31.873+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BOFacematchUser', 'wfLiveness_agent', '2025-03-24 12:59:48.201+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BOFacematchTime', 'wfMasking_agentTime', '2025-03-24 12:59:55.241+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfLiveness_queue', '2025-03-24 13:00:02.132+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfLiveness_agent', '2025-03-24 13:48:29.217+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfSimilarity_agent', '2025-03-24 13:49:00.405+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfSimilarity_agentTime', '2025-03-24 13:49:11.619+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'wfSimilarity_queue', '2025-03-24 13:49:26.191+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'CDATAC_addinfo1', '2025-03-24 13:49:44.237+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'CEXT_addinfo1', '2025-03-24 13:49:55.743+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'CIMGC_addinfo1', '2025-03-24 13:50:04.992+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      (NULL, 'CUSE_addinfo1', '2025-03-24 13:50:36.932+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BackofficeSteps', 'BackofficeSteps', '2025-03-24 13:50:49.591+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('AddressExtraction', 'AddressExtraction', '2025-03-24 13:51:01.029+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('FaceMatch', 'FaceMatch', '2025-03-24 13:51:13.576+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DDETasks', 'DDETasks', '2025-03-24 13:51:25.496+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('ScanCreationUTC', 'ScanCreationUTC', '2025-03-24 13:51:39.246+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('BODDEPicLoadingTime', 'BODDEPicLoadingTime', '2025-03-24 13:51:59.695+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DataExtractionMethod', 'DataExtractionMethod', '2025-03-24 13:52:16.938+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('fmSimilarity', 'fmSimilarity', '2025-03-24 13:53:28.683+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('fmSimilarityScore', 'fmSimilarityScore', '2025-03-24 13:53:37.430+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('fmValidityReason', 'fmValidityReason', '2025-03-24 13:53:46.148+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('DDEDataEntryDetails', 'DDEDataEntryDetails', '2025-03-24 13:54:06.895+05:30', 1, 1, 'Not Required');
      INSERT INTO jumio_app_selectfordwn (v2_old, v3_old, created_at, created_by_id, user_status, validation_required) VALUES
      ('RiskModel', 'RiskModel', '2025-03-24 13:54:37.584+05:30', 1, 1, 'Not Required');
-----------------------
Alter record

    ALTER TABLE jumio_app_selectfordwn ADD COLUMN validation_required VARCHAR(255) NULL;

