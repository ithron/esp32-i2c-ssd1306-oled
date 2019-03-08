set(COMPONENT_SRCS
  main/font_glcd_5x7.c
  main/font_tahoma_8pt.c
  main/fonts.c
  main/i2c.cpp
  main/ssd1306.cpp
)
set(COMPONENT_ADD_INCLUDEDIRS "main/include")

register_component()

