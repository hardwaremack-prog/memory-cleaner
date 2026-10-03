Memory Cleaner v1.0: portable RAM optimizer for Windows
=========================================================

Just run MemoryCleaner.exe. No install needed. Windows asks for administrator
rights because clearing system memory lists requires them.
Needs .NET Framework 4.8, which is built into Windows 10 and 11.

MEMORY AREAS (hover each one in the app for details)
  Working sets             - trims every process's working set
  System file cache        - trims the system file cache
  Modified file cache      - flushes write caches of all fixed drives
  Modified page list       - writes modified pages to disk
  Standby list (low prio)  - purges low-priority cached pages only
  Standby list             - purges all cached pages (frees the most RAM)
  Combined page list       - merges identical pages (Windows 10+)
  Registry cache           - flushes registry data from RAM (Windows 8.1+)

FEATURES
  - Live RAM and committed-memory usage
  - Auto-optimize every N hours, and/or when RAM usage goes above N%
  - Tray icon showing RAM %; left-click to open, right-click for menu
  - Global hotkey (default Ctrl+Alt+M). Click the box and press a new combo
  - Start with Windows (elevated logon task in Task Scheduler, no UAC prompt)
  - Settings saved to MemoryCleaner.ini next to the exe (portable)

COMMAND LINE
  MemoryCleaner.exe /optimize   optimize once with saved areas, then exit
  MemoryCleaner.exe /tray       start hidden in the system tray

NOTE: The exe is unsigned, so Windows SmartScreen may warn on first run.
Click "More info" then "Run anyway". Full source code is included.

BUILD FROM SOURCE (on Windows)
  dotnet build -c Release
