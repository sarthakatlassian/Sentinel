# Sentinel

# Database Schema Analysis

**Total Tables Found:** 564

**Tables with Primary Keys:** 564
**Tables with Foreign Keys:** 157
**Total Foreign Key Relationships:** 190

## Summary Table

| Table Name | Column Count | Primary Key(s) | Foreign Key Count |
|------------|--------------|----------------|-------------------|
| AO_0201F0_KB_HELPFUL_AGGR | 4 | ID | 0 |
| AO_0201F0_KB_VIEW_AGGR | 4 | ID | 0 |
| AO_0201F0_STATS_EVENT | 3 | ID | 0 |
| AO_0201F0_STATS_EVENT_PARAM | 4 | ID | 1 |
| AO_0A5972_NOTIFICATION_SETTING | 5 | ID | 0 |
| AO_0A5972_OAUTH2_CONFIGURATION | 4 | ID | 0 |
| AO_0A5972_PUSH_REGISTRATION | 6 | ID | 0 |
| AO_0AC321_RECOMMENDATION_AO | 8 | ID | 0 |
| AO_21D670_WHITELIST_RULES | 5 | ID | 0 |
| AO_21F425_MESSAGE_AO | 2 | ID | 0 |
| AO_21F425_MESSAGE_MAPPING_AO | 3 | ID | 0 |
| AO_21F425_USER_PROPERTY_AO | 4 | ID | 0 |
| AO_2C4E5C_MAILCHANNEL | 10 | ID | 1 |
| AO_2C4E5C_MAILCONNECTION | 13 | ID | 0 |
| AO_2C4E5C_MAILGLOBALHANDLER | 5 | ID | 0 |
| AO_2C4E5C_MAILHANDLER | 6 | ID | 1 |
| AO_2C4E5C_MAILITEM | 5 | ID | 0 |
| AO_2C4E5C_MAILITEMAUDIT | 13 | ID | 1 |
| AO_2C4E5C_MAILITEMCHUNK | 4 | ID | 1 |
| AO_2C4E5C_MAILRUNAUDIT | 8 | ID | 0 |
| AO_38321B_CUSTOM_CONTENT_LINK | 5 | ID | 0 |
| AO_3B1893_LOOP_DETECTION | 4 | ID | 0 |
| AO_4789DD_DISABLED_CHECKS | 2 | ID | 0 |
| AO_4789DD_HEALTH_CHECK_STATUS | 12 | ID | 0 |
| AO_4789DD_HEALTH_CHECK_WATCHER | 2 | ID | 0 |
| AO_4789DD_PROPERTIES | 3 | ID | 0 |
| AO_4789DD_READ_NOTIFICATIONS | 6 | ID | 0 |
| AO_4789DD_SHORTENED_KEY | 2 | ID | 0 |
| AO_4789DD_TASK_MONITOR | 11 | ID | 0 |
| AO_4AEACD_WEBHOOK_DAO | 12 | ID | 0 |
| AO_54307E_ASYNCUPGRADERECORD | 7 | ID | 0 |
| AO_54307E_CAPABILITY | 5 | ID | 1 |
| AO_54307E_CONFLUENCEKB | 8 | ID | 1 |
| AO_54307E_CONFLUENCEKBENABLED | 5 | ID | 3 |
| AO_54307E_CONFLUENCEKBLABELS | 5 | ID | 3 |
| AO_54307E_CUSTOMGLOBALTHEME | 11 | ID | 0 |
| AO_54307E_CUSTOMTHEME | 5 | ID | 0 |
| AO_54307E_EMAILCHANNELSETTING | 7 | ID | 2 |
| AO_54307E_EMAILSETTINGS | 8 | ID | 2 |
| AO_54307E_GOAL | 9 | ID | 1 |
| AO_54307E_GROUP | 5 | ID | 1 |
| AO_54307E_GROUPTOREQUESTTYPE | 4 | ID | 2 |
| AO_54307E_IMAGES | 2 | ID | 0 |
| AO_54307E_METRICCONDITION | 6 | ID | 1 |
| AO_54307E_OUT_EMAIL_SETTINGS | 3 | ID | 1 |
| AO_54307E_PARTICIPANTSETTINGS | 4 | ID | 1 |
| AO_54307E_QUEUE | 6 | ID | 0 |
| AO_54307E_QUEUECOLUMN | 4 | ID | 1 |
| AO_54307E_REPORT | 7 | ID | 1 |
| AO_54307E_SERIES | 9 | ID | 1 |
| AO_54307E_SERVICEDESK | 11 | ID | 0 |
| AO_54307E_STATUSMAPPING | 4 | ID | 1 |
| AO_54307E_SUBSCRIPTION | 4 | ID | 0 |
| AO_54307E_SYNCUPGRADERECORD | 7 | ID | 0 |
| AO_54307E_THRESHOLD | 3 | ID | 1 |
| AO_54307E_TIMEMETRIC | 11 | ID | 1 |
| AO_54307E_VIEWPORT | 8 | ID | 1 |
| AO_54307E_VIEWPORTFIELD | 9 | ID | 1 |
| AO_54307E_VIEWPORTFIELDVALUE | 5 | ID | 1 |
| AO_54307E_VIEWPORTFORM | 11 | ID | 1 |
| AO_550953_SHORTCUT | 7 | ID | 0 |
| AO_563AEE_ACTIVITY_ENTITY | 17 | ACTIVITY_ID | 4 |
| AO_563AEE_ACTOR_ENTITY | 5 | ID | 0 |
| AO_563AEE_MEDIA_LINK_ENTITY | 5 | ID | 0 |
| AO_563AEE_OBJECT_ENTITY | 8 | ID | 1 |
| AO_563AEE_TARGET_ENTITY | 8 | ID | 1 |
| AO_56464C_APPROVAL | 9 | ID | 0 |
| AO_56464C_APPROVER | 4 | ID | 1 |
| AO_56464C_APPROVERDECISION | 5 | ID | 1 |
| AO_56464C_NOTIFICATIONRECORD | 4 | ID | 1 |
| AO_575BF5_DEV_SUMMARY | 6 | ID | 0 |
| AO_575BF5_PROCESSED_COMMITS | 3 | ID | 0 |
| AO_575BF5_PROVIDER_ISSUE | 4 | ID | 0 |
| AO_575BF5_PROVIDER_SEQ_NO | 3 | ID | 0 |
| AO_587B34_GLANCE_CONFIG | 6 | ROOM_ID | 0 |
| AO_587B34_PROJECT_CONFIG | 7 | ID | 0 |
| AO_589059_AUDIT_ITEM | 17 | ID | 0 |
| AO_589059_AUDIT_ITEM_ASC_ITEM | 8 | ID | 2 |
| AO_589059_AUDIT_ITEM_CGE_ITEM | 7 | ID | 2 |
| AO_589059_AUDIT_ITEM_COMP_CGE | 8 | ID | 1 |
| AO_589059_AUDIT_ITEM_PROJECT | 3 | ID | 1 |
| AO_589059_AUTOMATION_QUEUE | 12 | ID | 1 |
| AO_589059_COUNTERS | 4 | ID | 0 |
| AO_589059_LEGACY_RULE_LINK | 3 | ID | 0 |
| AO_589059_RULE_CFG_COMPONENT | 9 | ID | 3 |
| AO_589059_RULE_CFG_PROJ_ASSOC | 4 | ID | 1 |
| AO_589059_RULE_CONFIG | 13 | ID | 0 |
| AO_589059_RULE_LABEL | 3 | ID | 0 |
| AO_589059_RULE_SCHEDULE | 7 | ID | 1 |
| AO_589059_RULE_SECRET | 3 | ID | 0 |
| AO_589059_RULE_STAT | 8 | ID | 0 |
| AO_589059_RULE_STATE_LATEST | 9 | ID | 0 |
| AO_589059_RULE_STAT_ROLLUP_DAY | 10 | ID | 0 |
| AO_589059_RULE_STAT_ROLLUP_HR | 10 | ID | 0 |
| AO_589059_RULE_STAT_ROLLUP_MIN | 10 | ID | 0 |
| AO_589059_RULE_TAG | 4 | ID | 1 |
| AO_589059_RULE_TO_LABEL | 3 | ID | 2 |
| AO_589059_RULE_TO_SECRET | 3 | ID | 1 |
| AO_589059_SECRET_PROJ_ASSOC | 3 | ID | 1 |
| AO_5FB9D7_AOHIP_CHAT_LINK | 13 | ID | 0 |
| AO_5FB9D7_AOHIP_CHAT_USER | 9 | ID | 1 |
| AO_60DB71_AUDITENTRY | 7 | ID | 0 |
| AO_60DB71_BOARDADMINS | 4 | ID | 1 |
| AO_60DB71_CARDCOLOR | 6 | ID | 1 |
| AO_60DB71_CARDLAYOUT | 5 | ID | 1 |
| AO_60DB71_COLUMN | 6 | ID | 1 |
| AO_60DB71_COLUMNSTATUS | 4 | ID | 1 |
| AO_60DB71_DETAILVIEWFIELD | 4 | ID | 1 |
| AO_60DB71_ESTIMATESTATISTIC | 4 | ID | 1 |
| AO_60DB71_ISSUERANKING | 4 | ID | 0 |
| AO_60DB71_ISSUERANKINGLOG | 9 | ID | 0 |
| AO_60DB71_LEXORANK | 8 | ID | 0 |
| AO_60DB71_LEXORANKBALANCER | 4 | ID | 0 |
| AO_60DB71_NONWORKINGDAY | 3 | ID | 1 |
| AO_60DB71_QUICKFILTER | 7 | ID | 1 |
| AO_60DB71_RANKABLEOBJECT | 2 | ID | 0 |
| AO_60DB71_RAPIDVIEW | 12 | ID | 0 |
| AO_60DB71_SPRINT | 14 | ID | 0 |
| AO_60DB71_STATSFIELD | 3 | ID | 1 |
| AO_60DB71_SUBQUERY | 5 | ID | 1 |
| AO_60DB71_SWIMLANE | 8 | ID | 1 |
| AO_60DB71_TRACKINGSTATISTIC | 4 | ID | 1 |
| AO_60DB71_VERSION | 3 | ID | 0 |
| AO_60DB71_WORKINGDAYS | 10 | ID | 1 |
| AO_6FF49D_ACCESS_LOG_PRC_CTRL | 9 | ID | 1 |
| AO_6FF49D_ACCESS_LOG_PRC_ITEM | 8 | ID | 1 |
| AO_6FF49D_ACTUAL_MIG_COUNTS | 7 | ID | 0 |
| AO_6FF49D_AD_PRELOAD_STATUS | 15 | ID | 0 |
| AO_6FF49D_ANALYTICS_EVENT | 4 | ID | 0 |
| AO_6FF49D_API_USAGE | 10 | ID | 0 |
| AO_6FF49D_APP_ASSESSMENT_INFO | 6 | APP_KEY | 0 |
| AO_6FF49D_BG_TASK | 7 | ID | 0 |
| AO_6FF49D_BG_TASK_UNITY | 7 | ID | 0 |
| AO_6FF49D_BROWSER_METRICS | 4 | ID | 0 |
| AO_6FF49D_CLOUD_SITE | 7 | CLOUD_ID | 0 |
| AO_6FF49D_CONFIG_ITEMS | 5 | ID | 0 |
| AO_6FF49D_CORRECTED_EMAIL | 14 | ID | 0 |
| AO_6FF49D_DAILY_USAGE_METRICS | 7 | ID | 1 |
| AO_6FF49D_DOMAIN_SCAN | 8 | ID | 0 |
| AO_6FF49D_DRY_RUN_MIGRATION | 3 | MIGRATION_ID | 0 |
| AO_6FF49D_EMAIL_TRST_DMN | 6 | ID | 0 |
| AO_6FF49D_EXPECTED_MIG_COUNTS | 5 | ID | 0 |
| AO_6FF49D_EXPELLED_USER | 9 | ID | 0 |
| AO_6FF49D_EXPORT_ERROR | 7 | ID | 0 |
| AO_6FF49D_FX3_STATE_ENTITY | 5 | FX3_STATE_ID | 0 |
| AO_6FF49D_GR_RESPONSE_GROUP | 6 | ID | 0 |
| AO_6FF49D_GUARDRAILS_RESPONSE | 12 | ID | 0 |
| AO_6FF49D_INCORRECT_EMAIL | 16 | ID | 0 |
| AO_6FF49D_INST_ANALYSIS_CTRL | 5 | ID | 0 |
| AO_6FF49D_MIGRATED_ASSET_MEDIA | 8 | ID | 0 |
| AO_6FF49D_MIGRATED_AVATAR | 7 | ID | 0 |
| AO_6FF49D_MIGRATED_FILE | 6 | ID | 0 |
| AO_6FF49D_MIGRATION_COMMAND | 5 | COMMAND_ID | 0 |
| AO_6FF49D_MIGRATION_ENTITY | 16 | MIGRATION_ID | 0 |
| AO_6FF49D_MIGRATION_INCREMENT | 9 | ID | 0 |
| AO_6FF49D_MIGRATION_SCOPE | 4 | CLOUD_ID | 0 |
| AO_6FF49D_MIG_CHAIN_ENTITY | 3 | MIGRATION_ID | 0 |
| AO_6FF49D_MIG_PREFLIGHT | 6 | PREFLIGHT_ID | 0 |
| AO_6FF49D_MIG_PREFLIGHT_CHECK | 7 | CHECK_ID | 0 |
| AO_6FF49D_MIG_REPORT_STATUS | 5 | ID | 0 |
| AO_6FF49D_MIG_STATUS_CACHE | 5 | ID | 0 |
| AO_6FF49D_MIG_V4_COMMAND_TABLE | 5 | ID | 0 |
| AO_6FF49D_NODE_INFRASTRUCTURE | 8 | ID | 0 |
| AO_6FF49D_NODE_NETWORK | 8 | ID | 1 |
| AO_6FF49D_PLAN_ENTITY | 7 | ID | 0 |
| AO_6FF49D_PMRA_FAILED_ENTITY | 11 | ID | 0 |
| AO_6FF49D_PREFLIGHT_LOCK | 1 | PLAN_ID | 0 |
| AO_6FF49D_PREMIG_OUTCOME | 6 | ID | 0 |
| AO_6FF49D_PROJ_EXPORT_PREFLT | 6 | PROJECT_ID | 0 |
| AO_6FF49D_PUBLIC_PLAN_MAPPING | 8 | JOB_ID | 0 |
| AO_6FF49D_SCOPED_USER_CACHE | 5 | PROJECT_ID | 0 |
| AO_6FF49D_SHADOW_CLOUD_SITE | 3 | ID | 0 |
| AO_6FF49D_SHADOW_JOB_DETAILS | 3 | ID | 0 |
| AO_6FF49D_SKIP_PREFLIGHT_RES | 4 | ID | 0 |
| AO_6FF49D_SKIP_PREFLT_RESULT | 4 | ID | 0 |
| AO_6FF49D_TOMBSTONE_ACCOUNT | 2 | USER_KEY | 0 |
| AO_6FF49D_UNSUPPORTED_ENTITY | 9 | ID | 0 |
| AO_6FF49D_USERBASE_SCAN | 12 | ID | 0 |
| AO_6FF49D_USERS_GROUPS_EXTRACT | 10 | ID | 0 |
| AO_6FF49D_USER_EMAIL_EVENT_LOG | 4 | ID | 0 |
| AO_6FF49D_VIRTUAL_ATTACHMENT | 2 | ID | 0 |
| AO_723324_CLIENT_CONFIG | 12 | ID | 0 |
| AO_723324_CLIENT_TOKEN | 11 | ID | 0 |
| AO_733371_EVENT | 7 | ID | 0 |
| AO_733371_EVENT_PARAMETER | 4 | ID | 1 |
| AO_733371_EVENT_RECIPIENT | 8 | ID | 1 |
| AO_7A2604_CALENDAR | 4 | ID | 0 |
| AO_7A2604_HOLIDAY | 5 | ID | 1 |
| AO_7A2604_WORKINGTIME | 5 | ID | 1 |
| AO_81F455_PERSONAL_TOKEN | 9 | ID | 0 |
| AO_82B313_ABILITY | 4 | ID | 2 |
| AO_82B313_ABSENCE | 5 | ID | 1 |
| AO_82B313_AVAILABILITY | 6 | ID | 1 |
| AO_82B313_INIT | 2 | ID | 0 |
| AO_82B313_PERSON | 6 | ID | 0 |
| AO_82B313_RESOURCE | 6 | ID | 2 |
| AO_82B313_SKILL | 3 | ID | 0 |
| AO_82B313_TEAM | 4 | ID | 0 |
| AO_8752F1_DATA_PIPELINE_CONFIG | 3 | ID | 0 |
| AO_8752F1_DATA_PIPELINE_EOO | 3 | ID | 0 |
| AO_8752F1_DATA_PIPELINE_JOB | 16 | ID | 0 |
| AO_88263F_HEALTH_CHECK_STATUS | 11 | ID | 0 |
| AO_88263F_PROPERTIES | 3 | ID | 0 |
| AO_88263F_READ_NOTIFICATIONS | 6 | ID | 0 |
| AO_8AE288_DASHBOARD_VIEWS | 3 | ID | 0 |
| AO_8AE288_PAGE_VIEW_USAGE | 9 | ID | 0 |
| AO_8AE288_USER_PAGE_VIEW | 5 | ID | 1 |
| AO_8AE288_USER_REST_USAGE | 5 | ID | 0 |
| AO_8AE288_USER_WEB_PANEL_USAGE | 7 | ID | 1 |
| AO_8AE288_WEB_PANEL_INFO | 7 | ID | 0 |
| AO_97EDAB_USERINVITATION | 7 | ID | 0 |
| AO_9B2E3B_EXEC_RULE_MSG_ITEM | 4 | ID | 1 |
| AO_9B2E3B_IF_CONDITION_CONFIG | 4 | ID | 1 |
| AO_9B2E3B_IF_COND_CONF_DATA | 4 | ID | 1 |
| AO_9B2E3B_IF_COND_EXECUTION | 7 | ID | 1 |
| AO_9B2E3B_IF_EXECUTION | 6 | ID | 1 |
| AO_9B2E3B_IF_THEN | 3 | ID | 1 |
| AO_9B2E3B_IF_THEN_EXECUTION | 7 | ID | 1 |
| AO_9B2E3B_PROJECT_USER_CONTEXT | 4 | ID | 0 |
| AO_9B2E3B_RSETREV_PROJ_CONTEXT | 3 | ID | 1 |
| AO_9B2E3B_RSETREV_USER_CONTEXT | 4 | ID | 1 |
| AO_9B2E3B_RULE | 4 | ID | 1 |
| AO_9B2E3B_RULESET | 2 | ID | 0 |
| AO_9B2E3B_RULESET_REVISION | 8 | ID | 1 |
| AO_9B2E3B_RULE_EXECUTION | 7 | ID | 0 |
| AO_9B2E3B_THEN_ACTION_CONFIG | 4 | ID | 1 |
| AO_9B2E3B_THEN_ACT_CONF_DATA | 4 | ID | 1 |
| AO_9B2E3B_THEN_ACT_EXECUTION | 7 | ID | 1 |
| AO_9B2E3B_THEN_EXECUTION | 6 | ID | 1 |
| AO_9B2E3B_WHEN_HANDLER_CONFIG | 4 | ID | 1 |
| AO_9B2E3B_WHEN_HAND_CONF_DATA | 4 | ID | 1 |
| AO_A0B856_DAILY_COUNTS | 7 | ID | 0 |
| AO_A0B856_HIST_INVOCATION | 18 | ID | 0 |
| AO_A0B856_WEBHOOK | 11 | ID | 0 |
| AO_A0B856_WEBHOOK_CONFIG | 4 | ID | 0 |
| AO_A0B856_WEBHOOK_EVENT | 3 | ID | 0 |
| AO_A0B856_WEB_HOOK_LISTENER_AO | 12 | ID | 0 |
| AO_A415DF_AOABILITY | 6 | ID_OTHER | 1 |
| AO_A415DF_AOABSENCE | 10 | ID_OTHER | 1 |
| AO_A415DF_AOAVAILABILITY | 11 | ID_OTHER | 1 |
| AO_A415DF_AOCONFIGURATION | 3 | ID_OTHER | 0 |
| AO_A415DF_AOCUSTOM_WORDING | 3 | ID_OTHER | 0 |
| AO_A415DF_AODEPENDENCY | 3 | ID_OTHER | 0 |
| AO_A415DF_AODOOR_STOP | 1 | ID | 0 |
| AO_A415DF_AOESTIMATE | 9 | ID_OTHER | 1 |
| AO_A415DF_AOEXTENSION_LINK | 6 | ID_OTHER | 0 |
| AO_A415DF_AONON_WORKING_DAYS | 10 | ID_OTHER | 1 |
| AO_A415DF_AOPERMISSION | 7 | ID_OTHER | 0 |
| AO_A415DF_AOPERSON | 8 | ID_OTHER | 1 |
| AO_A415DF_AOPLAN | 12 | ID_OTHER | 0 |
| AO_A415DF_AOPLAN_CONFIGURATION | 35 | ID_OTHER | 1 |
| AO_A415DF_AOPRESENCE | 10 | ID_OTHER | 1 |
| AO_A415DF_AORELEASE | 14 | ID_OTHER | 2 |
| AO_A415DF_AOREPLANNING | 4 | ID_OTHER | 1 |
| AO_A415DF_AORESOURCE | 7 | ID_OTHER | 2 |
| AO_A415DF_AOSKILL | 10 | ID_OTHER | 1 |
| AO_A415DF_AOSOLUTION_STORE | 4 | ID_OTHER | 0 |
| AO_A415DF_AOSPRINT | 10 | ID_OTHER | 1 |
| AO_A415DF_AOSTAGE | 10 | ID_OTHER | 1 |
| AO_A415DF_AOSTREAM | 11 | ID_OTHER | 1 |
| AO_A415DF_AOSTREAM_TO_TEAM | 4 | ID_OTHER | 2 |
| AO_A415DF_AOTEAM | 14 | ID_OTHER | 1 |
| AO_A415DF_AOTHEME | 10 | ID_OTHER | 1 |
| AO_A415DF_AOWORK_ITEM | 24 | ID_OTHER | 7 |
| AO_A415DF_AOWORK_ITEM_TO_RES | 4 | ID_OTHER | 2 |
| AO_A44657_HEALTH_CHECK_ENTITY | 1 | ID | 0 |
| AO_AC3877_RL_USER_COUNTER | 5 | ID | 0 |
| AO_AC3877_SETTINGS_VERSION | 2 | TYPE | 0 |
| AO_AC3877_SYSTEM_RL_SETTINGS | 11 | NAME | 0 |
| AO_AC3877_USER_RL_SETTINGS | 6 | USER_ID | 0 |
| AO_B9A0F0_APPLIED_TEMPLATE | 4 | ID | 0 |
| AO_C16815_ALERT_AO | 11 | ID | 0 |
| AO_C77861_AUDIT_ACTION_CACHE | 3 | ID | 0 |
| AO_C77861_AUDIT_CATEGORY_CACHE | 3 | ID | 0 |
| AO_C77861_AUDIT_DENY_LISTED | 2 | ID | 0 |
| AO_C77861_AUDIT_ENTITY | 29 | ID | 0 |
| AO_CC7F60_SEC_MON_ALERT | 7 | ID | 0 |
| AO_CC7F60_SEC_MON_SCHEDULE_JOB | 3 | ID | 0 |
| AO_CC7F60_SEC_MON_THREAT_EVENT | 15 | ID | 1 |
| AO_CFF990_AOTRANSITION_FAILURE | 9 | ID | 0 |
| AO_D9132D_ASSIGNMENT | 15 | ID | 1 |
| AO_D9132D_ASSIGNMENT_EXT | 15 | ID | 1 |
| AO_D9132D_CONFIGURATION | 4 | ID | 0 |
| AO_D9132D_DEP_ISSUE_LINK_TYPES | 3 | ID | 0 |
| AO_D9132D_DISTRIBUTION | 5 | ID | 1 |
| AO_D9132D_EXCLUDED_ISSUE_TYPES | 3 | ID | 1 |
| AO_D9132D_EXCLUDED_STATUSCATS | 3 | ID | 1 |
| AO_D9132D_EXCLUDED_STATUSES | 3 | ID | 1 |
| AO_D9132D_EXCLUDED_VERSIONS | 3 | ID | 1 |
| AO_D9132D_GENERICREPORT | 6 | ID | 0 |
| AO_D9132D_HIERARCHY_CONFIG | 4 | ID | 0 |
| AO_D9132D_INIT | 2 | ID | 0 |
| AO_D9132D_ISSUE_SOURCE | 5 | ID | 1 |
| AO_D9132D_NONWORKINGDAYS | 5 | ID | 1 |
| AO_D9132D_PERMISSIONS | 6 | ID | 2 |
| AO_D9132D_PLAN | 38 | ID | 0 |
| AO_D9132D_PLANNED_CAPACITY | 9 | ID | 1 |
| AO_D9132D_PLANSKILL | 6 | ID | 1 |
| AO_D9132D_PLANTEAM | 9 | ID | 2 |
| AO_D9132D_PLANTHEME | 5 | ID | 2 |
| AO_D9132D_PLANVERSION | 5 | ID | 2 |
| AO_D9132D_PLAN_CUSTOM_FIELD | 5 | ID | 1 |
| AO_D9132D_PLAN_USER_PROPERTY | 6 | ID | 1 |
| AO_D9132D_PLAN_US_PR_MAPPING | 3 | ID | 0 |
| AO_D9132D_PROGRAM | 4 | ID | 0 |
| AO_D9132D_PROGRAM_CUSTOM_FIELD | 4 | ID | 1 |
| AO_D9132D_RANK_ITEM | 5 | ID | 0 |
| AO_D9132D_SAVED_VIEW | 11 | ID | 0 |
| AO_D9132D_SAVED_VIEW2 | 12 | ID | 0 |
| AO_D9132D_SCENARIO | 6 | ID | 1 |
| AO_D9132D_SCENARIO_ABILITY | 10 | ID | 1 |
| AO_D9132D_SCENARIO_AVLBLTY | 6 | ID | 1 |
| AO_D9132D_SCENARIO_CHANGES | 5 | ID | 1 |
| AO_D9132D_SCENARIO_ISSUES | 55 | ID | 1 |
| AO_D9132D_SCENARIO_ISSUE_CMPNT | 3 | ID | 1 |
| AO_D9132D_SCENARIO_ISSUE_LABEL | 3 | ID | 1 |
| AO_D9132D_SCENARIO_ISSUE_LINKS | 11 | ID | 1 |
| AO_D9132D_SCENARIO_ISSUE_RES | 3 | ID | 1 |
| AO_D9132D_SCENARIO_PERSON | 9 | ID | 1 |
| AO_D9132D_SCENARIO_PLAN_CAP | 19 | ID | 1 |
| AO_D9132D_SCENARIO_RESOURCE | 16 | ID | 1 |
| AO_D9132D_SCENARIO_SKILL | 14 | ID | 1 |
| AO_D9132D_SCENARIO_STAGE | 13 | ID | 1 |
| AO_D9132D_SCENARIO_TEAM | 25 | ID | 2 |
| AO_D9132D_SCENARIO_THEME | 14 | ID | 1 |
| AO_D9132D_SCENARIO_VERSION | 20 | ID | 1 |
| AO_D9132D_SCENARIO_XPVERSION | 9 | ID | 1 |
| AO_D9132D_SCEN_CSTM_FLD_MVAL | 3 | ID | 1 |
| AO_D9132D_SCEN_CUSTOM_FIELD | 8 | ID | 2 |
| AO_D9132D_SCEN_TEAM_EX_SPRINT | 3 | ID | 1 |
| AO_D9132D_SHARED_REPORT | 10 | ID | 1 |
| AO_D9132D_SOLUTION | 11 | ID | 0 |
| AO_D9132D_STAGE | 5 | ID | 1 |
| AO_D9132D_TEAM_EX_SPRINT | 4 | ID | 1 |
| AO_D9132D_THEME | 4 | ID | 0 |
| AO_D9132D_VERSION_ENRICHMENT | 3 | ID | 0 |
| AO_D9132D_X_PROJECT_VERSION | 3 | ID | 1 |
| AO_E8B6CC_BRANCH | 3 | ID | 0 |
| AO_E8B6CC_BRANCH_HEAD_MAPPING | 4 | ID | 0 |
| AO_E8B6CC_CHANGESET_MAPPING | 18 | ID | 0 |
| AO_E8B6CC_COMMIT | 9 | ID | 0 |
| AO_E8B6CC_GIT_HUB_EVENT | 5 | ID | 0 |
| AO_E8B6CC_HOOK_MIGRATION_TASK | 3 | ID | 0 |
| AO_E8B6CC_ISSUE_MAPPING | 5 | ID | 0 |
| AO_E8B6CC_ISSUE_MAPPING_V2 | 13 | ID | 0 |
| AO_E8B6CC_ISSUE_TO_BRANCH | 3 | ID | 0 |
| AO_E8B6CC_ISSUE_TO_CHANGESET | 4 | ID | 0 |
| AO_E8B6CC_MESSAGE | 5 | ID | 0 |
| AO_E8B6CC_MESSAGE_QUEUE_ITEM | 7 | ID | 0 |
| AO_E8B6CC_MESSAGE_TAG | 3 | ID | 0 |
| AO_E8B6CC_ORGANIZATION_MAPPING | 18 | ID | 0 |
| AO_E8B6CC_ORG_TO_PROJECT | 3 | ID | 0 |
| AO_E8B6CC_PROJECT_MAPPING | 5 | ID | 0 |
| AO_E8B6CC_PROJECT_MAPPING_V2 | 9 | ID | 0 |
| AO_E8B6CC_PR_ISSUE_KEY | 4 | ID | 0 |
| AO_E8B6CC_PR_PARTICIPANT | 6 | ID | 0 |
| AO_E8B6CC_PR_TO_COMMIT | 4 | ID | 0 |
| AO_E8B6CC_PULL_REQUEST | 15 | ID | 0 |
| AO_E8B6CC_REPOSITORY_MAPPING | 20 | ID | 0 |
| AO_E8B6CC_REPO_TO_CHANGESET | 3 | ID | 0 |
| AO_E8B6CC_REPO_TO_PROJECT | 3 | ID | 0 |
| AO_E8B6CC_SYNC_AUDIT_LOG | 11 | ID | 0 |
| AO_E8B6CC_SYNC_EVENT | 6 | ID | 0 |
| AO_ED669C_IDP_CONFIG | 26 | ID | 0 |
| AO_ED669C_SEALED_ENTITY | 3 | ID | 0 |
| AO_ED669C_SEEN_ASSERTIONS | 3 | ID | 0 |
| AO_ED669C_TOTP_CODES | 4 | ID | 0 |
| AO_ED669C_TOTP_USER_ENROLLMENT | 5 | USER_KEY | 0 |
| AO_F1B27B_HISTORY_RECORD | 6 | ID | 0 |
| AO_F1B27B_KEY_COMPONENT | 4 | ID | 1 |
| AO_F1B27B_KEY_COMP_HISTORY | 4 | ID | 1 |
| AO_F1B27B_PROMISE | 10 | ID | 0 |
| AO_F1B27B_PROMISE_HISTORY | 4 | ID | 0 |
| AO_FE1BC5_ACCESS_TOKEN | 8 | ID | 0 |
| AO_FE1BC5_AUTHORIZATION | 8 | AUTHORIZATION_CODE | 0 |
| AO_FE1BC5_CLIENT | 6 | ID | 0 |
| AO_FE1BC5_REDIRECT_URI | 3 | ID | 0 |
| AO_FE1BC5_REFRESH_TOKEN | 9 | ID | 0 |
| app_user | 3 | id | 0 |
| audit_changed_value | 5 | id | 0 |
| audit_item | 7 | id | 0 |
| audit_log | 16 | id | 0 |
| avatar | 6 | id | 0 |
| board | 2 | id | 0 |
| boardproject | 2 | board_id, project_id | 0 |
| changegroup | 4 | id | 0 |
| changeitem | 8 | id | 0 |
| clusteredjob | 11 | id | 0 |
| clusterlockstatus | 4 | id | 0 |
| clustermessage | 6 | id | 0 |
| clusternode | 7 | node_id | 0 |
| clusternodeheartbeat | 3 | node_id | 0 |
| clusterupgradestate | 6 | id | 0 |
| columnlayout | 3 | id | 0 |
| columnlayoutitem | 4 | id | 0 |
| comment_pin | 5 | id | 0 |
| comment_reaction | 5 | id | 0 |
| comment_version | 5 | comment_id | 0 |
| component | 9 | id | 0 |
| configurationcontext | 5 | id | 0 |
| customfield | 12 | id | 0 |
| customfieldoption | 8 | id | 0 |
| customfieldvalue | 10 | id | 0 |
| cwd_application | 9 | id | 0 |
| cwd_application_address | 4 | application_id, remote_address | 0 |
| cwd_application_attribute | 3 | application_id, attribute_name | 0 |
| cwd_directory | 11 | id | 0 |
| cwd_directory_attribute | 3 | directory_id, attribute_name | 0 |
| cwd_directory_operation | 2 | directory_id, operation_type | 0 |
| cwd_group | 12 | id | 0 |
| cwd_group_attributes | 6 | id | 0 |
| cwd_membership | 10 | id | 0 |
| cwd_synchronisation_status | 7 | id | 0 |
| cwd_synchronisation_token | 2 | directory_id | 0 |
| cwd_user | 18 | id | 0 |
| cwd_user_attributes | 6 | id | 0 |
| deadletter | 5 | id | 0 |
| draftworkflowscheme | 6 | id | 0 |
| draftworkflowschemeentity | 4 | id | 0 |
| entity_property | 7 | id | 0 |
| entity_property_index_document | 6 | id | 0 |
| entity_translation | 6 | id | 0 |
| external_entities | 3 | id | 0 |
| externalgadget | 2 | id | 0 |
| favouriteassociations | 5 | id | 0 |
| feature | 4 | id | 0 |
| fieldconfigscheme | 5 | id | 0 |
| fieldconfigschemeissuetype | 4 | id | 0 |
| fieldconfiguration | 5 | id | 0 |
| fieldlayout | 5 | id | 0 |
| fieldlayoutitem | 8 | id | 0 |
| fieldlayoutscheme | 3 | id | 0 |
| fieldlayoutschemeassociation | 4 | id | 0 |
| fieldlayoutschemeentity | 4 | id | 0 |
| fieldscreen | 3 | id | 0 |
| fieldscreenlayoutitem | 5 | id | 0 |
| fieldscreenscheme | 3 | id | 0 |
| fieldscreenschemeitem | 4 | id | 0 |
| fieldscreentab | 5 | id | 0 |
| fileattachment | 9 | id | 0 |
| filtersubscription | 6 | id | 0 |
| gadgetuserpreference | 4 | id | 0 |
| genericconfiguration | 4 | id | 0 |
| globalpermissionentry | 3 | id | 0 |
| groupbase | 2 | id | 0 |
| issue_field_option | 5 | id | 0 |
| issue_field_option_scope | 4 | id | 0 |
| issue_version | 5 | issue_id | 0 |
| issuelink | 5 | id | 0 |
| issuelinktype | 6 | id | 0 |
| issuesecurityscheme | 4 | id | 0 |
| issuestatus | 6 | id | 0 |
| issuetype | 7 | id | 0 |
| issuetypescreenscheme | 3 | id | 0 |
| issuetypescreenschemeentity | 4 | id | 0 |
| jiraaction | 11 | id | 0 |
| jiradraftworkflows | 3 | id | 0 |
| jiraeventtype | 5 | id | 0 |
| jiraissue | 30 | id | 0 |
| jiraperms | 4 | id | 0 |
| jiraworkflows | 5 | id | 0 |
| jiraworkflowstatuses | 3 | id | 0 |
| jquartz_blob_triggers | 4 | trigger_name, trigger_group | 0 |
| jquartz_calendars | 3 | calendar_name | 0 |
| jquartz_cron_triggers | 5 | trigger_name, trigger_group | 0 |
| jquartz_fired_triggers | 16 | entry_id | 0 |
| jquartz_job_details | 12 | job_name, job_group | 0 |
| jquartz_job_listeners | 3 | job_name, job_group, job_listener | 0 |
| jquartz_locks | 2 | lock_name | 0 |
| jquartz_paused_trigger_grps | 2 | trigger_group | 0 |
| jquartz_scheduler_state | 4 | instance_name | 0 |
| jquartz_simple_triggers | 6 | trigger_name, trigger_group | 0 |
| jquartz_simprop_triggers | 14 | trigger_name, trigger_group | 0 |
| jquartz_trigger_listeners | 3 | trigger_group, trigger_listener | 0 |
| jquartz_triggers | 17 | trigger_name, trigger_group | 0 |
| label | 4 | id | 0 |
| licenserolesdefault | 2 | id | 0 |
| licenserolesgroup | 4 | id | 0 |
| listenerconfig | 3 | id | 0 |
| mailserver | 18 | id | 0 |
| managedconfigurationitem | 7 | id | 0 |
| membershipbase | 3 | id | 0 |
| moved_issue_key | 3 | id | 0 |
| nodeassociation | 6 | source_node_id, source_node_entity, sink_node_id, sink_node_entity, association_type | 0 |
| nodeindexcounter | 4 | id | 0 |
| nomenclature_entries | 5 | id | 0 |
| notification | 7 | id | 0 |
| notificationinstance | 5 | id | 0 |
| notificationscheme | 3 | id | 0 |
| oauthconsumer | 11 | id | 0 |
| oauthconsumertoken | 7 | id | 0 |
| oauthspconsumer | 11 | id | 0 |
| oauthsptoken | 16 | id | 0 |
| optionconfiguration | 5 | id | 0 |
| os_currentstep | 10 | id | 0 |
| os_currentstep_prev | 2 | id, previous_id | 0 |
| os_historystep | 10 | id | 0 |
| os_historystep_prev | 2 | id, previous_id | 0 |
| os_wfentry | 4 | id | 0 |
| permissionscheme | 3 | id | 0 |
| permissionschemeattribute | 4 | id | 0 |
| pluginstate | 2 | pluginkey | 0 |
| pluginversion | 5 | id | 0 |
| portalpage | 8 | id | 0 |
| portletconfiguration | 8 | id | 0 |
| priority | 6 | id | 0 |
| productlicense | 2 | id | 0 |
| project | 15 | id | 0 |
| project_key | 3 | id | 0 |
| projectcategory | 3 | id | 0 |
| projectchangedtime | 2 | project_id | 0 |
| projectrole | 3 | id | 0 |
| projectroleactor | 5 | id | 0 |
| projectversion | 10 | id | 0 |
| propertydata | 2 | id | 0 |
| propertydate | 2 | id | 0 |
| propertydecimal | 2 | id | 0 |
| propertyentry | 5 | id | 0 |
| propertynumber | 2 | id | 0 |
| propertystring | 2 | id | 0 |
| propertytext | 2 | id | 0 |
| qrtz_calendars | 3 | calendar_name | 0 |
| qrtz_cron_triggers | 3 | id | 0 |
| qrtz_fired_triggers | 6 | entry_id | 0 |
| qrtz_job_details | 8 | id | 0 |
| qrtz_job_listeners | 3 | id | 0 |
| qrtz_simple_triggers | 5 | id | 0 |
| qrtz_trigger_listeners | 3 | id | 0 |
| qrtz_triggers | 11 | id | 0 |
| reindex_component | 4 | id | 0 |
| reindex_request | 8 | id | 0 |
| remembermetoken | 4 | id | 0 |
| remotelink | 19 | id | 0 |
| replicatedindexoperation | 9 | id | 0 |
| resolution | 5 | id | 0 |
| rundetails | 6 | id | 0 |
| schemeissuesecurities | 5 | id | 0 |
| schemeissuesecuritylevels | 4 | id | 0 |
| schemepermissions | 6 | id | 0 |
| searchrequest | 10 | id | 0 |
| secret | 3 | identifier | 0 |
| securityproperty | 2 | property_key | 0 |
| sequence_value_item | 2 | seq_name | 0 |
| serviceconfig | 5 | id | 0 |
| sharepermissions | 7 | id | 0 |
| tempattachmentsmonitor | 6 | temporary_attachment_id | 0 |
| trackback_ping | 7 | id | 0 |
| trustedapp | 11 | id | 0 |
| upgradehistory | 5 | upgradeclass | 0 |
| upgradetaskhistory | 5 | id | 0 |
| upgradetaskhistoryauditlog | 7 | id | 0 |
| upgradeversionhistory | 4 | targetbuild | 0 |
| userassociation | 6 | source_name, sink_node_id, sink_node_entity, association_type | 0 |
| userbase | 3 | id | 0 |
| userhistoryitem | 6 | id | 0 |
| userpickerfilter | 4 | id | 0 |
| userpickerfiltergroup | 3 | id | 0 |
| userpickerfilterrole | 3 | id | 0 |
| versioncontrol | 4 | id | 0 |
| votehistory | 4 | id | 0 |
| workflowscheme | 3 | id | 0 |
| workflowschemeentity | 4 | id | 0 |
| worklog | 11 | id | 0 |
| worklog_version | 5 | worklog_id | 0 |

