# Lien utiles

###### [Mastercomfig](https://comfig.app/)
- Configuration de jeu optimisé.
- Hud communautaire
- Hit/Killsounds

###### [Cfg.tf](https://cfg.tf/)
- Configuration de jeu optimisé.

###### [Callouts.tf](https://callouts.tf)
- Call des maps compétitive.

# Binds
##### Banny bind (Respawn instant)
```
bind KEY "load_itempreset 0"
```

###### Improved Crouch Jump
```
// Improved Crouch Jump
alias +rj "-duck;+cr;alias checkrj +cr;spec_mode";
alias -rj "-cr;checkduck;alias checkrj";
alias +crouch "-cr;+duck;alias checkduck +duck";
alias -crouch "-duck;checkrj;alias checkduck";
alias checkduck;
alias checkrj;
alias +cr "+jump;+duck";
alias -cr "-duck;-jump";
bind space +rj;
bind ctrl +crouch;
```
