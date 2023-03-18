# custom-sandflies
A personal collection of custom sandflies. They likely need tuning for your particular environment. The _credential_leak_ sandflies look for typical patterns where processes or shell history contain credentials; typical places where a threat actor already present on a system will look to further their lateral movement.
# process_command_credential_leak
Looks through the current process list to see if command line arguments leak credentials.
# process_cron_credential_leak
Looks through _cron_ and _at_ jobs to see if commands line arguments leak credentials (become visible in the process list).
# user_history_credential_leak
Looks through users' _.bash_history_ files to see if there is a credential leak.
# end note
I have no affiliation with Sandfly Security (https://sandflysecurity.com). I simply like their product.
# licence
BSD Simplified 2-clause license.
