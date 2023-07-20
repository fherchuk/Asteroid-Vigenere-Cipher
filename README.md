# Asteroid: Vigenere Cipher Tool   ![image](https://asteroid-lang.readthedocs.io/en/latest/_images/asteroid-small.png) 
### Midterm: Spring 2023 Project  

This is a simple cipher tool that is able to encrypt or decrypt a [vignere cipher](https://en.wikipedia.org/wiki/Vigenère_cipher) from user input. Inputs can either be single lines of text via command prompt, or entire .txt files in the /textfiles directory.

- Asteroid is a current developing language, documentation can be found [Here](https://asteroid-lang.readthedocs.io/en/latest/).


### How to Run:
Python
---
Documentation and instructions on installing and running Asteroid via a Python interpreter can be found [Here](https://pypi.org/project/asteroid-lang/).

Replit
---
Additionally a virtual machine with asteroid installed is available [Here](https://replit.com/@RickHerchuk/csc493-asteroid-midterm-project) via Replit.


<details>
    <summary>Instructions:</summary>
  
    Click Run.
    Enter the following into the console:
      'source start'
      'cd midterm-project'
      'asteroid main.ast'
    
</details>

Program Commands
---
Input and  output are displayed via the console for encrypting or decrypting text. Additionally there is functionallity for .txt file to be imported and exported. 
### Importing .txt
- Simply place the .txt file in the /textfiles directory and enter the full file name when prompted.
  ###
  ```
  ex. "encrypt.txt"
  ```
  ###

### Output
- Once encryption/decryption is complete, an option to export the results to a .txt will appear. doing so exports to the "output.txt" in the /textfiles directory.
