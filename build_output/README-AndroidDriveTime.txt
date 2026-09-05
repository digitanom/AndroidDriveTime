AndroidDriveTime test build

Timestamp mapping:
- CreationTime = Android birth time when available, otherwise mtime
- LastWriteTime = Android mtime
- LastAccessTime = Android atime
- ChangeTime: setting ON -> Android ctime; setting OFF -> Android mtime
- Current precision: whole seconds

IMPORTANT:
AndroidDriveTime.exe and dokan2.dll are a matched pair.
Keep this dokan2.dll beside AndroidDriveTime.exe.
Do NOT replace the installed Dokan kernel driver (dokan2.sys).