## Detailed Table Information

### AO_0201F0_KB_HELPFUL_AGGR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COUNT | bigint | None |
| ID | bigint | NOT NULL |
| SERVICE_DESK_ID | bigint | None |
| START_TIME | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0201F0_KB_VIEW_AGGR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COUNT | bigint | None |
| ID | bigint | NOT NULL |
| SERVICE_DESK_ID | bigint | None |
| START_TIME | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0201F0_STATS_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT_KEY | character | None |
| EVENT_TIME | bigint | None |
| ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0201F0_STATS_EVENT_PARAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PARAM_NAME | character | None |
| PARAM_VALUE | character | None |
| STATS_EVENT_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| STATS_EVENT_ID | AO_0201F0_STATS_EVENT | ID |

---

### AO_0A5972_NOTIFICATION_SETTING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| TYPE | character | NOT NULL |
| USER_KEY | character | NOT NULL |
| VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0A5972_OAUTH2_CONFIGURATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BROWSER_CACHE_ENABLED | boolean | NOT NULL, DEFAULT |
| CLIENT_ID | character | NOT NULL |
| CONFIGURATION_ID | character | NOT NULL |
| ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0A5972_PUSH_REGISTRATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BUILD | character | NOT NULL |
| ENDPOINT | character | None |
| ID | character | NOT NULL |
| OS | character | NOT NULL |
| TOKEN | character | None |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_0AC321_RECOMMENDATION_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CATEGORY | character | None |
| CUSTOM_FIELD_ID | bigint | None |
| ID | character | NOT NULL |
| NAME | character | None |
| PERFORMANCE_IMPACT | double | None |
| PROJECT_IDS | text | None |
| RESOLVED | boolean | None |
| TYPE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_21D670_WHITELIST_RULES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ALLOWINBOUND | boolean | None |
| EXPRESSION | text | NOT NULL |
| ID | integer | NOT NULL |
| TYPE | character | NOT NULL |
| AUTHENTICATIONREQUIRED | boolean | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_21F425_MESSAGE_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENT | text | NOT NULL |
| ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_21F425_MESSAGE_MAPPING_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| MESSAGE_ID | character | NOT NULL |
| USER_HASH | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_21F425_USER_PROPERTY_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | NOT NULL |
| USER | character | NOT NULL |
| VALUE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_2C4E5C_MAILCHANNEL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | None |
| ENABLED | boolean | None |
| ID | integer | NOT NULL |
| MAIL_CHANNEL_KEY | character | None |
| MAIL_CONNECTION_ID | integer | None |
| MAX_RETRY_ON_FAILURE | integer | None |
| MODIFIED_BY | character | None |
| PROJECT_ID | bigint | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| MAIL_CONNECTION_ID | AO_2C4E5C_MAILCONNECTION | ID |

---

### AO_2C4E5C_MAILCONNECTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| EMAIL_ADDRESS | character | None |
| FOLDER | character | None |
| HOST_NAME | character | None |
| ID | integer | NOT NULL |
| PASSWORD | character | None |
| PORT | integer | None |
| PROTOCOL | character | None |
| PULL_FROM_DATE | bigint | None |
| TIMEOUT | bigint | None |
| TLS | boolean | None |
| UPDATED_TIMESTAMP | bigint | None |
| USER_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_2C4E5C_MAILGLOBALHANDLER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| HANDLER_TYPE | character | None |
| ID | integer | NOT NULL |
| MODULE_COMPLETE_KEY | character | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_2C4E5C_MAILHANDLER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| HANDLER_TYPE | character | None |
| ID | integer | NOT NULL |
| MAIL_CHANNEL_ID | integer | None |
| MODULE_COMPLETE_KEY | character | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| MAIL_CHANNEL_ID | AO_2C4E5C_MAILCHANNEL | ID |

---

### AO_2C4E5C_MAILITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| ID | integer | NOT NULL |
| MAIL_CONNECTION_ID | integer | None |
| STATUS | character | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_2C4E5C_MAILITEMAUDIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| FROM_ADDRESS | character | None |
| HANDLER_NAME_KEY | character | None |
| ID | integer | NOT NULL |
| ISSUE_KEY | character | None |
| MAIL_CHANNEL_ID | integer | None |
| MAIL_CHANNEL_NAME | character | None |
| MAIL_ITEM_ID | integer | None |
| MESSAGE | character | None |
| NO_OF_RETRY | integer | None |
| RESULT_STATUS | character | None |
| SUBJECT | character | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| MAIL_ITEM_ID | AO_2C4E5C_MAILITEM | ID |

---

### AO_2C4E5C_MAILITEMCHUNK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| MAIL_ITEM_ID | integer | None |
| MIME_MSG_CHUNK | text | None |
| MIME_MSG_CHUNK_IDX | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| MAIL_ITEM_ID | AO_2C4E5C_MAILITEM | ID |

---

