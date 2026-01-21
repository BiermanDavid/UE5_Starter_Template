# UE5 Multiplayer Template - Development Roadmap

A living Unreal Engine 5 multiplayer template that will be released publicly when it reaches a more advanced stage. Built with Steam integration and designed to provide a solid foundation for multiplayer game development.

## 🚀 Current Features

- **Steam Subsystem Integration**: Fully implemented Steam API for multiplayer functionality
- **Basic Server Browser**: Functional server discovery and listing from various YouTube tutorials
- **Lobby System**: Automatic level loading when maximum lobby size is reached
- **Settings System**: Working save settings for FOV, Windowed mode, graphics, Bloom, Motion Blur, and Vsync.

## Settings Panel

![Settings Panel](https://github.com/BiermanDavid/UE5_Starter_Template/blob/NewMaster/readme/SettingsPanel.png)

The settings panel graphic above shows an example of a pause menu **without a background image**, featuring **hover detection** on each setting. When a setting is highlighted, the details panel updates to correspond to that specific game option.  

This functionality is achieved by creating **individual widget blueprints** combined with **widget switchers**.  
The background can be customized to use a **simple blur**, a **standard image**, or even a combination of both.


## 🛠️ Development Roadmap

### Server Browser Improvements
- [ ] Prevent full servers from being joined
- [ ] Server browser refreshes automatically on open

### Lobby System Enhancements  
- [ ] Implement ready system controlled by server host
- [ ] Replace automatic level loading with host-controlled game start

### Host Migration System
- [ ] Implement seamless host migration
- [ ] Send all players to lobby during migration
- [ ] Select highest ping player to become new host

### Settings System Expansion
- [ ] Create universal widgets for different settings panels
- [ ] Add voice chat settings (volume, push to talk)
- [ ] Implement sensitivity settings
- [ ] Add audio controls (master volume, music, SFX, voice chat volume)
- [ ] Build comprehensive keybinding system for keyboard controls
