# diamondberry

Just a code that formats Markdown in GdC and promises to do more while being transparently open source.
<br><sub><sub><sub>(Who cares about the frickin description??)</sub></sub></sub><br>
<img src="https://img.shields.io/badge/Javascript-black?logo=javascript" width="auto" height="50"><img src="https://img.shields.io/badge/CSS-black?logo=css" width="auto" height="50">
# Desktop: Chrome/Firefox/<sub>[any other Chromium-based/Firefox-based browser]</sub>
<a href="https://tampermonkey.net">
  <img src="https://img.shields.io/badge/Get%20Tampermonkey-orange?logo=tampermonkey" width="auto" height="50">
</a><br>
<a href="https://diamondberry.run/diamondberry.user.js">
  <img src="https://img.shields.io/badge/Tampermonkey-Install-orange?logo=tampermonkey" width="auto" height="50">
</a><br>
<a href="https://greasyfork.org/fr-CA/scripts/526194-diamondberry">
  <img src="https://img.shields.io/badge/TpMk-Install_v1.7_via_Greasy_Fork-orange?logo=tampermonkey" width="auto" height="50">
</a>

### **[Are you on a mobile device?](#mobile-android)**
### Supported browsers 
(for reference only, open an issue if you find problems, can be updated later)
#### Chromium-based browsers
- Google Chrome v117.0+
- Microsoft Edge v117.0+
- Brave v1.57+
- Opera v102.0+
- Vivaldi v6.2+

#### Firefox-based browsers
- Mozilla Firefox v118.0+
- LibreWolf v118.0+
- Waterfox vG5.1.10+

### Tested on
- [x] Windows/Chrome v133.0.6943.59
- [x] Windows/Opera One v116.0.5366.71
- [x] Android/Edge v133.0.3065.54
- [ ] other browsers (will update later)

