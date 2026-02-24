Numbers are element numbers used in original array. The following is order listed in program.

Theme layout "simple = no" is -
  * headings = mdWidgetDone array []
  * bg_rightpanel = 0
  * console_bg = 1
  * console_fg = 2
  * button_fg = 7
  * button_bg = 4
  * button_icon = 5
  * button_border = 6
  * opacity = usu 0.9
  * prompt_fg = 1
  * prompt_bg =3
  * listbox_fg = 7
  * listbox_bg = 3
  * label_fg = 7 button_fg
  * label_bg = 0 (not used yet)

Theme layout "simple = yes" is 5 colors is - 
  * Headings are headings.
  * Colors are (numbering 0th as 1):
  * 1 - overall background
  * 2 - Fonts + Console background (inverse each other)
  * 3 - Console font, background for prompt box and listbox
  * 4 - Button color (right)
  * 5 - Buttons below terminal

Opacity must be defined for both.

inverse or matrix are color alignment with prompt_bg and the buttons. They were used heavily in a previous build and may be removed soon. inverse is default.
