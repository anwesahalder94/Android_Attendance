Upasthiti Android
This Repository is for Upasthiti Android. Please follow the below instructions before using the following repository:

------------------------------------------------------------------------------------------------------
For Development Team:
------------------------------------------------------------------------------------------------------

Replace the tags with the needed values before starting development, please do not push the changes to the specified tags to the stash as this will affect the build plan

In BuildConstants(app\src\main\java\com\oit\upasthiti\util\BuildConstants.kt)

api_protocol
api_base_url
user_login_sub_url
user_fetch_admin_contact_details_sub_url
user_add_attendence_sub_url
user_logout_sub_url
user_update_password_sub_url
user_get_attendence_sub_url
user_get_holidays_sub_url

Replace the values to the above mentioned keys with their environment specific values (Refer below for values according to their environment).

------------------------------------------------------------------------------------------------------
For Systems/Infrastructure Team:
------------------------------------------------------------------------------------------------------

Please follow the below instructions for building the build plan
(the values are provided in "Key":"Value" format, replace the key with the provided value in the build plan)

DEV Release:

Tags which needs to be changed in BuildConstants, below is the file location in project structure:
-- app\src\main\java\com\oit\upasthiti\util\BuildConstants.kt

api_protocol ==> http://
api_base_url ==> upasthiti-api.oitsystems.com
user_login_sub_url ==> /v1/auth/login
user_fetch_admin_contact_details_sub_url ==> /v1/admin/contact
user_add_attendence_sub_url ==> /v1/user/attendance/save
user_logout_sub_url ==> /v1/auth/logout
user_update_password_sub_url ==> /v1/user/password/update
user_get_attendence_sub_url ==> /v1/user/attendance/{month}/{year}
user_get_holidays_sub_url ==> /v1/user/holidays/

------------------------------------------------------------------------------------------------------

QC Release:

Tags which needs to be changed in BuildConstants, below is the file location in project structure:
-- app\src\main\java\com\oit\upasthiti\util\BuildConstants.kt

api_protocol ==> To be Replaced when QC URL is provided
api_base_url ==> To be Replaced when QC URL is provided
user_login_sub_url ==> /v1/auth/login
user_fetch_admin_contact_details_sub_url ==> /v1/admin/contact
user_add_attendence_sub_url ==> /v1/user/attendance/save
user_logout_sub_url ==> /v1/auth/logout
user_update_password_sub_url ==> /v1/user/password/update
user_get_attendence_sub_url ==> /v1/user/attendance/{month}/{year}
user_get_holidays_sub_url ==> /v1/user/holidays/