### AO_2C4E5C_MAILRUNAUDIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | None |
| FAILURE_MESSAGE | character | None |
| ID | integer | NOT NULL |
| MAIL_CHANNEL_NAME | character | None |
| MAIL_CONNECTION_ID | integer | None |
| NO_OF_RETRY | integer | None |
| RUN_OUTCOME | character | None |
| UPDATED_TIMESTAMP | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_38321B_CUSTOM_CONTENT_LINK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENT_KEY | character | None |
| ID | integer | NOT NULL |
| LINK_LABEL | character | None |
| LINK_URL | character | None |
| SEQUENCE | integer | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_3B1893_LOOP_DETECTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COUNTER | integer | NOT NULL, DEFAULT |
| EXPIRES_AT | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| SENDER_EMAIL | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_DISABLED_CHECKS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HEALTH_CHECK_KEY | character | NOT NULL |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_HEALTH_CHECK_STATUS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPLICATION_NAME | character | None |
| COMPLETE_KEY | character | None |
| DESCRIPTION | text | None |
| FAILED_DATE | timestamp | None |
| FAILURE_REASON | text | None |
| ID | integer | NOT NULL |
| IS_HEALTHY | boolean | None |
| IS_RESOLVED | boolean | None |
| NODE_ID | character | None |
| RESOLVED_DATE | timestamp | None |
| SEVERITY | character | None |
| STATUS_NAME | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_HEALTH_CHECK_WATCHER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_PROPERTIES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PROPERTY_NAME | character | NOT NULL |
| PROPERTY_VALUE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_READ_NOTIFICATIONS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| IS_SNOOZED | boolean | None |
| NOTIFICATION_ID | integer | NOT NULL |
| SNOOZE_COUNT | integer | None |
| SNOOZE_DATE | timestamp | None |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_SHORTENED_KEY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4789DD_TASK_MONITOR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLUSTERED_TASK_ID | character | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| ID | integer | NOT NULL |
| NODE_ID | character | None |
| PROGRESS_MESSAGE | text | None |
| PROGRESS_PERCENTAGE | integer | None |
| SERIALIZED_ERRORS | text | None |
| SERIALIZED_WARNINGS | text | None |
| TASK_ID | character | NOT NULL |
| TASK_MONITOR_KIND | character | None |
| TASK_STATUS | text | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_4AEACD_WEBHOOK_DAO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ENABLED | boolean | None |
| ENCODED_EVENTS | text | None |
| EXCLUDE_ISSUE_DETAILS | boolean | None |
| FILTER | text | None |
| ID | integer | NOT NULL |
| JQL | character | None |
| LAST_UPDATED | timestamp | NOT NULL |
| LAST_UPDATED_USER | character | NOT NULL |
| NAME | text | NOT NULL |
| PARAMETERS | text | None |
| REGISTRATION_METHOD | character | NOT NULL |
| URL | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_ASYNCUPGRADERECORD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | None |
| CREATED_DATE | timestamp | None |
| EXCEPTION | text | None |
| ID | integer | NOT NULL |
| MESSAGE | text | None |
| SERVICE_DESK_VERSION | character | None |
| UPGRADE_TASK_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_CAPABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CAPABILITY_NAME | character | None |
| CAPABILITY_VALUE | character | None |
| ID | integer | NOT NULL |
| SERVICE_DESK_ID | integer | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_CONFLUENCEKB

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPLINKS_APPLICATION_ID | character | None |
| APPLINK_NAME | character | None |
| APPLINK_URL | text | None |
| ID | integer | NOT NULL |
| SERVICE_DESK_ID | integer | None |
| SPACE_KEY | character | None |
| SPACE_NAME | character | None |
| SPACE_URL | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_CONFLUENCEKBENABLED

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFLUENCE_KBID | integer | None |
| ENABLED | boolean | None |
| FORM_ID | integer | None |
| ID | integer | NOT NULL |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| CONFLUENCE_KBID | AO_54307E_CONFLUENCEKB | ID |
| FORM_ID | AO_54307E_VIEWPORTFORM | ID |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_CONFLUENCEKBLABELS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFLUENCE_KBID | integer | None |
| FORM_ID | integer | None |
| ID | integer | NOT NULL |
| LABEL | character | None |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| CONFLUENCE_KBID | AO_54307E_CONFLUENCEKB | ID |
| FORM_ID | AO_54307E_VIEWPORTFORM | ID |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_CUSTOMGLOBALTHEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENT_LINK_COLOR | character | None |
| CONTENT_TEXT_COLOR | character | None |
| CUSTOM_CSS | text | None |
| HEADER_BADGE_BGCOLOR | character | None |
| HEADER_BGCOLOR | character | None |
| HEADER_LINK_COLOR | character | None |
| HEADER_LINK_HOVER_BGCOLOR | character | None |
| HEADER_LINK_HOVER_COLOR | character | None |
| HELP_CENTER_TITLE | character | None |
| ID | integer | NOT NULL |
| LOGO_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_CUSTOMTHEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HEADER_BGCOLOR | character | None |
| HEADER_LINK_COLOR | character | None |
| HEADER_LINK_HOVER_BGCOLOR | character | None |
| HEADER_LINK_HOVER_COLOR | character | None |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_EMAILCHANNELSETTING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EMAIL_ADDRESS | character | None |
| ID | integer | NOT NULL |
| LAST_PROCEEDED_TIME | bigint | None |
| MAIL_CHANNEL_KEY | character | None |
| ON_DEMAND | boolean | None |
| REQUEST_TYPE_ID | integer | None |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| REQUEST_TYPE_ID | AO_54307E_VIEWPORTFORM | ID |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_EMAILSETTINGS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EMAIL_ADDRESS | character | None |
| ENABLED | boolean | None |
| ID | integer | NOT NULL |
| JIRA_MAIL_SERVER_ID | bigint | None |
| LAST_PROCEEDED_TIME | bigint | None |
| ON_DEMAND | boolean | None |
| REQUEST_TYPE_ID | integer | None |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| REQUEST_TYPE_ID | AO_54307E_VIEWPORTFORM | ID |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_GOAL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CALENDAR_ID | integer | None |
| DEFAULT_GOAL | boolean | DEFAULT |
| ID | integer | NOT NULL |
| JQL_QUERY | text | None |
| POS | integer | None |
| TARGET_DURATION | bigint | None |
| TIME_METRIC_ID | integer | None |
| TIME_UPDATED_DATE | timestamp | None |
| TIME_UPDATED_MS_EPOCH | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| TIME_METRIC_ID | AO_54307E_TIMEMETRIC | ID |

---

### AO_54307E_GROUP

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DELETED_TIME | bigint | None |
| GROUP_NAME | character | None |
| ID | integer | NOT NULL |
| ORDER | integer | None |
| VIEWPORT_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| VIEWPORT_ID | AO_54307E_VIEWPORT | ID |

---

### AO_54307E_GROUPTOREQUESTTYPE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| GROUP_ID | integer | None |
| ID | integer | NOT NULL |
| ORDER | integer | None |
| REQUEST_TYPE_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| GROUP_ID | AO_54307E_GROUP | ID |
| REQUEST_TYPE_ID | AO_54307E_VIEWPORTFORM | ID |

---

### AO_54307E_IMAGES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENTS | text | None |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_METRICCONDITION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONDITION_ID | character | None |
| FACTORY_KEY | character | None |
| ID | integer | NOT NULL |
| PLUGIN_KEY | character | None |
| TIME_METRIC_ID | integer | None |
| TYPE_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| TIME_METRIC_ID | AO_54307E_TIMEMETRIC | ID |

---

### AO_54307E_OUT_EMAIL_SETTINGS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EMAIL_SUBJECT_PREFIX_ENABLED | boolean | None |
| ID | integer | NOT NULL |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_PARTICIPANTSETTINGS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTOCOMPLETE_ENABLED | boolean | None |
| ID | integer | NOT NULL |
| MANAGE_ENABLED | boolean | None |
| SERVICE_DESK_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_QUEUE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| JQL | text | None |
| NAME | character | None |
| PROJECT_ID | bigint | None |
| PROJECT_KEY | character | None |
| QUEUE_ORDER | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_QUEUECOLUMN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLUMN_ID | character | None |
| COLUMN_ORDER | integer | None |
| ID | integer | NOT NULL |
| QUEUE_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| QUEUE_ID | AO_54307E_QUEUE | ID |

---

### AO_54307E_REPORT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_DATE | timestamp | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| REPORT_ORDER | integer | None |
| REPORT_TYPE | character | None |
| SERVICE_DESK_ID | integer | None |
| UPDATED_DATE | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_SERIES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | None |
| CREATED_DATE | timestamp | None |
| ID | integer | NOT NULL |
| JQL | text | None |
| REPORT_ID | integer | None |
| SERIES_DATA_TYPE | character | None |
| SERIES_LABEL | character | None |
| TIME_METRIC_ID | bigint | None |
| UPDATED_DATE | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| REPORT_ID | AO_54307E_REPORT | ID |

---

### AO_54307E_SERVICEDESK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY_USER_KEY | character | None |
| CREATED_DATE | timestamp | None |
| CREATED_WITH_EMPTY_PROJECT | boolean | None |
| DISABLED | boolean | None |
| ID | integer | NOT NULL |
| LEGACY_TRANSITION_DISABLED | boolean | None |
| OPEN_CUSTOMER_ACCESS | integer | None |
| PROJECT_ID | bigint | None |
| PROJECT_KEY | character | None |
| PUBLIC_SIGNUP | integer | None |
| VERSION_CREATED_AT | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_STATUSMAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FORM_ID | integer | None |
| ID | integer | NOT NULL |
| STATUS_ID | character | None |
| STATUS_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| FORM_ID | AO_54307E_VIEWPORTFORM | ID |

---

### AO_54307E_SUBSCRIPTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| ISSUE_ID | bigint | None |
| SUBSCRIBED | boolean | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_SYNCUPGRADERECORD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | None |
| CREATED_DATE | timestamp | None |
| EXCEPTION | text | None |
| ID | integer | NOT NULL |
| MESSAGE | text | None |
| SERVICE_DESK_VERSION | character | None |
| UPGRADE_TASK_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_54307E_THRESHOLD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| REMAINING_TIME | bigint | None |
| TIME_METRIC_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| TIME_METRIC_ID | AO_54307E_TIMEMETRIC | ID |

---

### AO_54307E_TIMEMETRIC

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_DATE | bigint | None |
| CUSTOM_FIELD_ID | bigint | None |
| DEFINITION_CHANGE_DATE | timestamp | None |
| DEFINITION_CHANGE_MS_EPOCH | bigint | None |
| GOALS_CHANGE_DATE | timestamp | None |
| GOALS_CHANGE_MS_EPOCH | bigint | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| SERVICE_DESK_ID | integer | None |
| THRESHOLDS_CHANGE_MS_EPOCH | bigint | None |
| THRESHOLDS_CONFIG_CHANGE_DATE | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SERVICE_DESK_ID | AO_54307E_SERVICEDESK | ID |

---

### AO_54307E_VIEWPORT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | text | None |
| ID | integer | NOT NULL |
| KEY | character | None |
| LOGO_ID | integer | None |
| NAME | character | None |
| PROJECT_ID | bigint | None |
| SEND_EMAIL_NOTIFICATIONS | boolean | None |
| THEME_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| THEME_ID | AO_54307E_CUSTOMTHEME | ID |

---

### AO_54307E_VIEWPORTFIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | text | None |
| DISPLAYED | boolean | None |
| FIELD_ID | character | None |
| FIELD_ORDER | integer | None |
| FIELD_TYPE | character | None |
| FORM_ID | integer | None |
| ID | integer | NOT NULL |
| LABEL | character | None |
| REQUIRED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| FORM_ID | AO_54307E_VIEWPORTFORM | ID |

---

### AO_54307E_VIEWPORTFIELDVALUE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FIELD_ID | integer | None |
| FIELD_NAME | character | None |
| ID | integer | NOT NULL |
| VALUE | text | None |
| VALUE_ORDER | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| FIELD_ID | AO_54307E_VIEWPORTFIELD | ID |

---

### AO_54307E_VIEWPORTFORM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CALL_TO_ACTION | text | None |
| DESCRIPTION | text | None |
| FORM_ORDER | integer | None |
| ICON | integer | None |
| ICON_ID | bigint | None |
| ID | integer | NOT NULL |
| INTRO | text | None |
| ISSUE_TYPE_ID | bigint | None |
| KEY | character | None |
| NAME | character | None |
| VIEWPORT_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| VIEWPORT_ID | AO_54307E_VIEWPORT | ID |

---

### AO_550953_SHORTCUT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ICON | character | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| PROJECT_ID | bigint | None |
| SHORTCUT_URL | text | None |
| URL | character | None |
| SEQUENCE | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_563AEE_ACTIVITY_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVITY_ID | bigint | NOT NULL |
| ACTOR_ID | integer | None |
| CONTENT | text | None |
| GENERATOR_DISPLAY_NAME | character | None |
| GENERATOR_ID | character | None |
| ICON_ID | integer | None |
| ID | character | None |
| ISSUE_KEY | character | None |
| OBJECT_ID | integer | None |
| POSTER | character | None |
| PROJECT_KEY | character | None |
| PUBLISHED | timestamp | None |
| TARGET_ID | integer | None |
| TITLE | character | None |
| URL | character | None |
| USERNAME | character | None |
| VERB | character | None |

**Primary Key(s):** ACTIVITY_ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| ACTOR_ID | AO_563AEE_ACTOR_ENTITY | ID |
| ICON_ID | AO_563AEE_MEDIA_LINK_ENTITY | ID |
| OBJECT_ID | AO_563AEE_OBJECT_ENTITY | ID |
| TARGET_ID | AO_563AEE_TARGET_ENTITY | ID |

---

### AO_563AEE_ACTOR_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FULL_NAME | character | None |
| ID | integer | NOT NULL |
| PROFILE_PAGE_URI | character | None |
| PROFILE_PICTURE_URI | character | None |
| USERNAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_563AEE_MEDIA_LINK_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DURATION | integer | None |
| HEIGHT | integer | None |
| ID | integer | NOT NULL |
| URL | character | None |
| WIDTH | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_563AEE_OBJECT_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENT | character | None |
| DISPLAY_NAME | character | None |
| ID | integer | NOT NULL |
| IMAGE_ID | integer | None |
| OBJECT_ID | character | None |
| OBJECT_TYPE | character | None |
| SUMMARY | character | None |
| URL | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IMAGE_ID | AO_563AEE_MEDIA_LINK_ENTITY | ID |

---

### AO_563AEE_TARGET_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTENT | character | None |
| DISPLAY_NAME | character | None |
| ID | integer | NOT NULL |
| IMAGE_ID | integer | None |
| OBJECT_ID | character | None |
| OBJECT_TYPE | character | None |
| SUMMARY | character | None |
| URL | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IMAGE_ID | AO_563AEE_MEDIA_LINK_ENTITY | ID |

---

### AO_56464C_APPROVAL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPROVE_CONDITION_TYPE | character | None |
| APPROVE_CONDITION_VALUE | character | None |
| COMPLETED_DATE | bigint | None |
| CREATED_DATE | bigint | None |
| DECISION | character | None |
| ID | integer | NOT NULL |
| ISSUE_ID | bigint | None |
| NAME | character | None |
| STATUS_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_56464C_APPROVER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPROVAL_ID | integer | None |
| ID | integer | NOT NULL |
| TYPE | character | None |
| VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| APPROVAL_ID | AO_56464C_APPROVAL | ID |

---

### AO_56464C_APPROVERDECISION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPROVAL_ID | integer | None |
| DECISION | character | None |
| ID | integer | NOT NULL |
| SENT_DATE | bigint | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| APPROVAL_ID | AO_56464C_APPROVAL | ID |

---

### AO_56464C_NOTIFICATIONRECORD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPROVAL_ID | integer | None |
| ID | integer | NOT NULL |
| SENT_DATE | bigint | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| APPROVAL_ID | AO_56464C_APPROVAL | ID |

---

### AO_575BF5_DEV_SUMMARY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED | timestamp | NOT NULL |
| ID | integer | NOT NULL |
| ISSUE_ID | bigint | NOT NULL, DEFAULT |
| JSON | text | None |
| PROVIDER_SOURCE_ID | character | NOT NULL |
| UPDATED | timestamp | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_575BF5_PROCESSED_COMMITS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMMIT_HASH | character | NOT NULL |
| ID | integer | NOT NULL |
| METADATA_HASH | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_575BF5_PROVIDER_ISSUE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| ISSUE_ID | bigint | NOT NULL, DEFAULT |
| PROVIDER_SOURCE_ID | character | NOT NULL |
| STALE_AFTER | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_575BF5_PROVIDER_SEQ_NO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PROVIDER_SOURCE_ID | character | NOT NULL |
| SEQUENCE_NO | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_587B34_GLANCE_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPLICATION_USER_KEY | character | None |
| JQL | character | None |
| NAME | character | None |
| ROOM_ID | bigint | NOT NULL |
| STATE | character | None |
| SYNC_NEEDED | boolean | None |

**Primary Key(s):** ROOM_ID

**Foreign Keys:** None

---

### AO_587B34_PROJECT_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIGURATION_GROUP_ID | character | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| NAME_UNIQUE_CONSTRAINT | character | UNIQUE |
| PROJECT_ID | bigint | None |
| ROOM_ID | bigint | None |
| VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_AUDIT_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHOR_KEY | character | None |
| CATEGORY | character | None |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| DESCRIPTION | text | None |
| DURATION | bigint | DEFAULT |
| END_TIME | timestamp | None |
| END_TO_END_DURATION | bigint | None |
| EVENT_SOURCE | character | None |
| ID | bigint | NOT NULL |
| OBJECT_ITEM_ID | bigint | None |
| OBJECT_ITEM_NAME | character | None |
| OBJECT_ITEM_PARENT_ID | character | None |
| OBJECT_ITEM_PARENT_NAME | character | None |
| OBJECT_ITEM_TYPE | character | None |
| START_TIME | timestamp | None |
| SUMMARY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_AUDIT_ITEM_ASC_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ASSOC_ITEM_ID | character | None |
| AUDIT_ITEM_COMPONENT_CHANGE_ID | bigint | None |
| AUDIT_ITEM_ID | bigint | None |
| ID | bigint | NOT NULL |
| NAME | character | None |
| PARENT_ID | character | None |
| PARENT_NAME | character | None |
| TYPE_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AUDIT_ITEM_COMPONENT_CHANGE_ID | AO_589059_AUDIT_ITEM_COMP_CGE | ID |
| AUDIT_ITEM_ID | AO_589059_AUDIT_ITEM | ID |

---

### AO_589059_AUDIT_ITEM_CGE_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ITEM_COMPONENT_CHANGE_ID | bigint | None |
| AUDIT_ITEM_ID | bigint | None |
| CHANGE_FROM | text | None |
| CHANGE_TO | text | None |
| FIELD_NAME | character | None |
| ID | bigint | NOT NULL |
| MESSAGE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AUDIT_ITEM_COMPONENT_CHANGE_ID | AO_589059_AUDIT_ITEM_COMP_CGE | ID |
| AUDIT_ITEM_ID | AO_589059_AUDIT_ITEM | ID |

---

### AO_589059_AUDIT_ITEM_COMP_CGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ITEM_ID | bigint | None |
| COMPONENT | character | None |
| COMPONENT_ID | bigint | None |
| COMPONENT_NAME_KEY | character | None |
| DURATION | bigint | DEFAULT |
| ID | bigint | NOT NULL |
| OPTIMISED_IDS | character | None |
| START_TIME | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AUDIT_ITEM_ID | AO_589059_AUDIT_ITEM | ID |

---

### AO_589059_AUDIT_ITEM_PROJECT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ITEM_ID | bigint | None |
| ID | bigint | NOT NULL |
| PROJECT_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AUDIT_ITEM_ID | AO_589059_AUDIT_ITEM | ID |

---

### AO_589059_AUTOMATION_QUEUE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ITEM_ID | bigint | None |
| CLAIMANT | character | None |
| CLAIM_COUNT | integer | DEFAULT |
| CLAIM_TIME | timestamp | None |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| EXECUTION_UUID | character | None |
| ID | bigint | NOT NULL |
| PAYLOAD | text | None |
| PRIORITY | bigint | NOT NULL, DEFAULT |
| RULE_ID | bigint | None |
| ZIPPED_PAYLOAD | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AUDIT_ITEM_ID | AO_589059_AUDIT_ITEM | ID |

---

### AO_589059_COUNTERS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLIENT_KEY | character | NOT NULL |
| COUNT | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_LEGACY_RULE_LINK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LEGACY_ID | bigint | NOT NULL, DEFAULT |
| NEW_ID | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_CFG_COMPONENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMPONENT | character | NOT NULL |
| CONDITION_PARENT_ID | bigint | None |
| ID | bigint | NOT NULL |
| PARENT_CFG_COMPONENT_ID | bigint | None |
| RULE_CONFIG_ID | bigint | NOT NULL |
| SCHEMA_VERSION | integer | NOT NULL, DEFAULT |
| SEQUENCE | integer | NOT NULL, DEFAULT |
| TYPE | character | NOT NULL |
| VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| CONDITION_PARENT_ID | AO_589059_RULE_CFG_COMPONENT | ID |
| PARENT_CFG_COMPONENT_ID | AO_589059_RULE_CFG_COMPONENT | ID |
| RULE_CONFIG_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_RULE_CFG_PROJ_ASSOC

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PROJECT_ID | character | None |
| PROJECT_TYPE_KEY | character | None |
| RULE_CONFIG_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_CONFIG_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_RULE_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTOR_KEY | character | NOT NULL |
| AUTHOR_KEY | character | NOT NULL |
| CAN_OTHER_RULE_TRIGGER | boolean | None |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| DESCRIPTION | text | None |
| ID | bigint | NOT NULL |
| NAME | character | NOT NULL |
| NOTIFY_ON_ERROR | character | NOT NULL, DEFAULT |
| PROJECT_ID | character | None |
| PROJECT_TYPE_KEY | character | None |
| STATE | character | NOT NULL |
| UPDATED | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_LABEL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | NOT NULL |
| ID | bigint | NOT NULL |
| NAME | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_SCHEDULE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLIENT_KEY | character | NOT NULL |
| ERROR_COUNT | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| NEXT_EXECUTION | timestamp | NOT NULL |
| PAYLOAD | character | None |
| RULE_CONFIG_ID | bigint | NOT NULL |
| TYPE | character | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_CONFIG_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_RULE_SECRET

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| VALUE | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_STAT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ID | bigint | NOT NULL |
| CATEGORY | character | NOT NULL, DEFAULT |
| CREATED | timestamp | NOT NULL |
| DURATION | bigint | NOT NULL |
| EVENT_HASH | character | None |
| ID | bigint | NOT NULL |
| QUEUED_ITEM_COUNT | integer | NOT NULL, DEFAULT |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_STATE_LATEST

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CURRENT_AUDIT_ID | bigint | NOT NULL |
| CURRENT_CATEGORY | character | NOT NULL |
| CURRENT_CREATED | timestamp | NOT NULL |
| EXEC_COUNT | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| PREVIOUS_AUDIT_ID | bigint | None |
| PREVIOUS_CATEGORY | character | None |
| PREVIOUS_CREATED | timestamp | None |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_STAT_ROLLUP_DAY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ID | bigint | NOT NULL, DEFAULT |
| CATEGORY | character | NOT NULL, DEFAULT |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| DURATION | bigint | NOT NULL |
| END_TO_END_DURATION | bigint | NOT NULL |
| EXECUTION_COUNT | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| QUEUED_ITEM_COUNT | bigint | NOT NULL |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_STAT_ROLLUP_HR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ID | bigint | NOT NULL, DEFAULT |
| CATEGORY | character | NOT NULL, DEFAULT |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| DURATION | bigint | NOT NULL |
| END_TO_END_DURATION | bigint | NOT NULL |
| EXECUTION_COUNT | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| QUEUED_ITEM_COUNT | bigint | NOT NULL |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_STAT_ROLLUP_MIN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUDIT_ID | bigint | NOT NULL, DEFAULT |
| CATEGORY | character | NOT NULL, DEFAULT |
| CLIENT_KEY | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| DURATION | bigint | NOT NULL |
| END_TO_END_DURATION | bigint | NOT NULL |
| EXECUTION_COUNT | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| QUEUED_ITEM_COUNT | bigint | NOT NULL |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_589059_RULE_TAG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| RULE_CONFIG_ID | bigint | NOT NULL |
| TAG_TYPE | character | NOT NULL |
| TAG_VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_CONFIG_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_RULE_TO_LABEL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LABEL_ID | bigint | NOT NULL |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| LABEL_ID | AO_589059_RULE_LABEL | ID |
| RULE_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_RULE_TO_SECRET

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| RULE_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_ID | AO_589059_RULE_CONFIG | ID |

---

### AO_589059_SECRET_PROJ_ASSOC

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PROJECT_ID | character | None |
| RULE_SECRET_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_SECRET_ID | AO_589059_RULE_SECRET | ID |

---

### AO_5FB9D7_AOHIP_CHAT_LINK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADDON_TOKEN_EXPIRY | timestamp | None |
| API_URL | character | None |
| CONNECT_DESCRIPTOR | text | None |
| GROUP_ID | integer | None |
| GROUP_NAME | character | None |
| ID | integer | NOT NULL |
| OAUTH_ID | character | None |
| SECRET_KEY | character | None |
| SYSTEM_PASSWORD | character | None |
| SYSTEM_TOKEN_EXPIRY | timestamp | None |
| SYSTEM_USER | character | None |
| SYSTEM_USER_TOKEN | character | None |
| TOKEN | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_5FB9D7_AOHIP_CHAT_USER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HIP_CHAT_LINK_ID | integer | None |
| HIP_CHAT_USER_ID | character | None |
| HIP_CHAT_USER_NAME | character | None |
| ID | integer | NOT NULL |
| REFRESH_CODE | character | None |
| USER_KEY | character | None |
| USER_SCOPES | character | None |
| USER_TOKEN | character | None |
| USER_TOKEN_EXPIRY | timestamp | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| HIP_CHAT_LINK_ID | AO_5FB9D7_AOHIP_CHAT_LINK | ID |

---

### AO_60DB71_AUDITENTRY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CATEGORY | character | NOT NULL |
| DATA | text | NOT NULL |
| ENTITY_CLASS | character | NOT NULL |
| ENTITY_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| TIME | bigint | None |
| USER | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_BOARDADMINS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| RAPID_VIEW_ID | bigint | NOT NULL |
| TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_CARDCOLOR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | None |
| ID | bigint | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| RAPID_VIEW_ID | bigint | NOT NULL |
| STRATEGY | character | None |
| VAL | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_CARDLAYOUT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FIELD_ID | character | NOT NULL |
| ID | bigint | NOT NULL |
| MODE_NAME | character | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| RAPID_VIEW_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_COLUMN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| MAXIM | double | None |
| MINIM | double | None |
| NAME | character | None |
| POS | integer | NOT NULL, DEFAULT |
| RAPID_VIEW_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_COLUMNSTATUS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLUMN_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| STATUS_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| COLUMN_ID | AO_60DB71_COLUMN | ID |

