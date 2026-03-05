# Steam-Playtime-Monitor

A lightweight tool that monitors your active processes and tracks playtime for specific games or applications. 
Perfect for keeping an eye on how much time you spend in-game, even for non-Steam titles or apps that don't track time natively.

# How to use
<ol>
  <li>Launch the <strong>Playtime Monitor</strong> before starting your game.</li>
  <li>The program will automatically detect and track the <strong>active processes</strong> you have specified.</li>
  <li>View your accumulated <strong>playtime logs</strong> directly in the application interface.</li>
  <li>All data is saved locally, so you can track your progress over multiple sessions.</li>
</ol>

# Build
* Put `playtime_monitor.py` and your `.ico` file in the same folder.
* You need **PyInstaller** and any required dependencies for this to work. Install them via pip:
  `pip install PyInstaller`
* Run the following command to build the executable:
  `py -m PyInstaller --noconsole --onefile --icon=monitor.ico playtime_monitor.py`
* After building, your executable will be in the **dist** folder.

### 🎮 Twitch
Catch me live on **[My Twitch Channel](https://www.twitch.tv/panmenelg)**! I stream my development process and some gameplay. Feel free to drop by, and say hi!

### 💬 Discord
Join the community on **[My Discord Server](https://discord.gg/TWÓJ_LINK)**! It's the best place to get updates on my projects, ask for help, or just hang out. Feel free to drop by, and say hi!
