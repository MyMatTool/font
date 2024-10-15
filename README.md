# MATLAB UI Font Change Function

This function is used to change the font on the MATLAB UI.

## How to run

Enter a number or string after the `font` command and execute.

#### Change font size
  Entering a number will change the font size.
  ```matlab
  >> font 10
  ```
#### Execute shortcut key
  If you have registered a shortcut key, you can change to the setting by executing with key as an argument.
  ```matlab
  >> font key
  ````

#### Display shortcut key list
  Executing without arguments will display a list of shortcut keys.
  ```matlab
  >> font
  --------------------------------------------------
  <<Shortcut list>>
      shortcutKey                        font                        size
      ___________    ____________________________________________    ____
  
      {'default'}    {'Monospaced'                              }     13 
      {'a'      }    {'Academy Engraved LET'                    }      0 
      {'e'      }    {'Menlo'                                   }      0 
      {'m'      }    {'Monospaced'                              }      0 
      {'pm'     }    {'PT Mono'                                 }      0 
      {'am'     }    {'Andale Mono'                             }      0 
      {'ay'     }    {'Ayuthaya'                                }      0 
      {'user'   }    {'__REPLACE WITH YOUR FAVORITE FONT NAME__'}     12 
  
  --------------------------------------------------
  input key :
  ```

## Register shortcut keys
Shortcut keys can be registered in `shortcut.csv`. Do not use spaces in the key. You can assign a font name and font size to one key. If you want to set only the font name, register the value of the size column as `0`.


## Demo
<img src="https://github.com/user-attachments/assets/849f1fda-edf4-4d11-8fd6-3819497be8bc" width="70%">