---

### AO_60DB71_DETAILVIEWFIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FIELD_ID | character | NOT NULL |
| ID | bigint | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| RAPID_VIEW_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_ESTIMATESTATISTIC

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FIELD_ID | character | None |
| ID | bigint | NOT NULL |
| RAPID_VIEW_ID | bigint | NOT NULL |
| TYPE_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_ISSUERANKING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CUSTOM_FIELD_ID | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| ISSUE_ID | bigint | NOT NULL, DEFAULT |
| NEXT_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_ISSUERANKINGLOG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CUSTOM_FIELD_ID | bigint | None |
| ID | bigint | NOT NULL |
| ISSUE_ID | bigint | None |
| LOG_TYPE | character | None |
| NEW_NEXT_ID | bigint | None |
| NEW_PREVIOUS_ID | bigint | None |
| OLD_NEXT_ID | bigint | None |
| OLD_PREVIOUS_ID | bigint | None |
| SANITY_CHECKED | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_LEXORANK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BUCKET | integer | DEFAULT |
| FIELD_ID | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| ISSUE_ID | bigint | NOT NULL, DEFAULT |
| LOCK_HASH | character | None |
| LOCK_TIME | bigint | None |
| RANK | character | NOT NULL |
| TYPE | integer | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_LEXORANKBALANCER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DISABLE_RANK_OPERATIONS | boolean | NOT NULL |
| FIELD_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| REBALANCE_TIME | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_NONWORKINGDAY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| ISO8601_DATE | character | NOT NULL |
| WORKING_DAYS_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| WORKING_DAYS_ID | AO_60DB71_WORKINGDAYS | ID |

---

### AO_60DB71_QUICKFILTER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | character | None |
| ID | bigint | NOT NULL |
| LONG_QUERY | text | None |
| NAME | character | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| QUERY | character | None |
| RAPID_VIEW_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_RANKABLEOBJECT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_RAPIDVIEW

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CARD_COLOR_STRATEGY | character | None |
| ID | bigint | NOT NULL |
| KAN_PLAN_ENABLED | boolean | None |
| NAME | character | NOT NULL |
| OWNER_USER_NAME | character | NOT NULL |
| SAVED_FILTER_ID | bigint | NOT NULL |
| SHOW_DAYS_IN_COLUMN | boolean | None |
| SPRINTS_ENABLED | boolean | None |
| SWIMLANE_STRATEGY | character | None |
| OLD_DONE_ISSUES_CUTOFF | character | None |
| SHOW_EPIC_AS_PANEL | boolean | None |
| REFINED_VELOCITY_ACTIVE | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_SPRINT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOSED | boolean | NOT NULL |
| COMPLETE_DATE | bigint | None |
| END_DATE | bigint | None |
| GOAL | text | None |
| ID | bigint | NOT NULL |
| NAME | character | NOT NULL |
| RAPID_VIEW_ID | bigint | None |
| SEQUENCE | bigint | None |
| STARTED | boolean | None |
| START_DATE | bigint | None |
| ACTIVATED_DATE | bigint | None |
| AUTO_START_STOP | boolean | None |
| SYNCED | boolean | None |
| INCOMPLETE_ISSUES_DESTINATION | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_STATSFIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| RAPID_VIEW_ID | bigint | NOT NULL |
| TYPE_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_SUBQUERY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LONG_QUERY | text | None |
| QUERY | character | None |
| RAPID_VIEW_ID | bigint | None |
| SECTION | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_SWIMLANE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DEFAULT_LANE | boolean | NOT NULL, DEFAULT |
| DESCRIPTION | character | None |
| ID | bigint | NOT NULL |
| LONG_QUERY | text | None |
| NAME | character | NOT NULL |
| POS | integer | NOT NULL, DEFAULT |
| QUERY | character | None |
| RAPID_VIEW_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_TRACKINGSTATISTIC

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FIELD_ID | character | None |
| ID | bigint | NOT NULL |
| RAPID_VIEW_ID | bigint | NOT NULL |
| TYPE_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_60DB71_VERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| START_DATE | bigint | None |
| VERSION_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_60DB71_WORKINGDAYS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FRIDAY | boolean | NOT NULL |
| ID | bigint | NOT NULL |
| MONDAY | boolean | NOT NULL |
| RAPID_VIEW_ID | bigint | NOT NULL |
| SATURDAY | boolean | NOT NULL |
| SUNDAY | boolean | NOT NULL |
| THURSDAY | boolean | NOT NULL |
| TIMEZONE | character | NOT NULL |
| TUESDAY | boolean | NOT NULL |
| WEDNESDAY | boolean | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RAPID_VIEW_ID | AO_60DB71_RAPIDVIEW | ID |

---

### AO_6FF49D_ACCESS_LOG_PRC_CTRL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END_TIMESTAMP | bigint | None |
| ID | integer | NOT NULL |
| INST_ANALYSIS_CTRL_ID | integer | NOT NULL |
| LAST_UPDATE_TIMESTAMP | bigint | None |
| MESSAGE | text | None |
| NODE | character | NOT NULL |
| RETRY_COUNT | integer | DEFAULT |
| START_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| STATUS | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| INST_ANALYSIS_CTRL_ID | AO_6FF49D_INST_ANALYSIS_CTRL | ID |

---

### AO_6FF49D_ACCESS_LOG_PRC_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_LOG_PROC_CTRL_ID | integer | NOT NULL |
| END_TIMESTAMP | bigint | None |
| FILE_NAME | character | None |
| ID | integer | NOT NULL |
| MESSAGE | text | None |
| PROCESSING_DATE | timestamp | NOT NULL |
| START_TIMESTAMP | bigint | None |
| STATUS | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| ACCESS_LOG_PROC_CTRL_ID | AO_6FF49D_ACCESS_LOG_PRC_CTRL | ID |

---

### AO_6FF49D_ACTUAL_MIG_COUNTS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ENTITY_TYPE | character | None |
| EXECUTION_ID | character | NOT NULL |
| FAIL_COUNT | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| PROJECT_KEY | character | None |
| SUCCESS_COUNT | bigint | NOT NULL, DEFAULT |
| TOTAL_COUNT | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_AD_PRELOAD_STATUS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_APP_KEY | character | NOT NULL |
| CLOUD_ID | character | NOT NULL |
| CONTEXT_TYPE | character | NOT NULL |
| CONTEXT_VALUE | character | None |
| CREATED_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| FAILED_REASON | text | None |
| ID | integer | NOT NULL |
| INFO | character | None |
| MIGRATION_ID | character | None |
| S3_KEY | character | None |
| SERVER_APP_KEY | character | NOT NULL |
| TRANSFER_ID | character | None |
| UPDATED_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| UPLOADED | boolean | NOT NULL, DEFAULT |
| VENDOR_FILE_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_ANALYTICS_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT | text | NOT NULL |
| EVENT_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| EVENT_TYPE | character | NOT NULL |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_API_USAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| API_TYPE | character | NOT NULL |
| COUNT | bigint | NOT NULL, DEFAULT |
| DATE | timestamp | NOT NULL |
| HTTP_METHOD | character | NOT NULL |
| ID | integer | NOT NULL |
| LOOKUP_HASH | bigint | NOT NULL, DEFAULT |
| PROJECT_IDS_JSON | text | NOT NULL |
| REFERRER_TYPE | character | NOT NULL |
| USERNAME_HASH | character | None |
| USER_AGENT_TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_APP_ASSESSMENT_INFO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_SCOPES | character | None |
| ALTERNATIVE_APP_KEY | character | None |
| APP_KEY | character | NOT NULL |
| CONSENT | character | None |
| MIGRATION_NOTES | character | None |
| MIGRATION_STATUS | character | NOT NULL |

**Primary Key(s):** APP_KEY

**Foreign Keys:** None

---

### AO_6FF49D_BG_TASK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | bigint | DEFAULT |
| DESCRIPTION | character | None |
| ID | integer | NOT NULL |
| PROGRESS | integer | DEFAULT |
| STATUS | character | None |
| TASK_ID | character | None |
| UPDATED_AT | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_BG_TASK_UNITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | bigint | DEFAULT |
| ID | integer | NOT NULL |
| NODE_ID | character | None |
| STATUS | character | None |
| TASK_ID | character | None |
| TASK_UNIT_ID | character | None |
| UPDATED_AT | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_BROWSER_METRICS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | bigint | DEFAULT |
| ID | integer | NOT NULL |
| METRICS_JSON | character | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_CLOUD_SITE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_EDITION | character | None |
| CLOUD_ID | character | NOT NULL |
| CLOUD_TYPE | character | None |
| CLOUD_URL | character | None |
| CONTAINER_TOKEN | character | None |
| PRODUCTS_JSON | text | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |

**Primary Key(s):** CLOUD_ID

**Foreign Keys:** None

---

### AO_6FF49D_CONFIG_ITEMS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_ITEM_ID | character | None |
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| NAME | character | NOT NULL |
| TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_CORRECTED_EMAIL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCOUNT_TYPE | character | None |
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| DRAFT | boolean | DEFAULT |
| ID | character | NOT NULL |
| NEW_EMAIL | character | None |
| OLD_EMAIL | character | None |
| TOMBSTONE | boolean | None |
| TYPE | character | None |
| UDC_MODE | character | None |
| UPDATED_BY | character | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |
| USER_KEY | character | None |
| USER_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_DAILY_USAGE_METRICS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DAILY_ACTIVE_USERS | integer | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| INST_ANALYSIS_CTRL_ID | integer | NOT NULL |
| METRICS_DATE | timestamp | NOT NULL |
| NODES_PROCESSING_JSON | text | NOT NULL |
| PEAK_HOURLY_REQUESTS_BY_DAY | integer | NOT NULL, DEFAULT |
| PEAK_HOURLY_USERS_BY_DAY | integer | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| INST_ANALYSIS_CTRL_ID | AO_6FF49D_INST_ANALYSIS_CTRL | ID |

---

### AO_6FF49D_DOMAIN_SCAN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BLOCKED_DOMAINS_COUNT | bigint | DEFAULT |
| DISTINCT_DOMAINS_COUNT | bigint | DEFAULT |
| EXECUTION_TIME | bigint | DEFAULT |
| FINISHED_AT | bigint | DEFAULT |
| ID | character | NOT NULL |
| LOOKUP_METHOD | character | None |
| STARTED_AT | bigint | DEFAULT |
| STATUS | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_DRY_RUN_MIGRATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| MIGRATION_ID | character | NOT NULL |
| PLAN_ID | character | NOT NULL |
| STARTED_BY | character | NOT NULL |

**Primary Key(s):** MIGRATION_ID

**Foreign Keys:** None

---

### AO_6FF49D_EMAIL_TRST_DMN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVE_USERS | integer | DEFAULT |
| DOMAIN_NAME | character | NOT NULL |
| ID | character | NOT NULL |
| INACTIVE_USERS | integer | DEFAULT |
| REVIEW_METHOD | character | None |
| RULE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_EXPECTED_MIG_COUNTS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ENTITY_TYPE | character | None |
| ENTITY_TYPE_COUNT | bigint | NOT NULL, DEFAULT |
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| PROJECT_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_EXPELLED_USER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| EMAIL | character | None |
| EXECUTION_ID | character | None |
| ID | character | NOT NULL |
| PREFLIGHT_CHECK_TYPE | character | None |
| UPDATED_BY | character | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_EXPORT_ERROR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_ID | character | NOT NULL |
| ERROR | text | NOT NULL |
| ERROR_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| MIGRATION_ID | character | None |
| MIGRATION_SCOPE_ID | character | None |
| SOURCE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_FX3_STATE_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_ID | character | NOT NULL |
| CUSTOM_ATTRIBUTES | text | NOT NULL |
| FX3_FETCH_TIME | bigint | NOT NULL, DEFAULT |
| FX3_PAYLOAD | text | None |
| FX3_STATE_ID | integer | NOT NULL, DEFAULT |

**Primary Key(s):** FX3_STATE_ID

**Foreign Keys:** None

---

### AO_6FF49D_GR_RESPONSE_GROUP

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_JSON | text | None |
| END_TIMESTAMP | bigint | None |
| ID | integer | NOT NULL |
| JOB_ID | character | NOT NULL |
| NODE_ID | character | NOT NULL |
| START_TIMESTAMP | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_GUARDRAILS_RESPONSE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| GUARDRAILS_RESPONSE | bigint | None |
| GUARDRAILS_RESPONSE_TEXT | text | None |
| GUARDRAILS_RESPONSE_TYPE | character | None |
| ID | integer | NOT NULL |
| JESAT_RESPONSE | text | None |
| JOB_ID | character | NOT NULL |
| QUERY_CPU_LOAD | double | DEFAULT |
| QUERY_DURATION | bigint | DEFAULT |
| QUERY_ID | character | NOT NULL |
| QUERY_PRODUCT_TYPE | character | None |
| QUERY_STATUS | character | None |
| SUCCESS | boolean | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_INCORRECT_EMAIL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| DIRECTORY_ID | bigint | DEFAULT |
| DIRECTORY_NAME | character | None |
| EMAIL_CORRECTION_DATA | text | None |
| EXECUTION_ID | character | None |
| ID | character | NOT NULL |
| LAST_AUTHENTICATED | bigint | DEFAULT |
| NEW_EMAIL | character | None |
| OLD_EMAIL | character | None |
| PREFLIGHT_CHECK_TYPE | character | None |
| TYPE | character | None |
| UPDATED_BY | character | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |
| USER_KEY | character | None |
| USER_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_INST_ANALYSIS_CTRL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ANALYSIS_TYPE | character | NOT NULL |
| COMPLETION_STATUS | character | None |
| END_TIMESTAMP | bigint | None |
| ID | integer | NOT NULL |
| START_TIMESTAMP | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATED_ASSET_MEDIA

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FILE_MEDIA_ID | character | NOT NULL |
| FILE_SERVER_ID | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| MEDIA_CLIENT_ID | character | NOT NULL |
| MIGRATED | boolean | NOT NULL, DEFAULT |
| OBJECT_SCHEMA_KEY | character | None |
| TYPE | character | NOT NULL |
| UPLOAD_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATED_AVATAR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FILE_MEDIA_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| MEDIA_CLIENT_ID | character | NOT NULL |
| MIGRATED | boolean | NOT NULL, DEFAULT |
| SERVER_AVATAR_ID | bigint | NOT NULL, DEFAULT |
| SIZE | character | NOT NULL |
| UPLOAD_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATED_FILE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FILE_MEDIA_ID | character | NOT NULL |
| FILE_SERVER_ID | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| MEDIA_CLIENT_ID | character | NOT NULL |
| MIGRATED | boolean | NOT NULL, DEFAULT |
| UPLOAD_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATION_COMMAND

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMMAND_ID | character | NOT NULL |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| MIGRATION_ID | character | NOT NULL |
| UPDATED_TIMESTAMP | bigint | DEFAULT |
| VERSION | integer | DEFAULT |

**Primary Key(s):** COMMAND_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATION_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APP_OUTCOME_JSON | text | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| DATA_MOVEMENT_ID | character | None |
| IN_PROGRESS_STATUS_JSON | text | None |
| IN_PROGRESS_STATUS_JSON_V2 | text | None |
| MIGRATION_ID | character | NOT NULL |
| NEW_PROTOCOL_JSON | character | None |
| OUTCOME_JSON | text | None |
| OUTCOME_JSON_V2 | text | None |
| PLAN_ID | character | NOT NULL |
| PROTOCOL_JSON | character | None |
| STARTED_BY | character | None |
| START_MIGRATION_CONTEXT_JSON | text | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |
| USER_MIGRATION_END_TIME | bigint | DEFAULT |
| USER_MIGRATION_START_TIME | bigint | DEFAULT |

**Primary Key(s):** MIGRATION_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATION_INCREMENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_ID | character | NOT NULL |
| CUTOFF | bigint | NOT NULL, DEFAULT |
| FINAL | boolean | NOT NULL, DEFAULT |
| ID | character | NOT NULL |
| MIGRATION_ID | character | NOT NULL |
| PLAN_ID | character | NOT NULL |
| PROJECT_ID | bigint | NOT NULL, DEFAULT |
| START_TIME | bigint | NOT NULL, DEFAULT |
| STATUS | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIGRATION_SCOPE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVATION_ID | character | None |
| CLOUD_ID | character | NOT NULL |
| SCOPE_ID | character | None |
| SERVER_URL | character | None |

**Primary Key(s):** CLOUD_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_CHAIN_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | DEFAULT |
| MIGRATION_CHAIN_ID | character | NOT NULL |
| MIGRATION_ID | character | NOT NULL |

**Primary Key(s):** MIGRATION_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_PREFLIGHT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| EXECUTION_ID | character | NOT NULL |
| NODE_ID | character | NOT NULL, DEFAULT |
| PLAN_ID | character | None |
| PLAN_NAME | character | NOT NULL |
| PREFLIGHT_ID | character | NOT NULL |

**Primary Key(s):** PREFLIGHT_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_PREFLIGHT_CHECK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHECK_ID | character | NOT NULL |
| CHECK_TYPE | character | NOT NULL |
| CREATED_AT | bigint | NOT NULL, DEFAULT |
| EXECUTION_ID | character | None |
| PREFLIGHT_ID | character | NOT NULL |
| STATUS | text | NOT NULL |
| UPDATED_AT | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** CHECK_ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_REPORT_STATUS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| REPORT_TYPE | character | NOT NULL |
| STATUS | character | NOT NULL |
| UPDATED_AT | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_STATUS_CACHE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| JSON | text | None |
| MIGRATION_ID | character | None |
| PROJECT_ID | bigint | DEFAULT |
| TASK_TYPE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_MIG_V4_COMMAND_TABLE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMMAND_ID | bigint | DEFAULT |
| COMMAND_JSON | text | None |
| COMMAND_NAME | character | None |
| ID | integer | NOT NULL |
| NODE_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_NODE_INFRASTRUCTURE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CPU_COUNT | integer | DEFAULT |
| ID | integer | NOT NULL |
| LAST_UPDATED | timestamp | NOT NULL |
| NODE_ID | character | NOT NULL |
| OPERATING_SYSTEM | character | None |
| RAM_MB | bigint | NOT NULL, DEFAULT |
| STORAGE_AVAILABLE_MB | bigint | DEFAULT |
| STORAGE_USED_MB | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_NODE_NETWORK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| INFRASTRUCTURE_ID | integer | NOT NULL |
| IN_ERRORS_PERCENT | double | NOT NULL, DEFAULT |
| MAX_SPEED_MBS | bigint | NOT NULL, DEFAULT |
| MTU_BPS | bigint | NOT NULL, DEFAULT |
| NAME | character | NOT NULL |
| NODE_ID | character | NOT NULL |
| OUT_ERRORS_PERCENT | double | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| INFRASTRUCTURE_ID | AO_6FF49D_NODE_INFRASTRUCTURE | ID |

---

### AO_6FF49D_PLAN_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED | timestamp | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| ID | character | NOT NULL |
| JSON | text | None |
| PLAN_NAME | character | NOT NULL |
| UPDATED | timestamp | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_PMRA_FAILED_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CATEGORY | character | NOT NULL |
| DESCRIPTION | character | NOT NULL |
| ENTITYTYPE | character | None |
| ENTITY_NAME | character | NOT NULL |
| ENTITY_TYPE | character | NOT NULL |
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| NEXT_STEPS | character | None |
| PROBLEM_DESCRIPTION | text | None |
| PROBLEM_SUMMARY | character | NOT NULL |
| PROJECT_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_PREFLIGHT_LOCK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| PLAN_ID | character | NOT NULL |

**Primary Key(s):** PLAN_ID

**Foreign Keys:** None

---

### AO_6FF49D_PREMIG_OUTCOME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHECK_ID | integer | NOT NULL, DEFAULT |
| CLOUD_ID | character | None |
| ID | bigint | NOT NULL |
| LAST_EXECUTION_TIME | bigint | DEFAULT |
| PHASE_ID | integer | NOT NULL, DEFAULT |
| PREFLIGHT_CHECK_EXECUTION_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_PROJ_EXPORT_PREFLT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_ITEMS | text | None |
| HARD_REFRESH_TIME | bigint | DEFAULT |
| MRIS | text | None |
| PROJECT_ID | bigint | NOT NULL, DEFAULT |
| SOFT_REFRESH_TIME | bigint | DEFAULT |
| UNSUPPORTED_ENTITIES | text | None |

**Primary Key(s):** PROJECT_ID

**Foreign Keys:** None

---

### AO_6FF49D_PUBLIC_PLAN_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| JOB_ID | character | NOT NULL |
| MIGRATION_ID | character | None |
| PLAN_ID | character | NOT NULL |
| PREFLIGHT_EXECUTION_ID | character | None |
| TASK_COMPLETION_TIME | bigint | DEFAULT |
| TASK_ID | character | None |
| TASK_STATUS | character | None |
| TASK_TYPE | character | None |

**Primary Key(s):** JOB_ID

**Foreign Keys:** None

---

### AO_6FF49D_SCOPED_USER_CACHE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| GROUP_NAMES | text | None |
| LAST_HARD_REFRESH_TIMESTAMP | timestamp | None |
| LAST_SOFT_REFRESH_TIMESTAMP | timestamp | None |
| PROJECT_ID | bigint | NOT NULL, DEFAULT |
| USER_KEYS | text | None |

**Primary Key(s):** PROJECT_ID

**Foreign Keys:** None

---

### AO_6FF49D_SHADOW_CLOUD_SITE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_ID | character | None |
| ID | bigint | NOT NULL |
| PLAN_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_SHADOW_JOB_DETAILS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| JOB_ID | character | None |
| PLAN_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_SKIP_PREFLIGHT_RES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHECK_TYPE | character | NOT NULL |
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| LAST_EXECUTION_TIME | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_SKIP_PREFLT_RESULT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHECK_ID | integer | NOT NULL, DEFAULT |
| EXECUTION_ID | character | NOT NULL |
| ID | bigint | NOT NULL |
| LAST_EXECUTION_TIME | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_TOMBSTONE_ACCOUNT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AAID | character | None |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** USER_KEY

**Foreign Keys:** None

---

### AO_6FF49D_UNSUPPORTED_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COUNT | integer | DEFAULT |
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| IMPACTED_ENTITY_ID | character | None |
| IMPACTED_ENTITY_NAME | character | None |
| PROBLEM_ENTITY_NAME | character | None |
| PROBLEM_TYPE_AND_DETAILS | character | None |
| PROJECT_KEY | character | None |
| REFERENCED_BY | text | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_USERBASE_SCAN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | DEFAULT |
| DUPLICATED_CUSTOMERS_COUNT | bigint | DEFAULT |
| DUPLICATED_USERS_COUNT | bigint | DEFAULT |
| FINISHED_AT | bigint | DEFAULT |
| ID | character | NOT NULL |
| INVALID_CUSTOMERS_COUNT | bigint | DEFAULT |
| INVALID_USERS_COUNT | bigint | DEFAULT |
| STARTED_AT | bigint | DEFAULT |
| STATUS | character | None |
| UPDATED_BY | character | None |
| UPDATED_TIMESTAMP | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_USERS_GROUPS_EXTRACT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EXECUTION_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| NAME | character | NOT NULL |
| PRESERVE_MEMBERSHIP | boolean | None |
| REFERENCED_BY | text | None |
| REFERENCED_BY_GROUPS | text | None |
| TYPE | character | NOT NULL |
| USER_EMAIL | character | None |
| USER_KEY | character | None |
| VERSION | integer | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_USER_EMAIL_EVENT_LOG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLOUD_ID | character | NOT NULL |
| EMAIL | character | NOT NULL |
| EVENT_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_6FF49D_VIRTUAL_ATTACHMENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| VIRTUAL_ATTACHMENT_ID | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_723324_CLIENT_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHORIZATION_ENDPOINT | character | None |
| CLIENT_CERTIFICATE | text | None |
| CLIENT_ID | character | NOT NULL |
| CLIENT_SECRET | character | None |
| CUSTOM_PARAMS | text | None |
| DESCRIPTION | character | None |
| GRANT_TYPE | character | DEFAULT |
| ID | character | NOT NULL |
| NAME | character | NOT NULL |
| SCOPES | text | NOT NULL |
| TOKEN_ENDPOINT | character | NOT NULL |
| TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_723324_CLIENT_TOKEN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_TOKEN | text | NOT NULL |
| ACCESS_TOKEN_EXPIRATION | bigint | NOT NULL, DEFAULT |
| CONFIG_ID | character | NOT NULL |
| EXTERNAL_ID | character | None |
| ID | character | NOT NULL |
| LAST_REFRESHED | bigint | None |
| LAST_STATUS_UPDATED | bigint | NOT NULL |
| REFRESH_COUNT | integer | DEFAULT |
| REFRESH_TOKEN | text | None |
| REFRESH_TOKEN_EXPIRATION | bigint | None |
| STATUS | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_733371_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | None |
| ACTION_ID | character | None |
| CREATED | timestamp | NOT NULL |
| EVENT_BUNDLE_ID | character | None |
| EVENT_TYPE | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_733371_EVENT_PARAMETER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| NAME | character | NOT NULL |
| VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| EVENT_ID | AO_733371_EVENT | ID |

