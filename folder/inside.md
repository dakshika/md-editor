---
sidebar_position: 5
sidebar_class_name: green
sidebar_custom_props:
  gtn_page_auth:
    auth: true
    groups:
      - sales
      - administrator
---

# Error Codes

GTN uses standard HTTP response codes to indicate the success or failure of an API request.

*List of Error Messages*

Error | Http Status | Reject Code | Description
---------|----------|---------|---------
SUCCESS | 200	| 0 | Success
INVALID_REQUEST | 200	| 1001	| invalid request. please check request again.
ERROR_VERIFY_JWT | 200	| 1002	| Error in verifying jwt
KEYS_NOT_CONFIGURED_PROPERLY | 200	| 1003	| Public and Private Keys not configured properly
USER_NOT_FOUND | 200	| 1004	| User not found
SECURITY_KEY_CONFIG_ISSUE | 200	| 1005	| Security Keys are not configured properly
INVALID_SERVER_ACCESS_TOKEN | 200	| 1006	| Invalid Server access token
EXPIRED_TOKEN | 200	| 1007	| Expired Token
TOKEN_VERIFICATION_ISSUE | 200	| 1008	| Invalid Token
INVALID_LOGIN_CREDENTIALS | 200	| 1009	| Invalid login credentials
USERNAME_NOT_UNIQUE | 200	| 1010	| Username is not unique
USER_VALIDATION_FAILED | 200	| 1011	| User validation failed
NO_ORDERS | 200	| 1012	| No orders found
INCORRECT_PASSWORD | 200	| 1013	| Incorrect password
IN_SUFFICIENT_DETAILS_IN_ASSERTION | 200	| 1014	| Insufficient details in assertion
EXCHANGE_ACCOUNT_ALREADY_DELETED | 200	| 1015	| Exchange account is already deleted
INVALID_INSTITUTION | 200	| 1016	| Invalid institution
INVALID_CUSTOMER_NUMBER | 200	| 1017	| Invalid Customer Number
ACC_NOT_FOUND | 200	| 1110	| Account cannot be found
CUSTOMER_NOT_FOUND | 200	| 1111	| Customer cannot be found
CASH_ACCOUNT_NOT_FOUND | 200	| 1112	| Cash account cannot be found
SECURITY_ACCOUNT_NOT_FOUND | 200	| 1113	| security account cannot be found
EXCHANGE_ACCOUNT_NOT_FOUND | 200	| 1114	| Exchange account cannot be found
BANK_ACC_NOT_FOUND | 200	| 1115	| Bank account number
MASTER_ACCOUNT_NOTE_FOUND | 200	| 1116 | Master Account not found for the institution
AUTHENTICATION_FAILED | 200	| 1120 | Authentication failed
ORD_REF_NUM_ALREADY_EXIST | 200	| 1121 | order reference number is already exist in the system.
NO_STOCK_TRANS_DETAILS | 200	| 1122 | no stock transactions found.
RETRY | 200	| 1123 | server is busy, please retry again.
ALREADY_EXISTING_REFERENCE_NUMBER | 200	| 1125 | Customer is already created with the referenceNumber
SYSTEM_ERROR_CODE	| 200	| 999 | System Error
UNAUTHORIZED_ACCESS	| 401	| - | User has no access
UNAUTHORIZED_ACCESS	| 401	| 1007 | token expired
UNAUTHORIZED_ACCESS	| 401	| 1008 | invalid token
TIMEOUT	| 408	| - | Failed because of timeout
