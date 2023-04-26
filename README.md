# minecraft-forge-mod-plan
> Minecraft Forge modding plan

## color-component
- Current Version (MC Version) : 1.0.2 (1.19.3)
- Status : Released
- modid : color_component
- Description : Support net.minecraft.network.chat.Component class hex color Style & Animation Color
- Project Visibility : Private
- Repository : Personal Gitlab
- need mod : nothing

## asyu-mod-lib
- Current Version (MC Version) : 1.0.1 (1.19.3)
- Status : Released
- modid : asyu_mod_lib
- Description : Support Modding Library (Ex : Custom Registry Helper, GUI Helper, etc.)
- Project Visibility : Private
- Repository : Personal Gitlab
- need mod : nothing

## community-lib
- Current Version (MC Version) : 1.0.0 (1.19.3)
- Status : Released
- modid : community_lib
- Description : Custom Nickname (Support Vanilla EntitySelector's player name, Server Tab Overlay), Custom Chat (Cancel Vanilla Chat Packet, New Custom Chat Packet)
- Project Visibility : Private
- Repository : Personal Gitlab
- need mod
  - asyu_mod_lib >= 1.0.1
  - color_component >= 1.0.2
 
## economy-api
- Current Version (MC Version) : 1.0.0 (1.19.3)
- Status : Developing...
- modid : economy_api
- Description : Support Money & /check <amount> (/수표 <amount>) command
- Project Visibility : Private
- Repository : Personal Gitlab
- need mod : nothing

## shop-api
- Current Version (MC Version) : 1.0.0 (1.19.3)
- Status : Developing...
- modid : shop_api
- Description : Support Shop GUI & API (for NPC mod)
- Project Visibility : Private
- Repository : Personal Gitlab
- need mod
  - color_component >= 1.0.2
