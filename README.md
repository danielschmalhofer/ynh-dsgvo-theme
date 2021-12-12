# ynh-dsgvo-theme
DSGVO Theme for YunoHost

1.  install a app that hosts the dsgvo info


2. modify the /usr/share/ssowat/portal/login.html file with the editor of your choice (nano will do):
add the line & change the LINK TO YOUR APP like https://myurl.com
<input type="button" onclick="window.location.href='LINK TO APP';" value="Impressum & DSGVO" class="btn dsgvo-btn large-btn"/>

3. change the css to the provided:
