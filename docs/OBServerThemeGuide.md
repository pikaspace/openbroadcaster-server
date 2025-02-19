Theme Guide

OpenBroadcaster has theme support, to allow a custom colour scheme throught menus including a branded transparent logo in background. To switch themes. Select Theme from User Account. To add custom Theme, copy and modify from Themes directory in server. Save. Refresh browser to load\view new theme.

Directory Structure

/themes : Main theme directory. Contains themes. /themes/THEME_NAME : Contains the theme 'THEME_NAME'.

Directories under THEME_NAME:

THEME_NAME/css_core : Overrides core CSS files. See files in /css. Create a file in THEME_NAME/css_core with the same filename, and it will be used instead.

THEME_NAME/css_theme : Any css files here will be included after the core CSS files.

THEME_NAME/html : HTML overrides. See files in /html. Create a file in THEME_NAME/html with the same filename, and it will be used instead.

THEME_NAME/images : Any images (to be used used with HTML/CSS). Use absolute path name when referring to images (in CSS or HTML).

---

  /* Background layers */
  --color-bg-main: #...;
  --color-bg-mid: #...;
  --color-bg-field: #...;

  /* Semantic background colors */
  --color-bg-notice-default: #...;
  --color-bg-notice-success: #...;
  --color-bg-notice-warning: #...;
  --color-bg-notice-danger: #...;
  --color-bg-button-default
  --color-bg-button-add
  --color-bg-button-edit
  --color-bg-button-delete

  /* Text colors */
  --color-text-field: 
  --color-text-placeholder:
  --color-text: #...;
  --color-text-inverse: #...;
  --color-text-link: #...;


Table Version 2 (Reference)

| Description | Light LC | Light HC | Dark LC | Dark HC |
| -------- | ----------- | ------- | --- | --- |
| --color-bg-main | #333336 |  #17171b  | #eeeeec  | #ededf1  |
| --color-bg-mid | #242426  | #101013   | #a6a6a5 | #a5a5a8  |
| --color-bg-field | #ffffff  |  #ffffff | #ffffff | #ffffff |
|  |  |  |  |  |
| --color-bg-notice-default | #eeeeec | - | #2e3436 | - |
| --color-bg-notice-success | #9de259 | #a8ff4b | #a3c77f | #1e5a1e |
| --color-bg-notice-warning | #fcef88 | #ffff8b | #e3dba0 | #DDC714 |
| --color-bg-notice-danger | #bf2121 |  #ffffff | - | #ffffff |
| --color-bg-button-default | #eeeeec | #ffffff | #2e3436 | #ffffff |
| --color-bg-button-add | #9de259 | #a8ff4b |  #a3c77f | #1e5a1e  |
| --color-bg-button-edit | #fcef88 | #ffff8b |  #e3dba0 | #DDC714 |
| --color-bg-button-delete | #bf2121  | #ffffff | - | #ffffff |
|  |  |  |  |  |
| --color-text-field | #2e3436 | #17171b | #333336 | #272727  |
| --color-text-placeholder | #757575  | #2e3436 | - | #2e3436 |
| --color-text | #eeeeec | #ffffff  | #333336 | #000000  |
| --color-text-inverse | #333336|  #000000 | #eeeeec | #ffffff |
| --color-text-link | #729fcf | #6dabdc | #204a87 | #11308c |
|  |  |  |  |  |


background colors:
background (furthest back, main background)
midground (sidebar / preview player)
field background

background colors with meanings (notice / buttons)
notice / default
success / save
warning / edit
danger / delete

text colors:
placeholder text
text
inverted text
link


--------

Table Version 1 (Old)

| Description | Light Low | Light High | Dark Low | Dark High |
| -------- | ----------- | ------- | --- | --- |
| primary background | #2e3436 | #17171b  | #eeeeec | #ffffff |
| secondary background | #000000 | #454843 | #2e3436 | #272727|
| tertiary background* || #2e3436 | #d3d7cf  | #2e3436 |
| tertiary background 2 | #919191 | - | #ededf1  | #ededf1 |
| tertiary background 3 || - | #8d9090 | #454843 |
| text | #eeeeec | #ffffff | #333336 | #000000 |
| inverted text | #333336 | #000000 | #eeeeec | #ffffff |
| link | #729fcf | #6dabdc | #204a87 | #11308c |
| success | #9de259 | #a8ff4b | #a3c77f | #1e5a1e |
| warning | #fcef88 | #ffff8b | #e3dba0 | #DDC714 |
| danger | #bf2121 | #ffffff | - | #ffffff |
| table border | #777777 | #aaaaaa | - | - |
| highlight | #e09529 | #e09529| - | #c1360f  |
| alternative color 1** | #666666 | #454843| #d3d7cf | #babcb8 |
| alternative color 2** | #557777 | #457474| #99bfbf | #8cbaba |
| alternative color 3** | #999966 | #747441| #e3dba0 | #bdbe8c |
| alternative color 4** | #669966 | #5d5da2| #9b9bc4 | #A3A2E5 |
| alternative color 5** | #996666 | #a25d5d| #ca9999 | #E09998 |
| alternative color 6** | #669966 | #2A512A| #a3c77f | #afd5b0 |


*placeholder or sidebar
**_addedit_item[
    1 = "dynamic-custom";
    2 = "station_id";
    3 = "breakpoint";
    4 = "audio";
    5 = "image";
    6 = "video";
]

---

"Colors"

- field background color
- field color
- text color
- footer text color
- body background color
- scrollbar color
- link color
- footer top border 
- table th border color
- table td border color
- button text color
- button background color
- button border color
- button add background color 
- button add text color 
- button edit background color 
- button edit text color 
- button delete background color 
- button delete text color 
- message text color
- message background color
- message success background color - color-success
- message success text color - color-
- message warning background color
- message warning text color
- message error text color
- placeholder color input
- droppable highlight color
- ob-media background color
- ob-media text color
- ob-media input empty border color
- obmenu list item border color
- obmenu list item background color
- ob tag input border color
- input select textarea border color
- sidebar player main background color
- sidebar player main border color
- sidebar player draghere text color
- sidebar search media container search background color
- sidebar search media container search border color
- sidebar search media container basic background color
- sidebar search media container basic border color
- sidebar search media container detailed background color
- sidebar search media container detailed border color
- sidebar search tab playlist background color
- sidebar search tab background color
- sidebar search tab border color
- sidebar search tab selected background color
- sidebar search tab selected border color
- sidebar search tab link text color
- sidebar search tab no results text color
- sidebar search media headings table color
- sidebar search media selected background color
- sidebar search media selected text color
- context menu background color
- context menu border color
- media upload form border color
- media upload form background color
- playlist edit advanced background color
- playlist items background color
- playlist items border color
- playlist added it dynamic custom background color
- playlist added it station_id background color
- playlist added it breakpoint background color
- playlist added it audio background color
- playlist added it image background color
- playlist added it video background color
- schedule container border color
- schedule container background color
- schedule details div background color
- schedule details div border color
- schedule data div border color
- schedule data div text color
- emergency list container background color
- layout modal window text color
- layout modal window background color
- layout modal window border color
- alert confirm background color
- alert confirm border color
- drag helper background color
- drag helper text color


----

Properties

