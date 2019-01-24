# Email Dotfiles <br>
.muttrc-mcc and .pinerc configured for MCC Office 365 work email.<br>
.muttrc-gmail for gmail.<br>

**Mutt** <br>
*Work Email*<br>
Download and copy .mutt and .muttrc-mcc to $HOME dir.<br>
Make changes as indicated in comments in .muttrc-mcc file. <br>
Use mutt -F .muttrc-mcc <br>
*Gmail*<br>
Followed instructions for 2FA from http://nidkil.me/2018/01/18/setting-up-mutt-to-send-mail-using-gmail-with-2fa-set/ <br>
Use mutt -F .muttrc-gmail <br>

**Alpine** <br>
Download and copy .pinerc file to $HOME dir. <br>
Make changes as indicated in comments in .pinerc file. <br>
For smtp to work, in Alpine go to choose [S]etup, then [C]onfig. <br>
Move down to the Customized Headers option <br>
then enter, From: "Full Name" <myusername@mccneb.edu> <br>

NOTE: Do not have saved password working with alpine.