---

### AO_733371_EVENT_RECIPIENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONSUMER_NAME | character | NOT NULL |
| CREATED | timestamp | NOT NULL |
| EVENT_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| SEND_DATE | timestamp | None |
| STATUS | character | NOT NULL |
| UPDATED | timestamp | None |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| EVENT_ID | AO_733371_EVENT | ID |

---

### AO_7A2604_CALENDAR

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONTEXT | text | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| TIMEZONE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_7A2604_HOLIDAY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CALENDAR_ID | integer | None |
| DATE_STRING | character | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| RECURRING | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| CALENDAR_ID | AO_7A2604_CALENDAR | ID |

---

### AO_7A2604_WORKINGTIME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CALENDAR_ID | integer | None |
| DAY | character | None |
| END_TIME | bigint | None |
| ID | integer | NOT NULL |
| START_TIME | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| CALENDAR_ID | AO_7A2604_CALENDAR | ID |

---

### AO_81F455_PERSONAL_TOKEN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | timestamp | NOT NULL |
| EXPIRING_AT | timestamp | NOT NULL |
| HASHED_TOKEN | character | NOT NULL |
| ID | bigint | NOT NULL |
| LAST_ACCESSED_AT | timestamp | None |
| NAME | character | NOT NULL |
| NOTIFICATION_STATE | character | NOT NULL |
| TOKEN_ID | character | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_82B313_ABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMBINED_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| PERSON_ID | bigint | None |
| SKILL_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PERSON_ID | AO_82B313_PERSON | ID |
| SKILL_ID | AO_82B313_SKILL | ID |

---

### AO_82B313_ABSENCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END | bigint | None |
| ID | bigint | NOT NULL |
| PERSON_ID | bigint | None |
| START | bigint | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PERSON_ID | AO_82B313_PERSON | ID |

---

### AO_82B313_AVAILABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| RESOURCE_ID | bigint | None |
| START | bigint | NOT NULL |
| TITLE | character | None |
| WEEKLY_HOURS | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RESOURCE_ID | AO_82B313_RESOURCE | ID |

---

### AO_82B313_INIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_82B313_PERSON

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AVATAR_URL | character | None |
| END | bigint | None |
| ID | bigint | NOT NULL |
| JIRA_USER_ID | character | None |
| START | bigint | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_82B313_RESOURCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| JOIN_DATE | bigint | None |
| LEAVE_DATE | bigint | None |
| PERSON_ID | bigint | None |
| TEAM_ID | bigint | None |
| WEEKLY_HOURS | double | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PERSON_ID | AO_82B313_PERSON | ID |
| TEAM_ID | AO_82B313_TEAM | ID |

---

### AO_82B313_SKILL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| SHAREABLE | boolean | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_82B313_TEAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AVATAR_URL | character | None |
| ID | bigint | NOT NULL |
| SHAREABLE | boolean | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8752F1_DATA_PIPELINE_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | NOT NULL |
| VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8752F1_DATA_PIPELINE_EOO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ENTITY_IDENTIFIER | character | NOT NULL |
| ENTITY_TYPE | character | NOT NULL |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8752F1_DATA_PIPELINE_JOB

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED | bigint | NOT NULL |
| ERRORS | text | None |
| EXPORTED_ENTITIES | integer | None |
| EXPORT_FORCED | boolean | None |
| EXPORT_FROM | bigint | NOT NULL |
| EXPORT_PATH | text | None |
| ID | integer | NOT NULL |
| METADATA | character | None |
| OPTED_OUT_ENTITY_IDENTIFIERS | text | None |
| OPTED_OUT_FILE_SCHEMAS | text | None |
| ROOT_EXPORT_PATH | character | None |
| SCHEMA_VERSION | integer | NOT NULL, DEFAULT |
| STATUS | character | NOT NULL |
| UPDATED | bigint | NOT NULL |
| WARNINGS | text | None |
| WRITTEN_ROWS | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_88263F_HEALTH_CHECK_STATUS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPLICATION_NAME | character | None |
| COMPLETE_KEY | character | None |
| DESCRIPTION | character | None |
| FAILED_DATE | timestamp | None |
| FAILURE_REASON | character | None |
| ID | integer | NOT NULL |
| IS_HEALTHY | boolean | None |
| IS_RESOLVED | boolean | None |
| RESOLVED_DATE | timestamp | None |
| SEVERITY | character | None |
| STATUS_NAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_88263F_PROPERTIES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PROPERTY_NAME | character | None |
| PROPERTY_VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_88263F_READ_NOTIFICATIONS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| IS_SNOOZED | boolean | None |
| NOTIFICATION_ID | integer | None |
| SNOOZE_COUNT | integer | None |
| SNOOZE_DATE | timestamp | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8AE288_DASHBOARD_VIEWS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DASHBOARD_ID | bigint | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| LAST_VIEWED | bigint | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8AE288_PAGE_VIEW_USAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | text | None |
| DESCRIPTION_TRANSLATION_KEY | character | None |
| ID | bigint | NOT NULL |
| NAME | character | None |
| PLUGIN_KEY | character | NOT NULL |
| SERVLET_KEY | character | NOT NULL |
| SERVLET_TRANSLATION_KEY | character | None |
| URL_PATTERN | character | NOT NULL |
| WEBWORK | boolean | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8AE288_USER_PAGE_VIEW

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LAST_VIEWED | bigint | NOT NULL, DEFAULT |
| PAGE_VIEW_ID | bigint | NOT NULL |
| TOTAL_USAGES | bigint | NOT NULL, DEFAULT |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PAGE_VIEW_ID | AO_8AE288_PAGE_VIEW_USAGE | ID |

---

### AO_8AE288_USER_REST_USAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LAST_USED | bigint | NOT NULL, DEFAULT |
| PLUGIN_KEY | character | NOT NULL |
| TOTAL_USAGES | bigint | NOT NULL, DEFAULT |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_8AE288_USER_WEB_PANEL_USAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LAST_CLICKED | bigint | DEFAULT |
| LAST_VIEWED | bigint | NOT NULL, DEFAULT |
| TOTAL_CLICKS | bigint | NOT NULL, DEFAULT |
| TOTAL_VIEWS | bigint | NOT NULL, DEFAULT |
| USER_KEY | character | NOT NULL |
| WEB_PANEL_INFO_ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| WEB_PANEL_INFO_ID | AO_8AE288_WEB_PANEL_INFO | ID |

---

### AO_8AE288_WEB_PANEL_INFO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LOCATION | character | NOT NULL |
| NAME | character | None |
| PLUGIN_KEY | character | NOT NULL |
| RESOURCE_LOCATION | character | NOT NULL |
| TRANSLATION_KEY | character | None |
| WEB_PANEL_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_97EDAB_USERINVITATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPLICATION_KEYS | character | None |
| EMAIL_ADDRESS | character | None |
| EXPIRY | timestamp | None |
| ID | integer | NOT NULL |
| REDEEMED | boolean | None |
| SENDER_USERNAME | character | None |
| TOKEN | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_9B2E3B_EXEC_RULE_MSG_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| RULE_EXECUTION_ID | bigint | None |
| RULE_MESSAGE_KEY | character | None |
| RULE_MESSAGE_VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_EXECUTION_ID | AO_9B2E3B_RULE_EXECUTION | ID |

---

### AO_9B2E3B_IF_CONDITION_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| IF_THEN_ID | bigint | None |
| MODULE_KEY | character | None |
| ORDINAL | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_THEN_ID | AO_9B2E3B_IF_THEN | ID |

---

### AO_9B2E3B_IF_COND_CONF_DATA

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_DATA_KEY | character | None |
| CONFIG_DATA_VALUE | text | None |
| ID | bigint | NOT NULL |
| IF_CONDITION_CONFIG_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_CONDITION_CONFIG_ID | AO_9B2E3B_IF_CONDITION_CONFIG | ID |

---

### AO_9B2E3B_IF_COND_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| IF_CONDITION_CONFIG_ID | bigint | None |
| IF_EXECUTION_ID | bigint | None |
| MESSAGE | text | None |
| OUTCOME | character | None |
| START_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_EXECUTION_ID | AO_9B2E3B_IF_EXECUTION | ID |

---

### AO_9B2E3B_IF_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| IF_THEN_EXECUTION_ID | bigint | None |
| MESSAGE | text | None |
| OUTCOME | character | None |
| START_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_THEN_EXECUTION_ID | AO_9B2E3B_IF_THEN_EXECUTION | ID |

---

### AO_9B2E3B_IF_THEN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| ORDINAL | integer | None |
| RULE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_ID | AO_9B2E3B_RULE | ID |

---

### AO_9B2E3B_IF_THEN_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| IF_THEN_ID | bigint | None |
| MESSAGE | text | None |
| OUTCOME | character | None |
| RULE_EXECUTION_ID | bigint | None |
| START_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_EXECUTION_ID | AO_9B2E3B_RULE_EXECUTION | ID |

---

### AO_9B2E3B_PROJECT_USER_CONTEXT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PROJECT_ID | bigint | None |
| STRATEGY | character | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_9B2E3B_RSETREV_PROJ_CONTEXT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PROJECT_ID | bigint | None |
| RULESET_REVISION_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULESET_REVISION_ID | AO_9B2E3B_RULESET_REVISION | ID |

---

### AO_9B2E3B_RSETREV_USER_CONTEXT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| RULESET_REVISION_ID | bigint | None |
| STRATEGY | character | None |
| USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULESET_REVISION_ID | AO_9B2E3B_RULESET_REVISION | ID |

---

### AO_9B2E3B_RULE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ENABLED | boolean | None |
| ID | bigint | NOT NULL |
| ORDINAL | integer | None |
| RULESET_REVISION_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULESET_REVISION_ID | AO_9B2E3B_RULESET_REVISION | ID |

---

### AO_9B2E3B_RULESET

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVE_REVISION_ID | bigint | None |
| ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_9B2E3B_RULESET_REVISION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP_MILLIS | bigint | None |
| DESCRIPTION | character | None |
| ID | bigint | NOT NULL |
| IS_SYSTEM_RULE_SET | boolean | None |
| NAME | character | None |
| RULE_SET_ID | bigint | None |
| TRIGGER_FROM_OTHER_RULES | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_SET_ID | AO_9B2E3B_RULESET | ID |

---

### AO_9B2E3B_RULE_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EXECUTOR_USER_KEY | character | None |
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| MESSAGE | text | None |
| OUTCOME | character | None |
| RULE_ID | bigint | None |
| START_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_9B2E3B_THEN_ACTION_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| IF_THEN_ID | bigint | None |
| MODULE_KEY | character | None |
| ORDINAL | integer | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_THEN_ID | AO_9B2E3B_IF_THEN | ID |

---

### AO_9B2E3B_THEN_ACT_CONF_DATA

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_DATA_KEY | character | None |
| CONFIG_DATA_VALUE | text | None |
| ID | bigint | NOT NULL |
| THEN_ACTION_CONFIG_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| THEN_ACTION_CONFIG_ID | AO_9B2E3B_THEN_ACTION_CONFIG | ID |

---

### AO_9B2E3B_THEN_ACT_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| MESSAGE | text | None |
| OUTCOME | character | None |
| START_TIME_MILLIS | bigint | None |
| THEN_ACTION_CONFIG_ID | bigint | None |
| THEN_EXECUTION_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| THEN_EXECUTION_ID | AO_9B2E3B_THEN_EXECUTION | ID |

---

### AO_9B2E3B_THEN_EXECUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FINISH_TIME_MILLIS | bigint | None |
| ID | bigint | NOT NULL |
| IF_THEN_EXECUTION_ID | bigint | None |
| MESSAGE | text | None |
| OUTCOME | character | None |
| START_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| IF_THEN_EXECUTION_ID | AO_9B2E3B_IF_THEN_EXECUTION | ID |

---

### AO_9B2E3B_WHEN_HANDLER_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| MODULE_KEY | character | None |
| ORDINAL | integer | None |
| RULE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| RULE_ID | AO_9B2E3B_RULE | ID |

---

### AO_9B2E3B_WHEN_HAND_CONF_DATA

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONFIG_DATA_KEY | character | None |
| CONFIG_DATA_VALUE | text | None |
| ID | bigint | NOT NULL |
| WHEN_HANDLER_CONFIG_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| WHEN_HANDLER_CONFIG_ID | AO_9B2E3B_WHEN_HANDLER_CONFIG | ID |

---

### AO_A0B856_DAILY_COUNTS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DAY_SINCE_EPOCH | bigint | NOT NULL, DEFAULT |
| ERRORS | integer | NOT NULL, DEFAULT |
| EVENT_ID | character | NOT NULL |
| FAILURES | integer | NOT NULL, DEFAULT |
| ID | character | NOT NULL |
| SUCCESSES | integer | NOT NULL, DEFAULT |
| WEBHOOK_ID | integer | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A0B856_HIST_INVOCATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ERROR_CONTENT | text | None |
| EVENT_ID | character | NOT NULL |
| FINISH | bigint | NOT NULL, DEFAULT |
| ID | character | NOT NULL |
| OUTCOME | character | NOT NULL |
| REQUEST_BODY | text | None |
| REQUEST_HEADERS | text | None |
| REQUEST_ID | character | NOT NULL |
| REQUEST_METHOD | character | NOT NULL |
| REQUEST_URL | character | NOT NULL |
| RESPONSE_BODY | text | None |
| RESPONSE_HEADERS | text | None |
| RESULT_DESCRIPTION | character | NOT NULL |
| START | bigint | NOT NULL, DEFAULT |
| STATUS_CODE | integer | None |
| WEBHOOK_ID | integer | NOT NULL, DEFAULT |
| EVENT_SCOPE_TYPE | character | NOT NULL |
| EVENT_SCOPE_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A0B856_WEBHOOK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVE | boolean | None |
| CREATED | timestamp | NOT NULL |
| ID | integer | NOT NULL |
| NAME | character | NOT NULL |
| SCOPE_ID | character | None |
| SCOPE_TYPE | character | NOT NULL |
| UPDATED | timestamp | NOT NULL |
| URL | text | NOT NULL |
| SSL_VERIFICATION_REQUIRED | boolean | NOT NULL, DEFAULT |
| USERNAME | character | None |
| PASSWORD | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A0B856_WEBHOOK_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | NOT NULL |
| VALUE | character | NOT NULL |
| WEBHOOKID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A0B856_WEBHOOK_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| WEBHOOKID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A0B856_WEB_HOOK_LISTENER_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | text | None |
| ENABLED | boolean | None |
| EVENTS | text | None |
| EXCLUDE_BODY | boolean | None |
| FILTERS | text | None |
| ID | integer | NOT NULL |
| LAST_UPDATED | timestamp | NOT NULL |
| LAST_UPDATED_USER | character | None |
| NAME | text | NOT NULL |
| PARAMETERS | text | None |
| REGISTRATION_METHOD | character | NOT NULL |
| URL | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A415DF_AOABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ABILITY_VALUE | double | None |
| AOPERSON_ID | integer | None |
| ID_OTHER | integer | NOT NULL |
| TARGET_ID | integer | None |
| TARGET_TYPE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPERSON_ID | AO_A415DF_AOPERSON | ID_OTHER |

---

### AO_A415DF_AOABSENCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPERSON_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| END_DATE | bigint | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| START_DATE | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPERSON_ID | AO_A415DF_AOPERSON | ID_OTHER |

---

### AO_A415DF_AOAVAILABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AORESOURCE_ID | integer | None |
| AVAILABILITY | double | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| END_DATE | bigint | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| START_DATE | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AORESOURCE_ID | AO_A415DF_AORESOURCE | ID_OTHER |

---

### AO_A415DF_AOCONFIGURATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID_OTHER | integer | NOT NULL |
| INITIALIZED | boolean | None |
| INIT_STATE | integer | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AOCUSTOM_WORDING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID_OTHER | integer | NOT NULL |
| WORD_KEY | character | None |
| WORD_VALUE | character | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AODEPENDENCY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DEPENDEE | integer | None |
| DEPENDENT | integer | None |
| ID_OTHER | integer | NOT NULL |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AODOOR_STOP

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_A415DF_AOESTIMATE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOWORK_ITEM_ID | integer | None |
| CURRENCY | integer | None |
| ESTIMATE | double | None |
| ID_OTHER | integer | NOT NULL |
| ORIGINAL | boolean | None |
| REPLANNING | boolean | None |
| TARGET_ID | integer | None |
| TARGET_TYPE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOWORK_ITEM_ID | AO_A415DF_AOWORK_ITEM | ID_OTHER |

---

### AO_A415DF_AOEXTENSION_LINK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOEXTENDABLE_ID | integer | None |
| AOEXTENDABLE_TYPE | character | None |
| EXTENSION_KEY | character | None |
| EXTENSION_LINK | character | None |
| ID_OTHER | integer | NOT NULL |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AONON_WORKING_DAYS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| END_DATE | bigint | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| START_DATE | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOPERMISSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HOLDER_ID | character | None |
| HOLDER_TYPE | character | None |
| ID_OTHER | integer | NOT NULL |
| PERMISSION | integer | None |
| TARGET_ID | character | None |
| TARGET_TYPE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AOPERSON

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOEXTERNAL_ID | character | None |
| AOPLAN_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| EXTERNAL | boolean | None |
| ID_OTHER | integer | NOT NULL |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOPLAN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AODATE | bigint | None |
| AOREPLANNING_DATE | bigint | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| IN_REPLANNING | boolean | None |
| IN_STREAM_MODE | boolean | None |
| PLAN_VERSION | bigint | None |
| REPLANNING_VERSION | bigint | None |
| SCHEDULING_VERSION | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AOPLAN_CONFIGURATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| AOPROGRESS_TRACKER_TYPE | character | None |
| AOWEEKDAY_CONFIG | integer | None |
| BACKLOG_RECORD_LIMIT | integer | None |
| DEFAULT_EPIC_ESTIMATE | double | DEFAULT |
| DEFAULT_STORY_ESTIMATE | double | DEFAULT |
| EPIC_SYNC_MODE | character | None |
| GLOBAL_DEFAULT_VELOCITY | double | DEFAULT |
| GLOBAL_SPRINT_LENGTH | integer | None |
| HAS_SPRINT_CONSTRAINT | boolean | None |
| HEURISTIC_THRESHOLD | integer | None |
| HOURS_PER_DAY | double | None |
| ID_OTHER | integer | NOT NULL |
| IMPORT_LIMIT | integer | None |
| INITIATIVE_SYNC_MODE | character | None |
| LINKING_MODE | character | None |
| MAX_RESOURCES_PER_STORY | bigint | None |
| MIN_LOAD_UNSTR_EPICS | bigint | None |
| PLANNING_UNIT | character | None |
| PROG_CMPLT_IF_RSLVD | boolean | None |
| PROG_DSPL_UNEST_RTIO | boolean | None |
| PROG_FIELD_NAME | character | None |
| PROG_STRY_SUB_TASK_MODE | character | None |
| SPRINT_EXCEEDED_WARN | boolean | None |
| STORY_SYNC_MODE | character | None |
| STRICT_STAGE_DIVISION | boolean | None |
| SUGGEST_REPL_ESTIMATES | boolean | None |
| SYNC_DESCRIPTION | boolean | None |
| SYNC_EPICS | boolean | None |
| SYNC_ESTIMATES | boolean | None |
| SYNC_INITIATIVES | boolean | None |
| SYNC_START_ENABLED | boolean | None |
| SYNC_STORIES | boolean | None |
| SYNC_SUMMARY | boolean | None |
| TEMPLATE_TYPE | character | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOPRESENCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPERSON_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| END_DATE | bigint | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| START_DATE | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPERSON_ID | AO_A415DF_AOPERSON | ID_OTHER |

---

### AO_A415DF_AORELEASE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AODELTA_START_DATE | bigint | None |
| AOFIXED_END_DATE | bigint | None |
| AOFIXED_START_DATE | bigint | None |
| AOPLAN_ID | integer | None |
| AOSTREAM_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| IS_LATER_RELEASE | boolean | None |
| ORDER_RANGE_IDENTIFIER | character | None |
| PRIMARY_VERSION | character | None |
| SORT_ORDER | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |
| AOSTREAM_ID | AO_A415DF_AOSTREAM | ID_OTHER |

---

### AO_A415DF_AOREPLANNING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID_OTHER | integer | NOT NULL |
| TARGET_ID | character | None |
| TARGET_TYPE | character | None |
| WORK_ITEM_ID | integer | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| WORK_ITEM_ID | AO_A415DF_AOWORK_ITEM | ID_OTHER |

---

### AO_A415DF_AORESOURCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPERSON_ID | integer | None |
| AOTEAM_ID | integer | None |
| AVAILABILITY | double | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPERSON_ID | AO_A415DF_AOPERSON | ID_OTHER |
| AOTEAM_ID | AO_A415DF_AOTEAM | ID_OTHER |

---

### AO_A415DF_AOSKILL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOSTAGE_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| PERCENTAGE | double | None |
| SORT_ORDER | bigint | None |
| STAGE_ID | character | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOSTAGE_ID | AO_A415DF_AOSTAGE | ID_OTHER |

---

### AO_A415DF_AOSOLUTION_STORE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | NOT NULL |
| ID_OTHER | integer | NOT NULL |
| SOLUTION | text | NOT NULL |
| SOLUTION_VERSION | bigint | NOT NULL |

**Primary Key(s):** ID_OTHER

**Foreign Keys:** None

---

### AO_A415DF_AOSPRINT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOTEAM_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| END_DATE | bigint | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SORT_ORDER | bigint | None |
| START_DATE | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOTEAM_ID | AO_A415DF_AOTEAM | ID_OTHER |

---

### AO_A415DF_AOSTAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| COLOR | character | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| PERCENTAGE | double | None |
| SORT_ORDER | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOSTREAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| COLOR | character | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| DYNAMIC_START_STREAM | boolean | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| SHORT_NAME | character | None |
| SORT_ORDER | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOSTREAM_TO_TEAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOSTREAM_ID | integer | None |
| AOTEAM_ID | integer | None |
| ID_OTHER | integer | NOT NULL |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOSTREAM_ID | AO_A415DF_AOSTREAM | ID_OTHER |
| AOTEAM_ID | AO_A415DF_AOTEAM | ID_OTHER |

---

### AO_A415DF_AOTEAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| AUTO_ADJUST_TO_ABSENCES | boolean | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| INCREMENTAL_ADJUSTMENT | double | None |
| ITERATION_START_TYPE | character | None |
| ORDER_RANGE_IDENTIFIER | character | None |
| PLANNING_MODE | character | None |
| SORT_ORDER | bigint | None |
| TITLE | character | None |
| VELOCITY | double | None |
| VERSION | bigint | None |
| WEEKS_PER_SPRINT | integer | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOTHEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOPLAN_ID | integer | None |
| COLOR | character | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| PERCENTAGE | double | None |
| SORT_ORDER | bigint | None |
| TITLE | character | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |

---