- body font size
- body font family
- link hover text decoration
- message max-width
- message margins
- message padding
- message border radius
- button padding
- button font size
- button border
- button border radius
- button font-weight
- button margin-left
- link button text decoration
- link button cursor
- button first child margin left
- placeholder input text align
- placeholder input opacity
- placeholder font weight
- fieldset border size
- fieldset border-top
- fieldset margin-top
- legend font-size
- legend font-weight
- legend padding
- fieldrow font-size
- fieldrow margin
- fieldrow verticle-align
- fieldrow > span display
- fieldrow > div verticle-align
- fieldrow > div display
- fieldrow > div > div + div margin
- fieldrow > label position
- fieldrow > label top
- fieldrow > verticle-align
- fieldrow > label display
- fieldrow > label width
- fieldrow > label text-align
- fieldrow > label padding-right
- fieldrow > label font-weight
- fieldrow > label.required font-weight
- fieldrow > label:after content
- fieldrow > label.empty:after content
- input[] select textarea display
- input[] select textarea text color
- input[] select textarea font-size
- input[] select textarea border-radius
- input[] select textarea border
- input[] select textarea padding
- input[] select textarea width
- input[] select textarea vertical-align
- input[] select textarea box-shadow
- media fieldrow > label padding-right
- media fieldrow > label + * position
- media fieldrow > label + * top
- textarea ob-group verticle-align
- textarea::placeholder text-align
- input[] checkbox radio vertical-align
- input[] checkbox radio position
- input[] checkbox radio top
- input[] range color vertical-align
- hidden display
- table width
- table max-width
- table th font-weight
- table th padding
- table th border-bottom
- table th white-space
- table th text-align
- table td padding
- table td border-bottom
- table tr:last-child td border bottom
- table tr:first-child padding-left
- table tr:last-child padding-right
- droppable media playlist border
- droppable highlighted border
- datapicker-div font-size
- datapicker-calendar table-layout
- ob tab-select display
- ob tab-select button border
- ob tab-select button-active border
- ob-group display
- ob-group select display
- ob-group select width
- ob-group select max-width
- ob-group padding
- ob-group border-radius
- ob-group margin
- ob-group positon
- ob-group font-size
- ob-group box-sizing
- ob-group margin
- ob-group span cursor
- ob-group span padding-left
- ob-group span padding-right
- ob-group span font-weight
- ob-group span font-size
- ob-group span position
- ob-group span right
- ob-group span: after content
- ob-group empty border
- ob-group empty::after content
- ob-group empty::after display
- ob-group empty::after text-align
- ob-group empty::after line-height
- ob-group data-single empty::after content
- ob-media empty::after content
- ob-media empty::after display
- ob-media empty::after text-align
- ob-media empty::after line-height
- ob-playlist ob-media empty::after content
- ob-tag-suggestions width
- ob-tag-suggestions padding
- ob-tag-suggestions border
- ob-tag-suggestions border-radius
- ob-tag-suggestions display
- ob-tag-suggestions margin-top
- ob-tag-suggestions height
- ob-tag-suggestions cursor
- ob-tag-input not focus margin-bottom
- ob-tag-input focus suggestions display
- ob-tag-input focus suggestions position
- ob-tag-input focus suggestions top
- ob-tag-input focus suggestions left
- ob-tag-input focus suggestions height
- ob-tag-input display
- ob-tag-input width
- ob-tag-input min-height
- ob-tag-input border
- ob-tag-input padding
- ob-tag-input border-radius
- ob-tag-input position
- ob-tag-input ob-tag display
- ob-tag-input ob-tag padding
- ob-tag-input ob-tag border-radius
- ob-tag-input ob-tag margin
- ob-tag-input ob-tag span cursor
- ob-tag-input ob-tag span padding-left
- ob-tag-input ob-tag span padding-right
- ob-tag-input ob-tag span font-weight
- ob-tag-input ob-tag span font-size
- ob-tag-input ob-tag span::after content
- ob-tag-input media playlist box-sizing
- ob-tag-input media playlist width
- ob-tag-input media playlist min-height
- ob-input readonly span display
- ob-input readonly select display
- drag helper z-index
- drag helper left
- drag helper top
- drag helper position
- drag helper cursor
- drag helper padding
- drag helper font-weight
- drag helper width
- drag helper text-align
- drag helper boder radius
- drag helper font-size
- drag helper pointer-event


---

