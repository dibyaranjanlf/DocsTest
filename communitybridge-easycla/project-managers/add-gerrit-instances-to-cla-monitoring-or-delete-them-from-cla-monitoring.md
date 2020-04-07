# Add Gerrit Instances to CLA Monitoring or Delete Them From CLA Monitoring

Complete the form fields, and click **SUBMIT**.

**Gerrit Instance Name** - Name of the Gerrit Instance

**Gerrit Instance URL** - URL of the Gerrit Instance

**ICLA Group ID** - An existing LDAP Group ID for Individual CLAs

**CCLA Group ID** - An existing LDAP Group ID for Corporate CLAs

​![CLA Add Gerrit Instance](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUptZOvZe2VuSJqlQ%2F-LuXUq_hSzrmzh8uzOmD%2Fcla-add-gerrit-instance.png?generation=1574684290372051&alt=media)​

**Notes**

* Contact the Linux Foundation IT if you do not know the LDAP Group IDs.
* One or both LDAP groups must exist for you to be able to create a Gerrit instance. If a group does not exist, an error message appears and you are prevented from creating a Gerrit instance.

The CLA Management Console lists the instance under Gerrit Instances.

​![CLA Gerrit Instances](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUptZOvZe2VuSJqlQ%2F-LuXUq_jEi5Jecbx9Jod%2Fcla-gerrit-instances.png?generation=1574684290393611&alt=media)​

The CLA Management Console presents a CLA block of code:

`[contributor-agreement "{ICLA-Name} “]`

`description = ICLA for Linux Foundation`

`agreementUrl = {URL }`

`accepted = group {Group-Name}`

`[contributor-agreement "{CCLA-Name} “]`

`description = CCLA for Linux Foundation`

`agreementUrl = {URL }`

`accepted = group {Group-Name}`

