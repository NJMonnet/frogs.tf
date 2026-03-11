# Lien utiles

###### [Mastercomfig](https://comfig.app/)
- Configurations TF2 optimisées.
- Hud communautaire.
- Hit/Killsounds.

###### [Cfg.tf](https://cfg.tf/)
- Configurations TF2 optimisées.

###### [Callouts.tf](https://callouts.tf)
- Call des maps compétitives.

###### [ETF2L](https://etf2l.org/)
- Ligue compétitive européenne.

###### [RGL](https://rgl.gg/)
- Ligue compétitive nord-américaine.

###### [OZFORTRESS](https://ozfortress.com/pages/home)
- Ligue compétitive asiatique / océanique.

# Binds
###### Banny bind (Respawn instant)
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
