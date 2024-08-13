# mint-themes-vanessa
The "Mint-Y" themes from Linux Mint 21 "Vanessa" unaltered.

![image](https://github.com/user-attachments/assets/e21b4ba8-df28-45d5-a3a4-3f84e59a0659)


Please not that GTK4 applications may not use the theme.

# Download

Click the green "Download" button then "Download ZIP".

or...
```
git clone https://github.com/contrarybaton60/mint-themes/vanessa
```

## If you're using a light theme (Mint-Y, Mint-Y-Blue, etc) add these lines for corner bar and separator applets to appear properly:

### Corner Bar:
```
   .applet-cornerbar {
  width: 8px;
  background-color: #c2c2c2; }
  .applet-cornerbar-box {
    padding: 4px 4px; }
    .applet-cornerbar-box:hover > .applet-cornerbar {
      background-color: #a8a8a8; }
  .applet-cornerbar.vertical {
    height: 8px; }
```



Put the above code in `ThemeFolder/cinnamon/cinnamon.css` at line 1703 so the "Corner Bar" applet would appear properly.

### Separator:
```
.applet-separator-line {
  width: 1px;
  background: #c2c2c2; }
  .applet-separator-line-vertical {
    height: 1px;
    background: #c2c2c2; }
```
 Replace the existing code with this in line 1590 in `ThemeFoler/Cinnamon/cinnamon.css` for "Separator" applet to appear properly.
