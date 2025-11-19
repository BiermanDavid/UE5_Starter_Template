# UE5 Multiplayer Template - Development Roadmap

A living Unreal Engine 5 multiplayer template that will be released publicly when it reaches a more advanced stage. Built with Steam integration and designed to provide a solid foundation for multiplayer game development.

## 🚀 Current Features

- **Steam Subsystem Integration**: Fully implemented Steam API for multiplayer functionality
- **Basic Server Browser**: Functional server discovery and listing from various YouTube tutorials
- **Lobby System**: Automatic level loading when maximum lobby size is reached
- **Settings System**: Working save settings for FOV, Windowed mode, graphics, Bloom, Motion Blur, and Vsync.

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
