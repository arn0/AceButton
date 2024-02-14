idf_component_register(SRCS
                        "src/ace_button/AceButton.cpp"
                        "src/ace_button/ButtonConfig.cpp"
                        "src/ace_button/EncodedButtonConfig.cpp"
                        "src/ace_button/LadderButtonConfig.cpp"
                    INCLUDE_DIRS 
                        ""
                        "src"
                        "src/ace_button"
                    REQUIRES arduino-esp32
                    )