### AO_A415DF_AOWORK_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AOBUSINESS_VALUE | double | None |
| AOEARLIEST_START | bigint | None |
| AOPARENT_ID | integer | None |
| AOPLAN_ID | integer | None |
| AORELEASE_ID | integer | None |
| AOSPRINT_ID | integer | None |
| AOSTREAM_ID | integer | None |
| AOTARGET_END | bigint | None |
| AOTARGET_START | bigint | None |
| AOTEAM_ID | integer | None |
| AOTHEME_ID | integer | None |
| DESCRIPTION | character | None |
| DETAILS | text | None |
| EARLIEST_START | bigint | None |
| HAS_ORIGINAL_ESTIMATES | boolean | None |
| ID_OTHER | integer | NOT NULL |
| ORDER_RANGE_IDENTIFIER | character | None |
| PARENT_ID | character | None |
| REPLANNING_STATUS | integer | None |
| SORT_ORDER | bigint | None |
| STATUS | integer | None |
| TITLE | character | None |
| TYPE | integer | None |
| VERSION | bigint | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AOPARENT_ID | AO_A415DF_AOWORK_ITEM | ID_OTHER |
| AOPLAN_ID | AO_A415DF_AOPLAN | ID_OTHER |
| AORELEASE_ID | AO_A415DF_AORELEASE | ID_OTHER |
| AOSPRINT_ID | AO_A415DF_AOSPRINT | ID_OTHER |
| AOSTREAM_ID | AO_A415DF_AOSTREAM | ID_OTHER |
| AOTEAM_ID | AO_A415DF_AOTEAM | ID_OTHER |
| AOTHEME_ID | AO_A415DF_AOTHEME | ID_OTHER |

---

### AO_A415DF_AOWORK_ITEM_TO_RES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AORESOURCE_ID | integer | None |
| AOWORK_ITEM_ID | integer | None |
| ID_OTHER | integer | NOT NULL |
| REPLANNING | boolean | None |

**Primary Key(s):** ID_OTHER

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| AORESOURCE_ID | AO_A415DF_AORESOURCE | ID_OTHER |
| AOWORK_ITEM_ID | AO_A415DF_AOWORK_ITEM | ID_OTHER |

---

### AO_A44657_HEALTH_CHECK_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_AC3877_RL_USER_COUNTER

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| INTERVAL_START | timestamp | NOT NULL |
| NODE_ID | character | NOT NULL |
| REJECT_COUNT | bigint | NOT NULL, DEFAULT |
| USER_ID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_AC3877_SETTINGS_VERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| TYPE | character | NOT NULL |
| VERSION | bigint | NOT NULL |

**Primary Key(s):** TYPE

**Foreign Keys:** None

---

### AO_AC3877_SYSTEM_RL_SETTINGS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CAPACITY | integer | NOT NULL, DEFAULT |
| CLEAN_JOB_DURATION | character | NOT NULL |
| FILL_RATE | integer | NOT NULL, DEFAULT |
| FLUSH_JOB_DURATION | character | NOT NULL |
| INTERVAL_FREQUENCY | integer | NOT NULL, DEFAULT |
| INTERVAL_TIME_UNIT | character | NOT NULL |
| MODE | character | NOT NULL |
| NAME | character | NOT NULL |
| REAPER_JOB_DURATION | character | NOT NULL |
| RETENTION_PERIOD_DURATION | character | NOT NULL |
| SETTINGS_RELOAD_JOB_DURATION | character | NOT NULL |

**Primary Key(s):** NAME

**Foreign Keys:** None

---

### AO_AC3877_USER_RL_SETTINGS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CAPACITY | integer | NOT NULL, DEFAULT |
| FILL_RATE | integer | NOT NULL, DEFAULT |
| INTERVAL_FREQUENCY | integer | NOT NULL, DEFAULT |
| INTERVAL_TIME_UNIT | character | NOT NULL |
| USER_ID | character | NOT NULL |
| WHITELISTED | boolean | NOT NULL |

**Primary Key(s):** USER_ID

**Foreign Keys:** None

---

### AO_B9A0F0_APPLIED_TEMPLATE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PROJECT_ID | bigint | DEFAULT |
| PROJECT_TEMPLATE_MODULE_KEY | character | None |
| PROJECT_TEMPLATE_WEB_ITEM_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_C16815_ALERT_AO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_DATE | bigint | DEFAULT |
| DETAILS_JSON | text | None |
| ID | bigint | NOT NULL |
| ISSUE_COMPONENT_ID | character | None |
| ISSUE_ID | character | None |
| ISSUE_SEVERITY | integer | DEFAULT |
| NODE_NAME | character | None |
| TRIGGER_MODULE | character | None |
| TRIGGER_PLUGIN_KEY | character | None |
| TRIGGER_PLUGIN_KEY_VERSION | character | None |
| TRIGGER_PLUGIN_VERSION | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_C77861_AUDIT_ACTION_CACHE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | NOT NULL |
| ACTION_T_KEY | character | None |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_C77861_AUDIT_CATEGORY_CACHE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CATEGORY | character | NOT NULL |
| CATEGORY_T_KEY | character | None |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_C77861_AUDIT_DENY_LISTED

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | None |
| ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_C77861_AUDIT_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION | character | NOT NULL |
| ACTION_T_KEY | character | None |
| AREA | character | NOT NULL |
| ATTRIBUTES | text | None |
| CATEGORY | character | None |
| CATEGORY_T_KEY | character | None |
| CHANGE_VALUES | text | None |
| ENTITY_TIMESTAMP | bigint | NOT NULL |
| ID | bigint | NOT NULL |
| LEVEL | character | NOT NULL |
| METHOD | character | None |
| NODE | character | None |
| PRIMARY_RESOURCE_ID | character | None |
| PRIMARY_RESOURCE_TYPE | character | None |
| RESOURCES | text | None |
| RESOURCE_ID_3 | character | None |
| RESOURCE_ID_4 | character | None |
| RESOURCE_ID_5 | character | None |
| RESOURCE_TYPE_3 | character | None |
| RESOURCE_TYPE_4 | character | None |
| RESOURCE_TYPE_5 | character | None |
| SEARCH_STRING | text | None |
| SECONDARY_RESOURCE_ID | character | None |
| SECONDARY_RESOURCE_TYPE | character | None |
| SOURCE | character | None |
| SYSTEM_INFO | character | None |
| USER_ID | character | None |
| USER_NAME | character | None |
| USER_TYPE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_CC7F60_SEC_MON_ALERT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ALERT_STATUS | integer | DEFAULT |
| ALERT_TIMESTAMP | bigint | DEFAULT |
| ALERT_TYPE | character | None |
| EMAIL_STATUS | character | NOT NULL |
| ID | bigint | NOT NULL |
| QUEUED_TIMESTAMP | bigint | None |
| UUID | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_CC7F60_SEC_MON_SCHEDULE_JOB

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| JOB_KEY | character | None |
| LAST_SUCCESSFUL_RUN | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_CC7F60_SEC_MON_THREAT_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTION_T_KEY | character | NOT NULL |
| ALERT_ID | bigint | None |
| CREATED_TIME | bigint | NOT NULL, DEFAULT |
| EVENT_SOURCE | character | None |
| EXTRA_ATTRIBUTE_T_KEY_1 | character | None |
| EXTRA_ATTRIBUTE_T_KEY_2 | character | None |
| EXTRA_ATTRIBUTE_T_KEY_3 | character | None |
| EXTRA_ATTRIBUTE_VALUE_COLUMN_1 | text | None |
| EXTRA_ATTRIBUTE_VALUE_COLUMN_2 | text | None |
| EXTRA_ATTRIBUTE_VALUE_COLUMN_3 | text | None |
| ID | bigint | NOT NULL |
| INSTANCE_BASE_URL | character | None |
| NODE | character | None |
| SOURCE_IP | character | None |
| TRIGGERING_USER_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| ALERT_ID | AO_CC7F60_SEC_MON_ALERT | ID |

---

### AO_CFF990_AOTRANSITION_FAILURE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ERROR_MESSAGES | text | None |
| FAILURE_TIME | timestamp | None |
| ID | integer | NOT NULL |
| ISSUE_ID | bigint | DEFAULT |
| LOG_REFERRAL_HASH | character | None |
| TRANSITION_ID | bigint | DEFAULT |
| TRIGGER_ID | bigint | DEFAULT |
| USER_KEY | character | None |
| WORKFLOW_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_ASSIGNMENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| INTERVAL_END | bigint | NOT NULL |
| INTERVAL_START | bigint | NOT NULL |
| ISSUE | character | NOT NULL |
| PLAN | bigint | NOT NULL |
| PROJECT | character | NOT NULL |
| RESOURCE | character | NOT NULL |
| SKILL | character | NOT NULL |
| SOLUTION_ID | bigint | None |
| SPRINT_INDEX | integer | NOT NULL |
| STAGE | character | NOT NULL |
| TEAM | character | NOT NULL |
| VERSION | character | NOT NULL |
| WORKLOAD | double | NOT NULL |
| SCENARIO | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SOLUTION_ID | AO_D9132D_SOLUTION | ID |

---

### AO_D9132D_ASSIGNMENT_EXT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| INTERVAL_END | bigint | NOT NULL |
| INTERVAL_START | bigint | NOT NULL |
| ISSUE | character | NOT NULL |
| PLAN | bigint | None |
| PROJECT | character | NOT NULL |
| RESOURCE | character | None |
| SCENARIO | bigint | None |
| SKILL | character | None |
| SOLUTION_ID | bigint | None |
| SPRINT_INDEX | integer | None |
| STAGE | character | None |
| TEAM | character | None |
| VERSION | character | None |
| WORKLOAD | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SOLUTION_ID | AO_D9132D_SOLUTION | ID |

---

### AO_D9132D_CONFIGURATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HIERARCHY_ISSUE_LIMIT | bigint | None |
| ID | bigint | NOT NULL |
| ISSUE_LIMIT | bigint | None |
| PROJECT_LIMIT | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_DEP_ISSUE_LINK_TYPES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LINK_ID | bigint | NOT NULL, DEFAULT |
| OUTWARD | boolean | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_DISTRIBUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| SCENARIO_ISSUE_ID | bigint | None |
| SKILL_ITEM_KEY | character | None |
| WEIGHT | double | None |
| ORIGINAL | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ISSUE_ID | AO_D9132D_SCENARIO_ISSUES | ID |

---

### AO_D9132D_EXCLUDED_ISSUE_TYPES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| ISSUE_TYPE | bigint | None |
| PLAN_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_EXCLUDED_STATUSCATS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| STATUS_CATEGORY | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_EXCLUDED_STATUSES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| STATUS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_EXCLUDED_VERSIONS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| VERSION | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_GENERICREPORT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HASH | character | NOT NULL |
| ID | bigint | NOT NULL |
| PARAMS | text | None |
| PARAMS_HASH | integer | None |
| TYPE | character | NOT NULL |
| TYPE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_HIERARCHY_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ICON_URL | character | None |
| ID | bigint | NOT NULL |
| ISSUE_TYPE_IDS | text | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_INIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_ISSUE_SOURCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CONVERSION_FACTOR | double | None |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| SOURCE_TYPE | character | None |
| SOURCE_VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_NONWORKINGDAYS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END | bigint | None |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| START | bigint | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PERMISSIONS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HOLDER_KEY | character | NOT NULL |
| HOLDER_TYPE | integer | NOT NULL, DEFAULT |
| ID | bigint | NOT NULL |
| PERMISSION | integer | NOT NULL, DEFAULT |
| PLAN_ID | bigint | None |
| PROGRAM_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |
| PROGRAM_ID | AO_D9132D_PROGRAM | ID |

---

### AO_D9132D_PLAN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ASSIGNEE_SCHEDULING_LEVEL | bigint | DEFAULT |
| COMMIT_ISSUE_ASSIGNEE | integer | None |
| DEFAULT_ESTIMATES | text | DEFAULT |
| DEFAULT_TEAM_WEEKLY_CAPACITY | double | DEFAULT |
| DEF_EST_MAP | character | None |
| DEPENDENCY_MODE | bigint | None |
| GLOBAL_DEFAULT_VELOCITY | double | DEFAULT |
| GLOBAL_SPRINT_LENGTH | integer | DEFAULT |
| HAS_SPRINT_CONSTRAINT | integer | DEFAULT |
| HEURISTIC_THRESHOLD | integer | DEFAULT |
| HOURS_PER_DAY | double | DEFAULT |
| ID | bigint | NOT NULL |
| MAX_RESOURCES_PER_STORY | bigint | DEFAULT |
| MIN_LOAD_UNSTR_EPICS | bigint | DEFAULT |
| PLANNING_UNIT | bigint | None |
| SCHEDULING_VERBOSITY | bigint | DEFAULT |
| SPRINT_EXCEEDED_WARN | integer | DEFAULT |
| STRICT_STAGE_DIVISION | integer | DEFAULT |
| SYNC_START_ENABLED | integer | DEFAULT |
| TITLE | character | None |
| UNESTIMATED_ISSUES_OPTION | bigint | DEFAULT |
| WEEKDAY_CONFIGURATION | integer | DEFAULT |
| CREATED_TIMESTAMP | bigint | None |
| INCLUDE_COMPLETED_ISSUES_FOR | integer | None |
| MULTI_SCENARIO_ENABLED | integer | None |
| PORTFOLIO_PLAN_VERSION | bigint | DEFAULT |
| BASELINE_END_FIELD_ID | character | None |
| BASELINE_START_FIELD_ID | character | None |
| IGNORE_SPRINTS | integer | None |
| TIME_ZONE | character | None |
| SCHEDULING_END_CUSTOM_FIELD | bigint | None |
| SCHEDULING_START_CUSTOM_FIELD | bigint | None |
| PROGRAM_ID | bigint | None |
| ISSUE_INFERRED_DATE_SELECTION | bigint | None |
| IGNORE_TEAMS | integer | None |
| CREATOR_ID | character | None |
| RANK_AGAINST_STORIES | boolean | None |
| IGNORE_RELEASES | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_PLANNED_CAPACITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CAPACITY | double | NOT NULL |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITERATION_ID | bigint | NOT NULL |
| PLANNING_UNIT | character | NOT NULL |
| PLAN_ID | bigint | None |
| SCHEDULING_MODE | character | NOT NULL |
| SPRINT_ID | character | None |
| TEAM_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PLANSKILL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| SKILL_ID | bigint | None |
| STAGE | bigint | None |
| WEIGHT | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PLANTEAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| ISSUE_SOURCE_ID | bigint | None |
| ITERATION_LENGTH | bigint | None |
| PLAN_ID | bigint | None |
| SCHEDULING_MODE | bigint | None |
| TEAM_ID | bigint | None |
| VELOCITY | double | None |
| WEEKLY_HOURS | double | None |
| CAPACITY_MEASUREMENT | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| ISSUE_SOURCE_ID | AO_D9132D_ISSUE_SOURCE | ID |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PLANTHEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| THEME_ID | bigint | None |
| WEIGHT | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |
| THEME_ID | AO_D9132D_THEME | ID |

---

### AO_D9132D_PLANVERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| VERSION_ID | bigint | None |
| XPROJECT_VERSION_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |
| XPROJECT_VERSION_ID | AO_D9132D_X_PROJECT_VERSION | ID |

---

### AO_D9132D_PLAN_CUSTOM_FIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CUSTOM_FIELD_ID | bigint | None |
| C_KEY | character | NOT NULL |
| FILTERING_ALLOWED | boolean | None |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PLAN_USER_PROPERTY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| PLAN_ID | bigint | NOT NULL |
| USER_KEY | character | NOT NULL |
| VALUE | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_PLAN_US_PR_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | DEFAULT |
| USER_ID | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_PROGRAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DESCRIPTION | text | None |
| ID | bigint | NOT NULL |
| OWNER | character | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_PROGRAM_CUSTOM_FIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CUSTOM_FIELD_ID | bigint | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| PROGRAM_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PROGRAM_ID | AO_D9132D_PROGRAM | ID |

---

### AO_D9132D_RANK_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DOMAIN | character | None |
| ID | bigint | NOT NULL |
| KEY | character | NOT NULL |
| RANGE_ID | bigint | NOT NULL, DEFAULT |
| UNIQUE | character | NOT NULL, UNIQUE |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_SAVED_VIEW

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | None |
| DEFAULT | boolean | DEFAULT |
| ID | bigint | NOT NULL |
| LAST_MODIFIED_BY | character | None |
| LAST_MODIFIED_TIMESTAMP | bigint | None |
| NAME | character | NOT NULL |
| PREFERENCES | text | NOT NULL |
| SUBJECT_ID | bigint | DEFAULT |
| SUBJECT_TYPE | character | NOT NULL |
| VERSION | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_SAVED_VIEW2

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_BY | character | None |
| CREATED_TIMESTAMP | bigint | None |
| C_KEY | character | NOT NULL |
| DEFAULT | boolean | DEFAULT |
| ID | bigint | NOT NULL |
| LAST_MODIFIED_BY | character | None |
| LAST_MODIFIED_TIMESTAMP | bigint | None |
| NAME | character | NOT NULL |
| PREFERENCES | text | NOT NULL |
| SUBJECT_ID | bigint | DEFAULT |
| SUBJECT_TYPE | character | NOT NULL |
| VERSION | bigint | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_SCENARIO

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| TITLE | character | None |
| COLOR | character | None |
| DESCRIPTION | character | None |
| MASTER | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_SCENARIO_ABILITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| PERSON_ITEM_KEY | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| SKILL_ITEM_KEY | character | None |
| U_AB | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_AVLBLTY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END | bigint | None |
| ID | bigint | NOT NULL |
| SCENARIO_RESOURCE_ID | bigint | None |
| START | bigint | None |
| TITLE | character | None |
| WEEKLY_HOURS | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_RESOURCE_ID | AO_D9132D_SCENARIO_RESOURCE | ID |

---

### AO_D9132D_SCENARIO_CHANGES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COUNTER | bigint | NOT NULL |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| SCENARIO_ID | bigint | None |
| T_TYPE | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_ISSUES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| DESCRIPTION | text | None |
| DESCRIPTION_CHANGED | boolean | None |
| DISTRIBUTION_CHANGED | boolean | None |
| EARLIEST_START | bigint | None |
| EARLIEST_START_CHANGED | boolean | None |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| LATER_RELEASE | boolean | None |
| LATER_RELEASE_CHANGED | boolean | None |
| PARENT_ID | character | None |
| PARENT_ID_CHANGED | boolean | None |
| PROJECT_ID | bigint | None |
| PROJECT_ID_CHANGED | boolean | None |
| RESOURCES_CHANGED | boolean | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| SPRINT_ID | character | None |
| SPRINT_ID_CHANGED | boolean | None |
| STATUS_ID | character | None |
| STATUS_ID_CHANGED | boolean | None |
| STORY_POINTS_ESTIMATE | double | None |
| STORY_POINTS_ESTIMATE_CHANGED | boolean | None |
| TEAM_ID_CHANGED | boolean | None |
| TEAM_KEY | character | None |
| THEME_ID | character | None |
| THEME_ID_CHANGED | boolean | None |
| TIME_ESTIMATE | bigint | None |
| TIME_ESTIMATE_CHANGED | boolean | None |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| TYPE_ID | bigint | None |
| TYPE_ID_CHANGED | boolean | None |
| VERSION_ID | character | None |
| VERSION_ID_CHANGED | boolean | None |
| BSLN_EARLIEST_START_CHANGED | boolean | None |
| DUE_DATE_CHANGED | boolean | None |
| ORIG_STPTS_ESTIMATE_CHANGED | boolean | None |
| CREATED | bigint | None |
| ORIG_TIME_ESTIMATE | bigint | None |
| ORIG_TIME_ESTIMATE_CHANGED | boolean | None |
| ORIG_DIST_CHANGED | boolean | None |
| LABELS_CHANGED | boolean | None |
| COMPONENTS_CHANGED | boolean | None |
| DUE_DATE | bigint | None |
| ASSIGNEE_ID | character | None |
| PRIORITY_ID | character | None |
| ORIG_STPTS_ESTIMATE | double | None |
| PRIORITY_ID_CHANGED | boolean | None |
| BASELINE_END | bigint | None |
| BASELINE_END_CHANGED | boolean | None |
| ASSIGNEE_ID_CHANGED | boolean | None |
| BSLN_EARLIEST_START | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_ISSUE_CMPNT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMPONENT_ID | bigint | None |
| ID | bigint | NOT NULL |
| SCENARIO_ISSUE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ISSUE_ID | AO_D9132D_SCENARIO_ISSUES | ID |

---

### AO_D9132D_SCENARIO_ISSUE_LABEL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| LABEL | character | None |
| SCENARIO_ISSUE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ISSUE_ID | AO_D9132D_SCENARIO_ISSUES | ID |

---

### AO_D9132D_SCENARIO_ISSUE_LINKS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| LINK_TYPE | bigint | None |
| LINK_TYPE_CHANGED | boolean | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| SOURCE | character | None |
| TARGET | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_ISSUE_RES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| RESOURCE_ITEM_KEY | character | None |
| SCENARIO_ISSUE_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ISSUE_ID | AO_D9132D_SCENARIO_ISSUES | ID |

---

### AO_D9132D_SCENARIO_PERSON

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_PLAN_CAP

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CAPACITY | double | None |
| CAPACITY_CHANGED | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| ITERATION_ID | bigint | None |
| ITERATION_ID_CHANGED | boolean | None |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| PLANNING_UNIT | character | None |
| PLANNING_UNIT_CHANGED | boolean | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| SCHEDULING_MODE | character | None |
| SCHEDULING_MODE_CHANGED | boolean | None |
| SPRINT_ID | character | None |
| SPRINT_ID_CHANGED | boolean | None |
| TEAM_KEY | character | None |
| TEAM_KEY_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_RESOURCE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AVAILABILITY_CHANGED | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| JOIN_DATE | bigint | None |
| JOIN_DATE_CHANGED | boolean | None |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| LEAVE_DATE | bigint | None |
| LEAVE_DATE_CHANGED | boolean | None |
| PERSON_ITEM_KEY | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| TEAM_ITEM_KEY | character | None |
| WEEKLY_HOURS | double | None |
| WEEKLY_HOURS_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_SKILL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADD_TO_PLAN | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| STAGE_ID | character | None |
| STAGE_ID_CHANGED | boolean | None |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| WEIGHT | double | None |
| WEIGHT_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_STAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | None |
| COLOR_CHANGED | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| WEIGHT | double | None |
| WEIGHT_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_TEAM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADD_TO_PLAN | boolean | None |
| AVATAR | character | None |
| AVATAR_CHANGED | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ISSUE_SOURCE_CHANGED | boolean | None |
| ISSUE_SOURCE_ID | bigint | None |
| ITEM_KEY | character | NOT NULL |
| ITERATION_LENGTH | bigint | None |
| ITERATION_LENGTH_CHANGED | boolean | None |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| SCHEDULING_MODE | character | None |
| SCHEDULING_MODE_CHANGED | boolean | None |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| VELOCITY | double | None |
| VELOCITY_CHANGED | boolean | None |
| WEEKLY_HOURS | double | None |
| WEEKLY_HOURS_CHANGED | boolean | None |
| CAPACITY_MEASUREMENT_CHANGED | boolean | None |
| CAPACITY_MEASUREMENT | character | None |
| EXCLUDED_SPRINTS_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| ISSUE_SOURCE_ID | AO_D9132D_ISSUE_SOURCE | ID |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_THEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADD_TO_PLAN | boolean | None |
| COLOR | character | None |
| COLOR_CHANGED | boolean | None |
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| WEIGHT | double | None |
| WEIGHT_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_VERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| DELTA | bigint | None |
| DELTA_CHANGED | boolean | None |
| DESCRIPTION | text | None |
| DESCRIPTION_CHANGED | boolean | None |
| END_DATE | bigint | None |
| END_DATE_CHANGED | boolean | None |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| PROJECT_ID | bigint | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |
| START_DATE | bigint | None |
| START_DATE_CHANGED | boolean | None |
| TITLE | character | None |
| TITLE_CHANGED | boolean | None |
| XPROJECT_VERSION | character | None |
| XPROJECT_VERSION_CHANGED | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCENARIO_XPVERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| ID | bigint | NOT NULL |
| ITEM_KEY | character | NOT NULL |
| LAST_CHANGE_TIMESTAMP | bigint | None |
| LAST_CHANGE_USER | character | None |
| NAME | character | None |
| NAME_CHANGED | boolean | None |
| SCENARIO_ID | bigint | None |
| SCENARIO_TYPE | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ID | AO_D9132D_SCENARIO | ID |

---

