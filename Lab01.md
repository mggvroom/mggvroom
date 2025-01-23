## Lab 01

- Name: Thomas Kammoe
- Email: kammoe.2@wright.edu

## Part 1 - GitHub Profile

1. [mggvroom](FIXTHISURL-https://github.com/mggvroom)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | use to get information about powershell help system.       |
| Get-Location | pwd    | use to get your current directory location.       |
| Get-ChildItem | ls    | use to display the items in the directory.       |
| mkdir   | mkdir       | use to create a directory.      |
| Set-Location | cd     | change current directory.       |
| New-Item | touch      | use to create a file or directory.     |
| Move-Item | mv        | use to move a file or directory to a different location.    |
| Copy-Item | cp        | use to copy a file or directory to a different location.       |
| Remove-Item | rm      | use to remove a file or directory.      |
| notepad.exe | vim     | used to open notepad.       |

## Part 3 - Command Line Navigation

My OS is: Windows
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: PS C:\Users\kammo>

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir DirA
2. Create a directory named `Dir B`: mkdir "Dir B"
3. Go into `DirA`:  cd DirA
4. Go into `Dir B` from `DirA`:  cd "Dir B"
5. Return to your user's home directory: cd ..
6. Create a file named `test.txt`: new-item test.txt
7. Move the file named `test.txt` into `DirA`: move-item test.txt DirA
8. Contents of `test.txt`: notepad test.txt
```
Put your words here: My goal by the end of this semester is to understand and know how to use a lot of the commands.By being disciplined and hardworking.
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: cd DirA, copy-item "test.txt" -destination "copy.txt"
10. View the contents of `DirA`: cd DirA, ls
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: copy-item ".\DirA\test.txt -destination ".\Dir B\fodder.txt
12. Delete / remove both `fodder.txt` AND `Dir B`: remove-item fodder.txt, remove-item "Dir B"

## Citations


I used Microsoft Copilot to help me with the syntax. The  website below helped me with difining the commands and how it works.

                                Works Cited
Gunnell, Marshall. “30 PowerShell Commands You Must Know (Cheat Sheet Included).” Techopedia, 23 Mar. 2024, www.techopedia.com/30-powershell-commands-you-must-know-cheat-sheet-included.


