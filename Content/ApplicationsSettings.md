# Applications Settings

### Applications" Settings Group

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications.

![](https://xanasoft.com/wp-content/uploads/2020/10/ApplicationsSettings.png)

This group of settings pages offers quick configuration of Sandboxie for use with other applications, particularly the various well-known Web browsers and email programs, but also some third-party applications that are known to require special configuration in Sandboxie.

* * *

### Web Browser

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications > Web Browser

This settings sub-group is itself divided into three sub-groups:


#### Internet Explorer
![](https://xanasoft.com/wp-content/uploads/2020/10/WebBrowserSettings1.png)</td>
See also:   [Internet Explorer Tips](InternetExplorerTips)

#### Firefox
![](https://xanasoft.com/wp-content/uploads/2020/10/WebBrowserSettings2.png)
See also:  [Firefox Tips](FirefoxTips)

#### Other Browsers
![](https://xanasoft.com/wp-content/uploads/2020/10/WebBrowserSettings3.png)</td>


This settings page offers quick configuration for the following browsers: Internet Explorer, Mozilla Firefox and SeaMonkey, the Opera Web browser, Maxthon 2, and Google Chrome.

Select (highlight) the desired configuration and click the _Add_ button to enable it for this sandbox. If you use non-default locations for the data (profile) folders used by your Web browsers, make sure to also visit the [Applications > Folders](ApplicationsSettings#folders) settings page to specify the alternate locations.

Two special settings on the Internet Explorer settings page:

*   Save outside sandbox: History of search strings and invoked commands. For detailed information, see [Sandboxie Ini](SandboxieIni) setting: [OpenProtectedStorage](OpenProtectedStorage).
*   Save outside sandbox: Account information for Hotmail and Messenger. For detailed information, see [Sandboxie Ini](SandboxieIni) setting: [OpenCredentials](OpenCredentials).
*   See also [Save Outside Sandbox in Internet Explorer Tips](InternetExplorerTips#SaveOutsideSandbox) for more information and recommendations.

* * *

#### Email Reader

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications > Email Reader

![](https://xanasoft.com/wp-content/uploads/2020/10/EmailReaderSettings.png)  

This settings page offers quick configuration for the following email programs:

*   Outlook Express
*   Office Outlook
*   Windows Vista Mail
*   Windows Live Mail
*   Mozilla Thunderbird
*   Mozilla SeaMonkey
*   Opera Mail
*   IncrediMail
*   Eudora
*   The Bat!

Select (highlight) the desired configuration and click the _Add_ button to enable it for this sandbox.

You may also need to tell Sandboxie where your mailbox data files reside, in the following cases:

*   If your mailbox resides in a non-default or non-standard location.
*   If you use the Eudora or The-Bat! email software.

To do that, open [Sandbox Settings > Applications > Folders](ApplicationsSettings.html#folders), select your email software from the drop-down list, and then select a folder location to be associated with it.

After completing the email configuration, you may want to test it, to make sure that even when running under Sandboxie, new emails are not lost when you delete the sandbox. To do that, follow the steps outlined in [Test Email Configuration](TestEmailConfiguration.html).

If your email program is not known to Sandboxie, you can use [Sandbox Settings > Resource Access > File Access > Direct Access](ResourceAccessSettings.html#file) to explicitly add direct access to the folder containing your mailbox data files.

See also message [SBIE2212](SBIE2212.html), [Email Protection](EmailProtection.html), and [FAQ Email](FAQ_Email.html).

* * *

### <a name="misc" id="misc"></a>Miscellaneous

The following settings pages are used to enable configurations for third-party software, categorized by subject. There are settings pages for PDF and printing software, for password and security software, for desktop utilities and other miscellaneous programs and settings.

Select (highlight) the desired configuration and click the _Open Web Site_ button to visit the vendor Web site for a particular program recognized by Sandboxie.

Select (highlight) the desired configuration and click the _Add_ button to enable it for this sandbox. In some cases, you also specify the locations of the data files used by the third-party software. Use [Applications > Folders](ApplicationsSettings#folders) settings page to specify the alternate locations.

* * *

#### Local

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications > Local

![](https://xanasoft.com/wp-content/uploads/2020/10/LocalApplicationsSettings.png)

Use this settings page to enter your own custom settings as an application configuration package that can be easily enabled or disabled for a particular sandbox.

For more information about designing your own application configuration packages, or templates, consult the _Templates.ini_ file in the Sandboxie installation folder.

* * *

#### Folders

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications > Folders

![](https://xanasoft.com/wp-content/uploads/2020/10/FolderApplicationsSettings.png)

Use this settings page to specify any alternate (non-default) folder locations for the data files used by applications for which you have enabled in (or add to) the sandbox.

First, select (highlight) the desired application, then click the _Add_ button to specify the alternate location.

* * *

#### Accessibility Settings

[Sandboxie Control](SandboxieControl) > [Sandbox Settings](SandboxSettings) > Applications > Accessibility

![](https://xanasoft.com/wp-content/uploads/2020/10/AccessibilitySettings.png)

This settings page offers quick configuration for the following screen reading programs:

*   JAWS
*   NVDA
*   Windows-Eyes
*   System Access

Accessibility support in Windows allows any program to provide hints and information about the content it is displaying. Screen reader software typically uses these hints to offer more detail about the content of the screen.

Normally, the isolation of Sandboxie prevents the screen reader from accessing the accessibility hints provided by the sandboxed program.

Enabling the setting will weaken the protection of the Sandboxie in order to permit two-way communication between the screen reader program and the sandboxed program.

You may wish to enable [Sandbox Settings > Restrictions > Drop Rights](RestrictionsSettings#drop) to compensate for the lost protection.