### AO_D9132D_SCEN_CSTM_FLD_MVAL

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| SCENARIO_ISSUE_CUSTOM_FIELD_ID | bigint | None |
| VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_ISSUE_CUSTOM_FIELD_ID | AO_D9132D_SCEN_CUSTOM_FIELD | ID |

---

### AO_D9132D_SCEN_CUSTOM_FIELD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| C_KEY | character | NOT NULL |
| DOUBLE_VALUE | double | None |
| ID | bigint | NOT NULL |
| NUMBER_VALUE | bigint | None |
| PLAN_CUSTOM_FIELD_ID | bigint | None |
| SCENARIO_ISSUE_ID | bigint | None |
| STRING_VALUE | character | None |
| TEXT_VALUE | text | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_CUSTOM_FIELD_ID | AO_D9132D_PLAN_CUSTOM_FIELD | ID |
| SCENARIO_ISSUE_ID | AO_D9132D_SCENARIO_ISSUES | ID |

---

### AO_D9132D_SCEN_TEAM_EX_SPRINT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| SCENARIO_TEAM_ID | bigint | None |
| SPRINT_ID | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| SCENARIO_TEAM_ID | AO_D9132D_SCENARIO_TEAM | ID |

---

### AO_D9132D_SHARED_REPORT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| FILTER_CONFIGURATION | text | NOT NULL |
| FILTER_CONFIG_HASH | integer | None |
| HASH | character | NOT NULL |
| HIERARCHY_LEVEL | integer | NOT NULL |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | NOT NULL |
| REPORT_CONFIGURATION | text | None |
| REPORT_CONFIG_HASH | integer | None |
| REPORT_ID | character | NOT NULL |
| SCENARIO | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_SOLUTION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| HEARTBEAT_TIMESTAMP | timestamp | NOT NULL |
| ID | bigint | NOT NULL |
| PLAN | bigint | NOT NULL |
| SCHEDULABLE_ISSUE_COUNT | bigint | None |
| SCHEDULED_ISSUE_COUNT | bigint | None |
| SOLUTION | text | None |
| STATE | character | NOT NULL |
| TRIGGER_TIMESTAMP | timestamp | NOT NULL |
| UNIQUE_GUARD | character | NOT NULL, UNIQUE |
| VERSION | character | None |
| SCENARIO | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_STAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | None |
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| SKILL_ID | bigint | None |
| WEIGHT | double | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_D9132D_TEAM_EX_SPRINT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLANTEAM_ID | bigint | None |
| PLAN_TEAM_ID | bigint | None |
| SPRINT_ID | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_TEAM_ID | AO_D9132D_PLANTEAM | ID |

---

### AO_D9132D_THEME

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COLOR | character | None |
| ID | bigint | NOT NULL |
| SHARED | boolean | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_VERSION_ENRICHMENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DELTA | bigint | None |
| ENV_ID | bigint | NOT NULL |
| ID | bigint | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_D9132D_X_PROJECT_VERSION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| PLAN_ID | bigint | None |
| TITLE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| PLAN_ID | AO_D9132D_PLAN | ID |

---

### AO_E8B6CC_BRANCH

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| NAME | character | None |
| REPOSITORY_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_BRANCH_HEAD_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BRANCH_NAME | character | None |
| HEAD | character | None |
| ID | integer | NOT NULL |
| REPOSITORY_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_CHANGESET_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHOR | character | None |
| AUTHOR_EMAIL | character | None |
| BRANCH | character | None |
| DATE | timestamp | None |
| FILES_DATA | text | None |
| FILE_COUNT | integer | DEFAULT |
| FILE_DETAILS_JSON | text | None |
| ID | integer | NOT NULL |
| ISSUE_KEY | character | None |
| MESSAGE | text | None |
| NODE | character | None |
| PARENTS_DATA | character | None |
| PROJECT_KEY | character | None |
| RAW_AUTHOR | character | None |
| RAW_NODE | character | None |
| REPOSITORY_ID | integer | DEFAULT |
| SMARTCOMMIT_AVAILABLE | boolean | None |
| VERSION | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_COMMIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHOR | character | None |
| AUTHOR_AVATAR_URL | character | None |
| DATE | timestamp | NOT NULL |
| DOMAIN_ID | integer | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| MERGE | boolean | None |
| MESSAGE | text | None |
| NODE | character | None |
| RAW_AUTHOR | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_GIT_HUB_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | timestamp | NOT NULL |
| GIT_HUB_ID | character | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| REPOSITORY_ID | integer | NOT NULL |
| SAVE_POINT | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_HOOK_MIGRATION_TASK

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| ORGANIZATION_ID | integer | DEFAULT |
| REPOSITORY_ID | integer | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ISSUE_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| ISSUE_ID | character | None |
| NODE | character | None |
| PROJECT_KEY | character | None |
| REPOSITORY_URI | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ISSUE_MAPPING_V2

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHOR | character | None |
| BRANCH | character | None |
| DATE | timestamp | None |
| FILES_DATA | text | None |
| ID | integer | NOT NULL |
| ISSUE_ID | character | None |
| MESSAGE | text | None |
| NODE | character | None |
| PARENTS_DATA | character | None |
| RAW_AUTHOR | character | None |
| RAW_NODE | character | None |
| REPOSITORY_ID | integer | None |
| VERSION | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ISSUE_TO_BRANCH

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| BRANCH_ID | integer | None |
| ID | integer | NOT NULL |
| ISSUE_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ISSUE_TO_CHANGESET

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHANGESET_ID | integer | None |
| ID | integer | NOT NULL |
| ISSUE_KEY | character | None |
| PROJECT_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_MESSAGE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADDRESS | character | NOT NULL |
| ID | integer | NOT NULL |
| PAYLOAD | text | NOT NULL |
| PAYLOAD_TYPE | character | NOT NULL |
| PRIORITY | integer | NOT NULL, DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_MESSAGE_QUEUE_ITEM

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| LAST_FAILED | timestamp | None |
| MESSAGE_ID | integer | NOT NULL |
| QUEUE | character | NOT NULL |
| RETRIES_COUNT | integer | NOT NULL, DEFAULT |
| STATE | character | NOT NULL |
| STATE_INFO | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_MESSAGE_TAG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | bigint | NOT NULL |
| MESSAGE_ID | integer | None |
| TAG | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ORGANIZATION_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_TOKEN | character | None |
| ADMIN_PASSWORD | character | None |
| ADMIN_USERNAME | character | None |
| APPROVAL_STATE | character | None |
| AUTOLINK_NEW_REPOS | boolean | None |
| DEFAULT_GROUPS_SLUGS | character | DEFAULT |
| DVCS_TYPE | character | None |
| HOST_URL | character | None |
| ID | integer | NOT NULL |
| NAME | character | None |
| OAUTH_KEY | character | None |
| OAUTH_SECRET | character | None |
| PRINCIPAL_ID | character | None |
| SMARTCOMMITS_FOR_NEW_REPOS | boolean | None |
| WEBHOOK_SECRET | character | None |
| TOKEN_ID | character | None |
| STATUS | character | None |
| LAST_POLLED | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_ORG_TO_PROJECT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| ORGANIZATION_ID | integer | None |
| PROJECT_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PROJECT_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PASSWORD | character | None |
| PROJECT_KEY | character | None |
| REPOSITORY_URI | character | None |
| USERNAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PROJECT_MAPPING_V2

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_TOKEN | character | None |
| ADMIN_PASSWORD | character | None |
| ADMIN_USERNAME | character | None |
| ID | integer | NOT NULL |
| LAST_COMMIT_DATE | timestamp | None |
| PROJECT_KEY | character | None |
| REPOSITORY_NAME | character | None |
| REPOSITORY_TYPE | character | None |
| REPOSITORY_URL | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PR_ISSUE_KEY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| DOMAIN_ID | integer | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| ISSUE_KEY | character | None |
| PULL_REQUEST_ID | integer | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PR_PARTICIPANT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| APPROVED | boolean | None |
| DOMAIN_ID | integer | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| PULL_REQUEST_ID | integer | None |
| ROLE | character | None |
| USERNAME | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PR_TO_COMMIT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| COMMIT_ID | integer | NOT NULL |
| DOMAIN_ID | integer | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| REQUEST_ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_PULL_REQUEST

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHOR | character | None |
| COMMENT_COUNT | integer | DEFAULT |
| CREATED_ON | timestamp | None |
| DESTINATION_BRANCH | character | None |
| DOMAIN_ID | integer | NOT NULL, DEFAULT |
| EXECUTED_BY | character | None |
| ID | integer | NOT NULL |
| LAST_STATUS | character | None |
| NAME | character | None |
| REMOTE_ID | bigint | None |
| SOURCE_BRANCH | character | None |
| SOURCE_REPO | character | None |
| TO_REPOSITORY_ID | integer | DEFAULT |
| UPDATED_ON | timestamp | None |
| URL | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_REPOSITORY_MAPPING

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACTIVITY_LAST_SYNC | timestamp | None |
| DELETED | boolean | None |
| FORK | boolean | None |
| FORK_OF_NAME | character | None |
| FORK_OF_OWNER | character | None |
| FORK_OF_SLUG | character | None |
| ID | integer | NOT NULL |
| LAST_CHANGESET_NODE | character | None |
| LAST_COMMIT_DATE | timestamp | None |
| LINKED | boolean | None |
| LOGO | text | None |
| NAME | character | None |
| ORGANIZATION_ID | integer | DEFAULT |
| SLUG | character | None |
| SMARTCOMMITS_ENABLED | boolean | None |
| UPDATE_LINK_AUTHORISED | boolean | None |
| WEBHOOK_STATUS | character | None |
| REPOSITORY_URI | character | None |
| REMOTE_ID | character | None |
| REPOSITORY_URL | text | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_REPO_TO_CHANGESET

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CHANGESET_ID | integer | None |
| ID | integer | NOT NULL |
| REPOSITORY_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_REPO_TO_PROJECT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| PROJECT_KEY | character | None |
| REPOSITORY_ID | integer | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_SYNC_AUDIT_LOG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| END_DATE | timestamp | None |
| EXC_TRACE | text | None |
| FIRST_REQUEST_DATE | timestamp | None |
| FLIGHT_TIME_MS | integer | DEFAULT |
| ID | integer | NOT NULL |
| NUM_REQUESTS | integer | DEFAULT |
| REPO_ID | integer | DEFAULT |
| START_DATE | timestamp | None |
| SYNC_STATUS | character | None |
| SYNC_TYPE | character | None |
| TOTAL_ERRORS | integer | DEFAULT |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_E8B6CC_SYNC_EVENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT_CLASS | text | NOT NULL |
| EVENT_DATE | timestamp | NOT NULL |
| EVENT_JSON | text | NOT NULL |
| ID | integer | NOT NULL |
| REPO_ID | integer | NOT NULL, DEFAULT |
| SCHEDULED_SYNC | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_ED669C_IDP_CONFIG

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ADDITIONAL_JIT_SCOPES | text | None |
| ADDITIONAL_SCOPES | text | None |
| AUTHORIZATION_ENDPOINT | character | None |
| BUTTON_TEXT | character | NOT NULL |
| CLIENT_ID | character | None |
| CLIENT_SECRET | character | None |
| ENABLED | boolean | NOT NULL |
| ENABLE_REMEMBER_ME | boolean | None |
| ID | bigint | NOT NULL |
| INCLUDE_CUSTOMER_LOGINS | boolean | None |
| ISSUER | character | NOT NULL |
| LAST_UPDATED | timestamp | None |
| MAPPING_DISPLAYNAME | character | None |
| MAPPING_EMAIL | character | None |
| MAPPING_GROUPS | character | None |
| NAME | character | NOT NULL |
| SAML_IDP_TYPE | character | None |
| SIGNING_CERT | text | None |
| SSO_TYPE | character | None |
| SSO_URL | character | None |
| TOKEN_ENDPOINT | character | None |
| USERNAME_ATTRIBUTE | character | None |
| USERNAME_CLAIM | character | None |
| USER_INFO_ENDPOINT | character | None |
| USER_PROVISIONING_ENABLED | boolean | None |
| USE_DISCOVERY | boolean | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_ED669C_SEALED_ENTITY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | NOT NULL |
| VALUE | text | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_ED669C_SEEN_ASSERTIONS

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ASSERTION_ID | character | NOT NULL |
| EXPIRY_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_ED669C_TOTP_CODES

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EXPIRY_TIMESTAMP | bigint | NOT NULL, DEFAULT |
| ID | integer | NOT NULL |
| TOTP_CODE_HASH | character | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_ED669C_TOTP_USER_ENROLLMENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CREATED_AT | timestamp | NOT NULL |
| MODIFIED_AT | timestamp | NOT NULL |
| RECOVERY_CODE | character | NOT NULL |
| SECRET | text | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** USER_KEY

**Foreign Keys:** None

---

### AO_F1B27B_HISTORY_RECORD

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| EVENT_TIME_MILLIS | bigint | None |
| EVENT_TYPE | character | None |
| ID | integer | NOT NULL |
| MESSAGE | character | None |
| TARGET_TIME_MILLIS | bigint | None |
| TIMED_PROMISE_HISTORY_KEY_HASH | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_F1B27B_KEY_COMPONENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | None |
| TIMED_PROMISE_ID | integer | None |
| VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| TIMED_PROMISE_ID | AO_F1B27B_PROMISE | ID |

---

### AO_F1B27B_KEY_COMP_HISTORY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ID | integer | NOT NULL |
| KEY | character | None |
| TIMED_PROMISE_ID | integer | None |
| VALUE | character | None |

**Primary Key(s):** ID

**Foreign Keys:**

| Column(s) | References Table | References Column(s) |
|-----------|------------------|--------------------- |
| TIMED_PROMISE_ID | AO_F1B27B_PROMISE_HISTORY | ID |

---

### AO_F1B27B_PROMISE

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLASSIFICATION | character | None |
| CONTENT | text | None |
| CREATED_TIME_MILLIS | bigint | None |
| ID | integer | NOT NULL |
| KEY_HASH | character | None |
| MIME_TYPE | character | None |
| STATUS | character | None |
| TARGET_TIME_MILLIS | bigint | None |
| TASK_KEY | character | None |
| UPDATED_TIME_MILLIS | bigint | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_F1B27B_PROMISE_HISTORY

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLASSIFICATION | character | None |
| ID | integer | NOT NULL |
| KEY_HASH | character | None |
| TASK_KEY | character | None |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_FE1BC5_ACCESS_TOKEN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHORIZATION_CODE | character | NOT NULL |
| AUTHORIZATION_DATE | bigint | NOT NULL |
| CLIENT_ID | character | NOT NULL |
| CREATED_AT | bigint | NOT NULL |
| ID | character | NOT NULL |
| LAST_ACCESSED | bigint | None |
| SCOPE | character | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_FE1BC5_AUTHORIZATION

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| AUTHORIZATION_CODE | character | NOT NULL |
| CLIENT_ID | character | NOT NULL |
| CODE_CHALLENGE | character | None |
| CODE_CHALLENGE_METHOD | character | None |
| CREATED_AT | bigint | NOT NULL |
| REDIRECT_URI | character | NOT NULL |
| SCOPE | character | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** AUTHORIZATION_CODE

**Foreign Keys:** None

---

### AO_FE1BC5_CLIENT

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLIENT_ID | character | NOT NULL |
| CLIENT_SECRET | character | NOT NULL |
| ID | character | NOT NULL |
| NAME | character | NOT NULL |
| SCOPE | character | None |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_FE1BC5_REDIRECT_URI

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| CLIENT_ID | character | NOT NULL |
| ID | integer | NOT NULL |
| URI | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### AO_FE1BC5_REFRESH_TOKEN

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| ACCESS_TOKEN_ID | character | None |
| AUTHORIZATION_CODE | character | NOT NULL |
| AUTHORIZATION_DATE | bigint | NOT NULL |
| CLIENT_ID | character | NOT NULL |
| CREATED_AT | bigint | NOT NULL |
| ID | character | NOT NULL |
| REFRESH_COUNT | integer | None |
| SCOPE | character | NOT NULL |
| USER_KEY | character | NOT NULL |

**Primary Key(s):** ID

**Foreign Keys:** None

---

