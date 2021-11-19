# Getting Started
Greater implementation abilities for MITRE ATT&CK Navigator with automated ingestion and display of layers from Medium Article [Automate the Creation of ATT&CK Navigator Group Layer Files with Python](https://medium.com/threat-hunters-forge/automate-the-creation-of-att-ck-navigator-group-layer-files-with-python-3b16a11a47cf), further work TBD.


Ability to reference repository layers demo here: [Custom ATT&CK Navigator URL](https://mitre-attack.github.io/attack-navigator/#layerURL=https%3A%2F%2Fraw.githubusercontent.com%2FChateau-Lav%2Fmitre%2Fmain%2Ftest_layer_1.json&layerURL=https%3A%2F%2Fraw.githubusercontent.com%2FChateau-Lav%2Fmitre%2Fmain%2Ftest_layer_2.json&leave_site_dialog=false&tabs=false&selecting_techniques=false&header=false&subtechniques=false&search=false&multiselect=false&deselect_all=false&layer_info=false&download_layer=false&export_excel=false&filters=false&sorting=false&color_setup=false&toggle_hide_disabled=false&layout_controls=false&legend=false&disable_techniques=false&manual_color=false&scoring=false&comments=false&comment_underline=false&clear_annotations=false)

## Custom URL Breakdown

### Main URL
```
https://mitre-attack.github.io/attack-navigator/
```

### Parameters
All parameters are **required** to be seperated by and ampersand: `&`

#### Layer URLs
These values are **required** to be URL Encoded  

```
layerURL=https://raw.githubusercontent.com/Chateau-Lav/mitre/main/test_layer_1.json
layerURL=https://raw.githubusercontent.com/Chateau-Lav/mitre/main/test_layer_2.json
```

#### Navigator Settings
These define what option will be native available within the web browser by default  

```
leave_site_dialog=false
tabs=false
selecting_techniques=false
header=false
subtechniques=false
search=false
multiselect=false
deselect_all=false
layer_info=false
download_layer=false
export_render=false
export_excel=false
filters=false
sorting=false
color_setup=false
toggle_hide_disabled=false
layout_controls=false
legend=false
disable_techniques=false
manual_color=false
scoring=false
comments=false
comment_underline=false
clear_annotations=false
```