## Bookmarklet
<a href="javascript:(function(){var script = document.createElement('script');script.src = 'https://diamondberry.run/diamondberry.user.js';script.type = 'text/javascript';document.body.appendChild(script);})();">
  <img src="https://img.shields.io/badge/Add_to_your_favorites-grey?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMjYuOSAyNS42NSIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMjYuOSAyNS42NSIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+PHN0eWxlIHR5cGU9InRleHQvY3NzIj4uc3Qwe2NsaXAtcGF0aDp1cmwoI1NWR0lEXzJfKTt9IC5zdDF7ZmlsbDojRkZENDAxO308L3N0eWxlPjxnPjxnPjxkZWZzPjxwYXRoIGlkPSJTVkdJRF8xXyIgZD0iTTE0LjEsMC40M2wzLjQ0LDguMDVsOC43MiwwLjc4YzAuMzksMC4wMywwLjY3LDAuMzcsMC42NCwwLjc2Yy0wLjAyLDAuMTktMC4xLDAuMzUtMC4yNCwwLjQ3bDAsMCBsLTYuNiw1Ljc2bDEuOTUsOC41NGMwLjA5LDAuMzgtMC4xNSwwLjc1LTAuNTMsMC44NGMtMC4xOSwwLjA0LTAuMzksMC0wLjU0LTAuMWwtNy41LTQuNDhsLTcuNTIsNC41IGMtMC4zMywwLjItMC43NiwwLjA5LTAuOTYtMC4yNGMtMC4xLTAuMTYtMC4xMi0wLjM1LTAuMDgtMC41MmgwbDEuOTUtOC41NGwtNi42LTUuNzZjLTAuMjktMC4yNS0wLjMyLTAuNy0wLjA3LTAuOTkgQzAuMyw5LjM1LDAuNDgsOS4yOCwwLjY2LDkuMjdsOC43LTAuNzhsMy40NC04LjA2YzAuMTUtMC4zNiwwLjU2LTAuNTIsMC45Mi0wLjM3QzEzLjksMC4xMywxNC4wMywwLjI3LDE0LjEsMC40M0wxNC4xLDAuNDMgTDE0LjEsMC40M3oiLz48L2RlZnM+PGNsaXBQYXRoIGlkPSJTVkdJRF8yXyI+PHVzZSB4bGluazpocmVmPSIjU1ZHSURfMV8iIHN0eWxlPSJvdmVyZmxvdzp2aXNpYmxlIi8+PC9jbGlwUGF0aD48ZyBjbGFzcz0ic3QwIj48ZGVmcz48cmVjdCBpZD0iU1ZHSURfM18iIHg9Ii0wLjA4IiB5PSItMC4xIiB3aWR0aD0iMjcuMDEiIGhlaWdodD0iMjUuODUiLz48L2RlZnM+PGNsaXBQYXRoIGlkPSJTVkdJRF80XyI+PHVzZSB4bGluazpocmVmPSIjU1ZHSURfM18iIHN0eWxlPSJvdmVyZmxvdzp2aXNpYmxlIi8+PC9jbGlwUGF0aD48ZyBzdHlsZT0iY2xpcC1wYXRoOnVybCgjU1ZHSURfNF8pIj48aW1hZ2Ugc3R5bGU9Im92ZXJmbG93OnZpc2libGUiIHdpZHRoPSI2NCIgaGVpZ2h0PSI1NyIgeGxpbms6aHJlZj0iZGF0YTppbWFnZS9qcGVnO2Jhc2U2NCwvOWovNEFBUVNrWkpSZ0FCQWdFQWxnQ1dBQUQvN0FBUlJIVmphM2tBQVFBRUFBQUFIZ0FBLys0QUlVRmtiMkpsQUdUQUFBQUFBUU1BIEVBTUNBd1lBQUFKSUFBQUNzQUFBQTRiLzJ3Q0VBQkFMQ3dzTUN4QU1EQkFYRHcwUEZ4c1VFQkFVR3g4WEZ4Y1hGeDhlRnhvYUdob1ggSGg0akpTY2xJeDR2THpNekx5OUFRRUJBUUVCQVFFQkFRRUJBUUVBQkVROFBFUk1SRlJJU0ZSUVJGQkVVR2hRV0ZoUWFKaG9hSEJvYSBKakFqSGg0ZUhpTXdLeTRuSnljdUt6VTFNREExTlVCQVAwQkFRRUJBUUVCQVFFQkFRUC9DQUJFSUFEd0FRd01CSWdBQ0VRRURFUUgvIHhBQ2lBQUFEQVFFQkFRQUFBQUFBQUFBQUFBQUFCQVVDQVFNR0FRQUNBd0VBQUFBQUFBQUFBQUFBQUFBQUF3UUZCZ0lRQUFJQUJRTUUgQXdBQUFBQUFBQUFBQUFBUkFRSURCQVVUSkJVU0l6TWxNaFEwRVFBQkFRWUdBUVVBQUFBQUFBQUFBQUFCQUJBZ0VYR2hNckVDRWtKeSBBekVoVVNJVEZCSUFBZ0FEQkFnSEFRQUFBQUFBQUFBQUFRSUFFQU1oTWFFaVVYR0JrYkhSTXRJUllSSnlrak56UXYvYUFBd0RBUUFDIEVRTVJBQUFBKzY4U2ZSeWFCUElyS0JQQW9la3RsM05NRFFSRXAxQ2JtcCtqSkFicnVBTnNwdFNPS3dHc3JrSmxLWG5MSFJrZ3UwWkEgMDBtMi9peUJxcXVkS3RvMEZpa09rTnlRNkFrNTFoNjZJR2tyUC8vYUFBZ0JBZ0FCQlFDL3Y3aWpjY3JlSEszaGJaRzZucm1VaHUwSSBzNGJreWNOMmhGbkRjbVJrbGpjNmNocHlGckpMQzRQLzJnQUlBUU1BQVFVQXBVcEpwTkNtYUZNbm95UWxMZUhiUWlyRHRsdER0SVJXIGgyeTJtakNsMVJPcUpWbWpwbi8vMmdBSUFRRUFBUVVBcjE0VUljakljakljakljakljakljaklVYnlXdE9aSDRNWXhqR1dINkRKZkIgakdNWXpIL29NcDQyTVl4ak1kSGNtVjhiR01ZeG1OanVqTCtOakdNWXpHUjNSbVBFeGpHTVppLzFsLzhBVjZQVW5xVDFKNms5U2VwTCBMNkd1Zi8vYUFBZ0JBZ0lHUHdCcWROZ0ZBWCtRYnhIV1BpSTZ4OFJGTkdjRlhjQTVSY1pQcVhoT2oraXlmVXZDZEg5Rmt4TlJGc1d3ICtyUjVBeDl0UGMvYkgyMDl6OXNVaUtpSE90Z0Rkc3YvMmdBSUFRTUNCajhBQkl0aTdHTHNZSkF1RWh0bTN0TWh0bS90TWhsSnZ1OE8gY2REWWM0Nkd3NXcrVmhsT2puTC8yZ0FJQVFFQkJqOEFCSUppWWVpc0tzS3NLc0tzS3NLMERLUVlSaXpKTXZpUlprbWNIeElzeVRPRCA0a1dkY3pnK0pGblh5T0Q0NGxuWHlPRDQ0bG1UOU1kTWZqcDkxdnF0OVZ2cXQ5VnZxdDlVUHo2dnNnZlBpRFAvMlE9PSIgdHJhbnNmb3JtPSJtYXRyaXgoMC40OCAwIDAgLTAuNDggLTEuMTM5OSAyNi43NDY5KSIvPjwvZz48L2c+PC9nPjxwYXRoIGNsYXNzPSJzdDEiIGQ9Ik0xNC4xLDAuNDNsMy40NCw4LjA1bDguNzIsMC43OGMwLjM5LDAuMDMsMC42NywwLjM3LDAuNjQsMC43NmMtMC4wMiwwLjE5LTAuMSwwLjM1LTAuMjQsMC40N2wwLDBsLTEuMTgsMS4wMyBjLTMuMjEsMS4xMS03LjQyLDEuNzgtMTIuMDMsMS43OGMtNC42MSwwLTguODMtMC42Ny0xMi4wMy0xLjc4bC0xLjE4LTEuMDNjLTAuMjktMC4yNS0wLjMyLTAuNy0wLjA3LTAuOTkgQzAuMyw5LjM1LDAuNDgsOS4yOCwwLjY2LDkuMjdsOC43LTAuNzhsMy40NC04LjA2YzAuMTUtMC4zNiwwLjU2LTAuNTIsMC45Mi0wLjM3QzEzLjksMC4xMywxNC4wMywwLjI3LDE0LjEsMC40M0wxNC4xLDAuNDMgTDE0LjEsMC40M3oiLz48L2c+PC9zdmc+" width="auto" height="50">