"Light On Dark (High Contrast)"
| variable | description | default |
| -------- | ----------- | ------- |
| --color-light| field background | #ffffff |
| --color-dark| field foreground | #17171b |
| --color-light-gray| foreground | #aaaaaa |
| --color-dark-gray| background | #454843 |
| --color-green-gray| unique color, background | #457474 |
| --color-yellow-gray| unique color, background | #747441 |
| --color-blue-gray| unique color, background | #5d5da2 |
| --color-red-gray| unique color, background | #a25d5d |
| --color-dark-green-gray| unique color, background | #2A512A |
| --scrollbar-color | body, main_container, footer | #ffffff rgba(0,0,0,0) |
| --link-color | links | #6dabdc |
| --button-add | unique color, button.add | #a8ff4b |
| --button-edit | unique color, button.edit | #ffff8b |
| --color-placeholder | for -placeholder | #2e3436 |
| --color-highlight | unique color droppable_target_highlighted | #e09529 |
| --color-sidebar | unique color sidebar_player_draghere | #cccccc |
| --color-transparent | background | transparent |
| - | - | - |
| --border-bottom | border-bottom | --color-light-gray |
| --field-color | field | --color-dark |
| --footer | footer colour | --color-light |
| --border-color | fieldset, layout_footer, border-top-color, border, ob-tab-select button | --color-light |
| --border-button-active | ob-tab-select button | --color-light |
| --background-color | background | --color-light |
| --color | foregorund | --color-dark |
| --button-delete | button.delete | --color-light |


------

"Dark on Light (Lower Contrast)"
| variable | description | default |
| -------- | ----------- | ------- |
| --color-light| field background | #eeeeec |
| --color-dark| field foreground | #2e3436 |
| --color-dark-gray| background | #333336 |
| --color-dark-gray-variant| unique color, sidebar_search_tabs a | #333333 |
| --scrollbar-color | body, main_container, footer | #8d9090 rgba(0,0,0,0) |
| --color-link| unique color, link | #204a87 |
| --color-green| button.add, video_add | #a3c77f |
| --color-yellow| button.edit, breakpoint_add | #e3dba0 |
| --color-light-green-gray| background | #d3d7cf |
| --color-light-yellow-gray| unique color, sidebar_search_tab | #a6a6a5 |
| --color-green-gray| unique color, station_id | #99bfbf |
| --color-blue-gray| unique color, data-type=audio| #9b9bc4 |
| --color-orange-gray| unique color, data-type=image| #ca9999 |
| --color-light-variant| unique color, schedule_details > div | #ededf1 |
| --color-background-shadow | unique color, drag_helper | rgba(0,0,0,0.8) |
| - | - | - |
| --border-color | border | --color-dark-gray |
| --button-color | ob-tab-select button | --color-dark-gray |
| --button-background | button background | --color-dark |
| --button-text | button text | --color-light |
| --button-text-action | button text | --color-dark |


------

"Dark on Light (High Contrast)"
| variable | description | default |
| -------- | ----------- | ------- |
| --color-dark| field foreground | #272727 |
| --color-white | field background | #ffffff |
| --color-light| background | #ededf1 |
| --color-black| text | #000000 |
| --scrollbar-color | body, main_container, footer | #272727 rgba(0,0,0,0) |
| --color-link| unique color, link | #11308c |
| --color-dark-gray| unique color, table td | #555555 |
| --color-green| button.add, message.success | #1e5a1e |
| --color-yellow| button.edit, message.warning | #DDC714 |
| --color-dark-gray| placeholders | #2e3436 |
| --color-red| unique color, droppable_target_highlighted | #c1360f |
| --color-border-bottom| unique color | #333333 |
| --color-green-gray| data-type=dynamic, custom| #babcb8 |
| --color-blue-gray| unique color, data-type=station_id | #8cbaba |
| --color-yellow-gray| unique color, data-type=breakpoint | #bdbe8c |
| --color-purple-gray| data-type=audio | #A3A2E5 |
| --color-red-gray| data-type=image | #E09998 |
| --color-green-gray-variant| data-type=image | #afd5b0 |
| --color-dark-green-gray| unique color, schedule_data > div | #454843 |
| --color-transparent | background | transparent |
| - | - | - |
| --border-color | border | --color-black |