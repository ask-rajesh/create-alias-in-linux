# create-alias-in-linux
End to end process to create a persistent alias.



#### Command to set alias

```
alias name='command'
```
Above command should be executed in terminal to set alias. But, above command will set alias only for current session. Once terminal is closed, the alias will get destroyed.

#### Steps to set alias which always persists

   * open ```~/.bashrc```, file and add your alias in this file and save it.
   * run ```source ~./bashrc``` in terminal.

Great, now you can access those alias anytime, anywhere.