</a><br>

# Mobile: Android
<a href="https://play.google.com/store/apps/details?id=com.xbrowser.play">
  <img src="https://img.shields.io/badge/Get_XBrowser-blue?logo=googlechrome&logoColor=white" width="auto" height="50">
</a><br>
<a href="https://diamondberry.run/diamondberry.user.js">
  <img src="https://img.shields.io/badge/Xbrowser-Install-blue?logo=googlechrome&logoColor=white" width="auto" height="50">
</a>
<br><br>
<a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox" style="display:flex;">
  <img src="https://img.shields.io/badge/Get_Firefox-orange?logo=firefox&logoColor=white" width="auto" height="50">
</a><br>
<a href="https://addons.mozilla.org/en-CA/firefox/addon/tampermonkey/" style="display:flex;">
  <img src="https://img.shields.io/badge/Get_Tampermonkey-orange?logo=firefox&logoColor=white" width="auto" height="50">
</a><br>
<a href="https://diamondberry.run/diamondberry.user.js" style="display:flex;">
   <img src="https://img.shields.io/badge/Tampermonkey-Install-orange?logo=firefox&logoColor=white" width="auto" height="50">
</a>
<br><br>
<a href="https://play.google.com/store/apps/details?id=com.microsoft.emmx" style="display:flex;">
  <img src="https://img.shields.io/badge/Get_Edge-white?logo=googlechrome&logoColor=green" width="auto" height="50">
</a>

Go to <img src="https://www.hostedredmine.com/attachments/download/205172/menu.png" alt="Menu" height="15">Menu and then tap on <img src="https://i.ibb.co/dwMWRDVJ/puzzle-1.png" alt="Extensions" height="15">Extensions. From there, install Tampermonkey. **Only then**, click below to install the script.
<!--<a href="https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd" style="display:flex;">
  <img src="https://img.shields.io/badge/Get_Tampermonkey-orange?logo=googlechrome&logoColor=green" width="auto" height="50">
</a>-->
<a href="https://diamondberry.run/diamondberry.user.js" style="display:flex;">
   <img src="https://img.shields.io/badge/Tampermonkey-Install-orange?logo=googlechrome&logoColor=green" width="auto" height="50">
</a>
<br>
