# gpologging
Group Policy logging ADMX/ADML file for various GP troubleshooting logs

This ADMX and accompany English language ADML enable a variety of client-side debug logging for Group Policy processing.

You can enable this logging by copying the ADMX file to your ADMX Central Store (or local store at %windir%\policydefinitions and the accompanying ADML file to the en-us folder under the Central Store. Once added, open GP Editor on a GPO and you will see the new policies under Computer Configuration\Policies\Administrative Templates\System\Group Policy Logging\Logging.

Note that because of the registry locations underlying these logging settings, they WILL tattoo the registry on a system where they are applied (i.e. you will have to explicit undo or remove the entries after applying them). 