### app_user

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| user_key | character | None |
| lower_user_name | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### audit_changed_value

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| log_id | numeric(18 | None |
| name | character | None |
| delta_from | text | None |
| delta_to | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### audit_item

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| log_id | numeric(18 | None |
| object_type | character | None |
| object_id | character | None |
| object_name | character | None |
| object_parent_id | character | None |
| object_parent_name | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### audit_log

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| remote_address | character | None |
| created | timestamp | None |
| author_key | character | None |
| summary | character | None |
| category | character | None |
| object_type | character | None |
| object_id | character | None |
| object_name | character | None |
| object_parent_id | character | None |
| object_parent_name | character | None |
| author_type | numeric(9 | None |
| event_source_name | character | None |
| description | character | None |
| long_description | text | None |
| search_field | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### avatar

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| filename | character | None |
| contenttype | character | None |
| avatartype | character | None |
| owner | character | None |
| systemavatar | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### board

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| jql | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### boardproject

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| board_id | numeric(18 | NOT NULL |
| project_id | numeric(18 | NOT NULL |

**Primary Key(s):** board_id, project_id

**Foreign Keys:** None

---

### changegroup

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| author | character | None |
| created | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### changeitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| groupid | numeric(18 | None |
| fieldtype | character | None |
| field | character | None |
| oldvalue | text | None |
| oldstring | text | None |
| newvalue | text | None |
| newstring | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### clusteredjob

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| job_id | character | None |
| job_runner_key | character | None |
| sched_type | character(1) | None |
| interval_millis | numeric(18 | None |
| first_run | numeric(18 | None |
| cron_expression | character | None |
| time_zone | character | None |
| next_run | numeric(18 | None |
| version | numeric(18 | None |
| parameters | bytea | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### clusterlockstatus

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| lock_name | character | None |
| locked_by_node | character | None |
| update_time | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### clustermessage

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| source_node | character | None |
| destination_node | character | None |
| claimed_by_node | character | None |
| message | character | None |
| message_time | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### clusternode

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| node_id | character | NOT NULL |
| node_state | character | None |
| timestamp | numeric(18 | None |
| ip | character | None |
| cache_listener_port | numeric(18 | None |
| node_build_number | numeric(18 | None |
| node_version | character | None |

**Primary Key(s):** node_id

**Foreign Keys:** None

---

### clusternodeheartbeat

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| node_id | character | NOT NULL |
| heartbeat_time | numeric(18 | None |
| database_time | numeric(18 | None |

**Primary Key(s):** node_id

**Foreign Keys:** None

---

### clusterupgradestate

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| database_time | numeric(18 | None |
| cluster_build_number | numeric(18 | None |
| cluster_version | character | None |
| state | character | None |
| order_number | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### columnlayout

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| username | character | None |
| searchrequest | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### columnlayoutitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| columnlayout | numeric(18 | None |
| fieldidentifier | character | None |
| horizontalposition | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### comment_pin

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issue_id | numeric(18 | None |
| comment_id | numeric(18 | None |
| pinned_by | character | None |
| pinned_date | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### comment_reaction

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| comment_id | numeric(18 | None |
| author | character | None |
| emoticon | character | None |
| created_date | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### comment_version

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| comment_id | numeric(18 | NOT NULL |
| parent_issue_id | numeric(18 | None |
| update_time | timestamp | None |
| index_version | numeric(18 | None |
| deleted | character(1) | None |

**Primary Key(s):** comment_id

**Foreign Keys:** None

---

### component

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| project | numeric(18 | None |
| cname | character | None |
| description | text | None |
| url | character | None |
| lead | character | None |
| assigneetype | numeric(18 | None |
| archived | character | None |
| deleted | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### configurationcontext

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| projectcategory | numeric(18 | None |
| project | numeric(18 | None |
| customfield | character | None |
| fieldconfigscheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### customfield

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| cfkey | character | None |
| customfieldtypekey | character | None |
| customfieldsearcherkey | character | None |
| cfname | character | None |
| description | text | None |
| defaultvalue | character | DEFAULT |
| fieldtype | numeric(18 | None |
| project | numeric(18 | None |
| issuetype | character | None |
| issueswithvalue | numeric(18 | None |
| lastvalueupdate | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### customfieldoption

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| customfield | numeric(18 | None |
| customfieldconfig | numeric(18 | None |
| parentoptionid | numeric(18 | None |
| sequence | numeric(18 | None |
| customvalue | character | None |
| optiontype | character | None |
| disabled | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### customfieldvalue

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issue | numeric(18 | None |
| customfield | numeric(18 | None |
| updated | numeric(18 | None |
| parentkey | character | None |
| stringvalue | character | None |
| numbervalue | double | None |
| textvalue | text | None |
| datevalue | timestamp | None |
| valuetype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_application

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| application_name | character | None |
| lower_application_name | character | None |
| created_date | timestamp | None |
| updated_date | timestamp | None |
| active | numeric(9 | None |
| description | character | None |
| application_type | character | None |
| credential | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_application_address

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| application_id | numeric(18 | NOT NULL |
| remote_address | character | NOT NULL |
| encoded_address_binary | character | None |
| remote_address_mask | numeric(9 | None |

**Primary Key(s):** application_id, remote_address

**Foreign Keys:** None

---

### cwd_application_attribute

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| application_id | numeric(18 | NOT NULL |
| attribute_name | character | NOT NULL |
| attribute_value | text | None |

**Primary Key(s):** application_id, attribute_name

**Foreign Keys:** None

---

### cwd_directory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| directory_name | character | None |
| lower_directory_name | character | None |
| created_date | timestamp | None |
| updated_date | timestamp | None |
| active | numeric(9 | None |
| description | character | None |
| impl_class | character | None |
| lower_impl_class | character | None |
| directory_type | character | None |
| directory_position | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_directory_attribute

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| directory_id | numeric(18 | NOT NULL |
| attribute_name | character | NOT NULL |
| attribute_value | text | None |

**Primary Key(s):** directory_id, attribute_name

**Foreign Keys:** None

---

### cwd_directory_operation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| directory_id | numeric(18 | NOT NULL |
| operation_type | character | NOT NULL |

**Primary Key(s):** directory_id, operation_type

**Foreign Keys:** None

---

### cwd_group

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| group_name | character | None |
| lower_group_name | character | None |
| active | numeric(9 | None |
| local | numeric(9 | None |
| created_date | timestamp | None |
| updated_date | timestamp | None |
| description | character | None |
| lower_description | character | None |
| group_type | character | None |
| directory_id | numeric(18 | None |
| external_id | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_group_attributes

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| group_id | numeric(18 | None |
| directory_id | numeric(18 | None |
| attribute_name | character | None |
| attribute_value | character | None |
| lower_attribute_value | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_membership

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| parent_id | numeric(18 | None |
| child_id | numeric(18 | None |
| membership_type | character | None |
| group_type | character | None |
| parent_name | character | None |
| lower_parent_name | character | None |
| child_name | character | None |
| lower_child_name | character | None |
| directory_id | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_synchronisation_status

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| directory_id | numeric(18 | None |
| node_id | character | None |
| sync_start | numeric(18 | None |
| sync_end | numeric(18 | None |
| sync_status | character | None |
| status_parameters | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_synchronisation_token

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| directory_id | numeric(18 | NOT NULL |
| sync_status_token | text | None |

**Primary Key(s):** directory_id

**Foreign Keys:** None

---

### cwd_user

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| directory_id | numeric(18 | None |
| user_name | character | None |
| lower_user_name | character | None |
| active | numeric(9 | None |
| created_date | timestamp | None |
| updated_date | timestamp | None |
| first_name | character | None |
| lower_first_name | character | None |
| last_name | character | None |
| lower_last_name | character | None |
| display_name | character | None |
| lower_display_name | character | None |
| email_address | character | None |
| lower_email_address | character | None |
| credential | character | None |
| deleted_externally | numeric(9 | None |
| external_id | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### cwd_user_attributes

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| user_id | numeric(18 | None |
| directory_id | numeric(18 | None |
| attribute_name | character | None |
| attribute_value | character | None |
| lower_attribute_value | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### deadletter

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| message_id | character | None |
| last_seen | numeric(18 | None |
| mail_server_id | numeric(18 | None |
| folder_name | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### draftworkflowscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |
| workflow_scheme_id | numeric(18 | None |
| last_modified_date | timestamp | None |
| last_modified_user | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### draftworkflowschemeentity

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| workflow | character | None |
| issuetype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### entity_property

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entity_name | character | None |
| entity_id | numeric(18 | None |
| property_key | character | None |
| created | timestamp | None |
| updated | timestamp | None |
| json_value | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### entity_property_index_document

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| plugin_key | character | None |
| module_key | character | None |
| entity_key | character | None |
| updated | timestamp | None |
| document | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### entity_translation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entity_name | character | None |
| entity_id | numeric(18 | None |
| locale | character | None |
| trans_name | character | None |
| trans_desc | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### external_entities

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| entitytype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### externalgadget

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| gadget_xml | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### favouriteassociations

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| username | character | None |
| entitytype | character | None |
| entityid | numeric(18 | None |
| sequence | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### feature

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| feature_name | character | None |
| feature_type | character | None |
| user_key | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldconfigscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| configname | character | None |
| description | text | None |
| fieldid | character | None |
| customfield | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldconfigschemeissuetype

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issuetype | character | None |
| fieldconfigscheme | numeric(18 | None |
| fieldconfiguration | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldconfiguration

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| configname | character | None |
| description | text | None |
| fieldid | character | None |
| customfield | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldlayout

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | character | None |
| layout_type | character | None |
| layoutscheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldlayoutitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| fieldlayout | numeric(18 | None |
| fieldidentifier | character | None |
| description | text | None |
| verticalposition | numeric(18 | None |
| ishidden | character | None |
| isrequired | character | None |
| renderertype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldlayoutscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldlayoutschemeassociation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issuetype | character | None |
| project | numeric(18 | None |
| fieldlayoutscheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldlayoutschemeentity

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| issuetype | character | None |
| fieldlayout | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldscreen

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldscreenlayoutitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| fieldidentifier | character | None |
| sequence | numeric(18 | None |
| fieldscreentab | numeric(18 | None |
| showwhenemptyindicator | character(1) | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldscreenscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldscreenschemeitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| operation | numeric(18 | None |
| fieldscreen | numeric(18 | None |
| fieldscreenscheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fieldscreentab

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | character | None |
| sequence | numeric(18 | None |
| fieldscreen | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### fileattachment

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| mimetype | character | None |
| filename | character | None |
| created | timestamp | None |
| filesize | numeric(18 | None |
| author | character | None |
| zip | numeric(9 | None |
| thumbnailable | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### filtersubscription

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| filter_i_d | numeric(18 | None |
| username | character | None |
| groupname | character | None |
| last_run | timestamp | None |
| email_on_empty | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### gadgetuserpreference

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| portletconfiguration | numeric(18 | None |
| userprefkey | character | None |
| userprefvalue | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### genericconfiguration

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| datatype | character | None |
| datakey | character | None |
| xmlvalue | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### globalpermissionentry

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| permission | character | None |
| group_id | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### groupbase

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| groupname | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issue_field_option

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| option_id | numeric(18 | None |
| field_key | character | None |
| option_value | character | None |
| properties | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issue_field_option_scope

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| option_id | numeric(18 | None |
| entity_id | character | None |
| scope_type | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issue_version

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| issue_id | numeric(18 | NOT NULL |
| parent_issue_id | numeric(18 | None |
| update_time | timestamp | None |
| index_version | numeric(18 | None |
| deleted | character(1) | None |

**Primary Key(s):** issue_id

**Foreign Keys:** None

---

### issuelink

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| linktype | numeric(18 | None |
| source | numeric(18 | None |
| destination | numeric(18 | None |
| sequence | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuelinktype

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| linkname | character | None |
| inward | character | None |
| outward | character | None |
| pstyle | character | None |
| position | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuesecurityscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |
| defaultlevel | numeric(18 | DEFAULT |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuestatus

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | character | NOT NULL |
| sequence | numeric(18 | None |
| pname | character | None |
| description | text | None |
| iconurl | character | None |
| statuscategory | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuetype

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | character | NOT NULL |
| sequence | numeric(18 | None |
| pname | character | None |
| pstyle | character | None |
| description | text | None |
| iconurl | character | None |
| avatar | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuetypescreenscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### issuetypescreenschemeentity

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issuetype | character | None |
| scheme | numeric(18 | None |
| fieldscreenscheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraaction

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| author | character | None |
| actiontype | character | None |
| actionlevel | character | None |
| rolelevel | numeric(18 | None |
| actionbody | text | None |
| created | timestamp | None |
| updateauthor | character | None |
| updated | timestamp | None |
| actionnum | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiradraftworkflows

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| parentname | character | None |
| descriptor | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraeventtype

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| template_id | numeric(18 | None |
| name | character | None |
| description | text | None |
| event_type | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraissue

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| pkey | character | None |
| issuenum | numeric(18 | None |
| project | numeric(18 | None |
| reporter | character | None |
| assignee | character | None |
| creator | character | None |
| issuetype | character | None |
| summary | character | None |
| description | text | None |
| environment | text | None |
| priority | character | None |
| resolution | character | None |
| issuestatus | character | None |
| created | timestamp | None |
| updated | timestamp | None |
| duedate | timestamp | None |
| resolutiondate | timestamp | None |
| votes | numeric(18 | None |
| watches | numeric(18 | None |
| timeoriginalestimate | numeric(18 | None |
| timeestimate | numeric(18 | None |
| timespent | numeric(18 | None |
| workflow_id | numeric(18 | None |
| security | numeric(18 | None |
| fixfor | numeric(18 | None |
| component | numeric(18 | None |
| archived | character(1) | None |
| archivedby | character | None |
| archiveddate | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraperms

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| permtype | numeric(18 | None |
| projectid | numeric(18 | None |
| groupname | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraworkflows

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| workflowname | character | None |
| creatorname | character | None |
| descriptor | text | None |
| islocked | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jiraworkflowstatuses

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| status | character | None |
| parentname | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### jquartz_blob_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_name | character | NOT NULL |
| trigger_group | character | NOT NULL |
| blob_data | bytea | None |

**Primary Key(s):** trigger_name, trigger_group

**Foreign Keys:** None

---

### jquartz_calendars

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| calendar_name | character | NOT NULL |
| calendar | bytea | None |

**Primary Key(s):** calendar_name

**Foreign Keys:** None

---

### jquartz_cron_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_name | character | NOT NULL |
| trigger_group | character | NOT NULL |
| cron_expression | character | None |
| time_zone_id | character | None |

**Primary Key(s):** trigger_name, trigger_group

**Foreign Keys:** None

---

### jquartz_fired_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| entry_id | character | NOT NULL |
| trigger_name | character | None |
| trigger_group | character | None |
| is_volatile | boolean | None |
| instance_name | character | None |
| fired_time | numeric(18 | None |
| sched_time | numeric(18 | None |
| priority | numeric(9 | None |
| state | character | None |
| job_name | character | None |
| job_group | character | None |
| is_stateful | boolean | None |
| is_nonconcurrent | boolean | None |
| is_update_data | boolean | None |
| requests_recovery | boolean | None |

**Primary Key(s):** entry_id

**Foreign Keys:** None

---

### jquartz_job_details

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| job_name | character | NOT NULL |
| job_group | character | NOT NULL |
| description | character | None |
| job_class_name | character | None |
| is_durable | boolean | None |
| is_volatile | boolean | None |
| is_stateful | boolean | None |
| is_nonconcurrent | boolean | None |
| is_update_data | boolean | None |
| requests_recovery | boolean | None |
| job_data | bytea | None |

**Primary Key(s):** job_name, job_group

**Foreign Keys:** None

---

### jquartz_job_listeners

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| job_name | character | NOT NULL |
| job_group | character | NOT NULL |
| job_listener | character | NOT NULL |

**Primary Key(s):** job_name, job_group, job_listener

**Foreign Keys:** None

---

### jquartz_locks

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| lock_name | character | NOT NULL |

**Primary Key(s):** lock_name

**Foreign Keys:** None

---

### jquartz_paused_trigger_grps

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_group | character | NOT NULL |

**Primary Key(s):** trigger_group

**Foreign Keys:** None

---

### jquartz_scheduler_state

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| instance_name | character | NOT NULL |
| last_checkin_time | numeric(18 | None |
| checkin_interval | numeric(18 | None |

**Primary Key(s):** instance_name

**Foreign Keys:** None

---

### jquartz_simple_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_name | character | NOT NULL |
| trigger_group | character | NOT NULL |
| repeat_count | numeric(18 | None |
| repeat_interval | numeric(18 | None |
| times_triggered | numeric(18 | None |

**Primary Key(s):** trigger_name, trigger_group

**Foreign Keys:** None

---

### jquartz_simprop_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_name | character | NOT NULL |
| trigger_group | character | NOT NULL |
| str_prop_1 | character | None |
| str_prop_2 | character | None |
| str_prop_3 | character | None |
| int_prop_1 | numeric(9 | None |
| int_prop_2 | numeric(9 | None |
| long_prop_1 | numeric(18 | None |
| long_prop_2 | numeric(18 | None |
| dec_prop_1 | numeric(13 | None |
| dec_prop_2 | numeric(13 | None |
| bool_prop_1 | boolean | None |
| bool_prop_2 | boolean | None |

**Primary Key(s):** trigger_name, trigger_group

**Foreign Keys:** None

---

### jquartz_trigger_listeners

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| trigger_name | character | None |
| trigger_group | character | NOT NULL |
| trigger_listener | character | NOT NULL |

**Primary Key(s):** trigger_group, trigger_listener

**Foreign Keys:** None

---

### jquartz_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| sched_name | character | None |
| trigger_name | character | NOT NULL |
| trigger_group | character | NOT NULL |
| job_name | character | None |
| job_group | character | None |
| is_volatile | boolean | None |
| description | character | None |
| next_fire_time | numeric(18 | None |
| prev_fire_time | numeric(18 | None |
| priority | numeric(9 | None |
| trigger_state | character | None |
| trigger_type | character | None |
| start_time | numeric(18 | None |
| end_time | numeric(18 | None |
| calendar_name | character | None |
| misfire_instr | numeric(4 | None |
| job_data | bytea | None |

**Primary Key(s):** trigger_name, trigger_group

**Foreign Keys:** None

---

### label

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| fieldid | numeric(18 | None |
| issue | numeric(18 | None |
| label | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### licenserolesdefault

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| license_role_name | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### licenserolesgroup

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| license_role_name | character | None |
| group_id | character | None |
| primary_group | character(1) | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### listenerconfig

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| clazz | character | None |
| listenername | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### mailserver

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |
| mailfrom | character | None |
| prefix | character | None |
| smtp_port | character | None |
| protocol | character | None |
| server_type | character | None |
| servername | character | None |
| jndilocation | character | None |
| mailusername | character | None |
| mailpassword | character | None |
| cipher_type | character | None |
| istlsrequired | character | None |
| timeout | numeric(18 | None |
| socks_port | character | None |
| socks_host | character | None |
| auth_conf | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### managedconfigurationitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| item_id | character | None |
| item_type | character | None |
| managed | character | None |
| access_level | character | None |
| source | character | None |
| description_key | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### membershipbase

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| user_name | character | None |
| group_name | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### moved_issue_key

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| old_issue_key | character | None |
| issue_id | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### nodeassociation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| source_node_id | numeric(18 | NOT NULL |
| source_node_entity | character | NOT NULL |
| sink_node_id | numeric(18 | NOT NULL |
| sink_node_entity | character | NOT NULL |
| association_type | character | NOT NULL |
| sequence | numeric(9 | None |

**Primary Key(s):** source_node_id, source_node_entity, sink_node_id, sink_node_entity, association_type

**Foreign Keys:** None

---

### nodeindexcounter

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| node_id | character | None |
| sending_node_id | character | None |
| index_operation_id | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### nomenclature_entries

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| original_name | character | None |
| new_name | character | None |
| new_name_plural | character | None |
| timestamp | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### notification

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| event | character | None |
| event_type_id | numeric(18 | None |
| template_id | numeric(18 | None |
| notif_type | character | None |
| notif_parameter | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### notificationinstance

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| notificationtype | character | None |
| source | numeric(18 | None |
| emailaddress | character | None |
| messageid | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### notificationscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### oauthconsumer

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| created | timestamp | None |
| consumername | character | None |
| consumer_key | character | None |
| consumerservice | character | None |
| public_key | text | None |
| private_key | text | None |
| description | text | None |
| callback | text | None |
| signature_method | character | None |
| shared_secret | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### oauthconsumertoken

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| created | timestamp | None |
| token_key | character | None |
| token | character | None |
| token_secret | character | None |
| token_type | character | None |
| consumer_key | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### oauthspconsumer

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| created | timestamp | None |
| consumer_key | character | None |
| consumername | character | None |
| public_key | text | None |
| description | text | None |
| callback | text | None |
| two_l_o_allowed | character | None |
| executing_two_l_o_user | character | None |
| two_l_o_impersonation_allowed | character | None |
| three_l_o_allowed | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### oauthsptoken

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| created | timestamp | None |
| token | character | None |
| token_secret | character | None |
| token_type | character | None |
| consumer_key | character | None |
| username | character | None |
| ttl | numeric(18 | None |
| spauth | character | None |
| callback | text | None |
| spverifier | character | None |
| spversion | character | None |
| session_handle | character | None |
| session_creation_time | timestamp | None |
| session_last_renewal_time | timestamp | None |
| session_time_to_live | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### optionconfiguration

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| fieldid | character | None |
| optionid | character | None |
| fieldconfig | numeric(18 | None |
| sequence | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### os_currentstep

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entry_id | numeric(18 | None |
| step_id | numeric(9 | None |
| action_id | numeric(9 | None |
| owner | character | None |
| start_date | timestamp | None |
| due_date | timestamp | None |
| finish_date | timestamp | None |
| status | character | None |
| caller | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### os_currentstep_prev

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| previous_id | numeric(18 | NOT NULL |

**Primary Key(s):** id, previous_id

**Foreign Keys:** None

---

### os_historystep

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entry_id | numeric(18 | None |
| step_id | numeric(9 | None |
| action_id | numeric(9 | None |
| owner | character | None |
| start_date | timestamp | None |
| due_date | timestamp | None |
| finish_date | timestamp | None |
| status | character | None |
| caller | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### os_historystep_prev

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| previous_id | numeric(18 | NOT NULL |

**Primary Key(s):** id, previous_id

**Foreign Keys:** None

---

### os_wfentry

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| initialized | numeric(9 | None |
| state | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### permissionscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### permissionschemeattribute

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| attribute_key | character | None |
| attribute_value | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### pluginstate

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| pluginkey | character | NOT NULL |
| pluginenabled | character | None |

**Primary Key(s):** pluginkey

**Foreign Keys:** None

---

### pluginversion

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| pluginname | character | None |
| pluginkey | character | None |
| pluginversion | character | None |
| created | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### portalpage

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| username | character | None |
| pagename | character | None |
| description | character | None |
| sequence | numeric(18 | None |
| fav_count | numeric(18 | None |
| layout | character | None |
| ppversion | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### portletconfiguration

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| portalpage | numeric(18 | None |
| portlet_id | character | None |
| column_number | numeric(9 | None |
| positionseq | numeric(9 | None |
| gadget_xml | text | None |
| color | character | None |
| dashboard_module_complete_key | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### priority

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | character | NOT NULL |
| sequence | numeric(18 | None |
| pname | character | None |
| description | text | None |
| iconurl | character | None |
| status_color | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### productlicense

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| license | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### project

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| pname | character | None |
| url | character | None |
| lead | character | None |
| description | text | None |
| pkey | character | None |
| pcounter | numeric(18 | None |
| assigneetype | numeric(18 | None |
| avatar | numeric(18 | None |
| originalkey | character | None |
| projecttype | character | None |
| created | timestamp | None |
| createdby | numeric(18 | None |
| updated | timestamp | None |
| updatedby | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### project_key

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| project_id | numeric(18 | None |
| project_key | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### projectcategory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| cname | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### projectchangedtime

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| project_id | numeric(18 | NOT NULL |
| issue_changed_time | timestamp | None |

**Primary Key(s):** project_id

**Foreign Keys:** None

---

### projectrole

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### projectroleactor

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| pid | numeric(18 | None |
| projectroleid | numeric(18 | None |
| roletype | character | None |
| roletypeparameter | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### projectversion

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| project | numeric(18 | None |
| vname | character | None |
| description | text | None |
| sequence | numeric(18 | None |
| released | character | None |
| archived | character | None |
| url | character | None |
| startdate | timestamp | None |
| releasedate | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertydata

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | oid | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertydate

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertydecimal

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | double | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertyentry

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entity_name | character | None |
| entity_id | numeric(18 | None |
| property_key | character | None |
| propertytype | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertynumber

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertystring

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### propertytext

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| propertyvalue | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_calendars

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | None |
| calendar_name | character | NOT NULL |
| calendar | text | None |

**Primary Key(s):** calendar_name

**Foreign Keys:** None

---

### qrtz_cron_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| trigger_id | numeric(18 | None |
| cronexperssion | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_fired_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | None |
| entry_id | character | NOT NULL |
| trigger_id | numeric(18 | None |
| trigger_listener | character | None |
| fired_time | timestamp | None |
| trigger_state | character | None |

**Primary Key(s):** entry_id

**Foreign Keys:** None

---

### qrtz_job_details

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| job_name | character | None |
| job_group | character | None |
| class_name | character | None |
| is_durable | character | None |
| is_stateful | character | None |
| requests_recovery | character | None |
| job_data | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_job_listeners

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| job | numeric(18 | None |
| job_listener | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_simple_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| trigger_id | numeric(18 | None |
| repeat_count | numeric(9 | None |
| repeat_interval | numeric(18 | None |
| times_triggered | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_trigger_listeners

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| trigger_id | numeric(18 | None |
| trigger_listener | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### qrtz_triggers

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| trigger_name | character | None |
| trigger_group | character | None |
| job | numeric(18 | None |
| next_fire | timestamp | None |
| trigger_state | character | None |
| trigger_type | character | None |
| start_time | timestamp | None |
| end_time | timestamp | None |
| calendar_name | character | None |
| misfire_instr | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### reindex_component

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| request_id | numeric(18 | None |
| affected_index | character | None |
| entity_type | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### reindex_request

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| type | character | None |
| request_time | timestamp | None |
| start_time | timestamp | None |
| completion_time | timestamp | None |
| status | character | None |
| execution_node_id | character | None |
| query | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### remembermetoken

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| created | timestamp | None |
| token | character | None |
| username | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### remotelink

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| globalid | character | None |
| title | character | None |
| summary | text | None |
| url | text | None |
| iconurl | text | None |
| icontitle | text | None |
| relationship | character | None |
| resolved | character(1) | None |
| statusname | character | None |
| statusdescription | text | None |
| statusiconurl | text | None |
| statusicontitle | text | None |
| statusiconlink | text | None |
| statuscategorykey | character | None |
| statuscategorycolorname | character | None |
| applicationtype | character | None |
| applicationname | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### replicatedindexoperation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| index_time | timestamp | None |
| node_id | character | None |
| affected_index | character | None |
| entity_type | character | None |
| affected_ids | text | None |
| versions | text | None |
| operation | character | None |
| filename | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### resolution

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | character | NOT NULL |
| sequence | numeric(18 | None |
| pname | character | None |
| description | text | None |
| iconurl | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### rundetails

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| job_id | character | None |
| start_time | timestamp | None |
| run_duration | numeric(18 | None |
| run_outcome | character(1) | None |
| info_message | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### schemeissuesecurities

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| security | numeric(18 | None |
| sec_type | character | None |
| sec_parameter | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### schemeissuesecuritylevels

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |
| scheme | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### schemepermissions

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| permission | numeric(18 | None |
| perm_type | character | None |
| perm_parameter | character | None |
| permission_key | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### searchrequest

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| filtername | character | None |
| authorname | character | None |
| description | text | None |
| username | character | None |
| groupname | character | None |
| projectid | numeric(18 | None |
| reqcontent | text | None |
| fav_count | numeric(18 | None |
| filtername_lower | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### secret

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| identifier | character | NOT NULL |
| sealed_secret | text | None |
| backend_id | character | None |

**Primary Key(s):** identifier

**Foreign Keys:** None

---

### securityproperty

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| property_key | character | NOT NULL |
| propertyvalue | text | None |

**Primary Key(s):** property_key

**Foreign Keys:** None

---

### sequence_value_item

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| seq_name | character | NOT NULL |
| seq_id | numeric(18 | None |

**Primary Key(s):** seq_name

**Foreign Keys:** None

---

### serviceconfig

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| delaytime | numeric(18 | None |
| clazz | character | None |
| servicename | character | None |
| cron_expression | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### sharepermissions

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entityid | numeric(18 | None |
| entitytype | character | None |
| sharetype | character | None |
| param1 | character | None |
| param2 | character | None |
| rights | numeric(9 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### tempattachmentsmonitor

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| temporary_attachment_id | character | NOT NULL |
| form_token | character | None |
| file_name | character | None |
| content_type | character | None |
| file_size | numeric(18 | None |
| created_time | numeric(18 | None |

**Primary Key(s):** temporary_attachment_id

**Foreign Keys:** None

---

### trackback_ping

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issue | numeric(18 | None |
| url | character | None |
| title | character | None |
| blogname | character | None |
| excerpt | character | None |
| created | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### trustedapp

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| application_id | character | None |
| name | character | None |
| public_key | text | None |
| ip_match | text | None |
| url_match | text | None |
| timeout | numeric(18 | None |
| created | timestamp | None |
| created_by | character | None |
| updated | timestamp | None |
| updated_by | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### upgradehistory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | None |
| upgradeclass | character | NOT NULL |
| targetbuild | character | None |
| status | character | None |
| downgradetaskrequired | character(1) | None |

**Primary Key(s):** upgradeclass

**Foreign Keys:** None

---

### upgradetaskhistory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| upgrade_task_factory_key | character | None |
| build_number | numeric(9 | None |
| status | character | None |
| upgrade_type | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### upgradetaskhistoryauditlog

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| upgrade_task_factory_key | character | None |
| build_number | numeric(9 | None |
| status | character | None |
| upgrade_type | character | None |
| timeperformed | timestamp | None |
| action | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### upgradeversionhistory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | None |
| timeperformed | timestamp | None |
| targetbuild | character | NOT NULL |
| targetversion | character | None |

**Primary Key(s):** targetbuild

**Foreign Keys:** None

---

### userassociation

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| source_name | character | NOT NULL |
| sink_node_id | numeric(18 | NOT NULL |
| sink_node_entity | character | NOT NULL |
| association_type | character | NOT NULL |
| sequence | numeric(9 | None |
| created | timestamp | None |

**Primary Key(s):** source_name, sink_node_id, sink_node_entity, association_type

**Foreign Keys:** None

---

### userbase

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| username | character | None |
| password_hash | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### userhistoryitem

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| entitytype | character | None |
| entityid | character | None |
| username | character | None |
| lastviewed | numeric(18 | None |
| data | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### userpickerfilter

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| customfield | numeric(18 | None |
| customfieldconfig | numeric(18 | None |
| enabled | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### userpickerfiltergroup

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| userpickerfilter | numeric(18 | None |
| groupname | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### userpickerfilterrole

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| userpickerfilter | numeric(18 | None |
| projectroleid | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### versioncontrol

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| vcsname | character | None |
| vcsdescription | character | None |
| vcstype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### votehistory

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| votes | numeric(18 | None |
| timestamp | timestamp | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### workflowscheme

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| name | character | None |
| description | text | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### workflowschemeentity

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| scheme | numeric(18 | None |
| workflow | character | None |
| issuetype | character | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### worklog

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| id | numeric(18 | NOT NULL |
| issueid | numeric(18 | None |
| author | character | None |
| grouplevel | character | None |
| rolelevel | numeric(18 | None |
| worklogbody | text | None |
| created | timestamp | None |
| updateauthor | character | None |
| updated | timestamp | None |
| startdate | timestamp | None |
| timeworked | numeric(18 | None |

**Primary Key(s):** id

**Foreign Keys:** None

---

### worklog_version

**Columns:**

| Column Name | Data Type | Constraints |
|-------------|-----------|-------------|
| worklog_id | numeric(18 | NOT NULL |
| parent_issue_id | numeric(18 | None |
| update_time | timestamp | None |
| index_version | numeric(18 | None |
| deleted | character(1) | None |

**Primary Key(s):** worklog_id

**Foreign Keys:** None

---

