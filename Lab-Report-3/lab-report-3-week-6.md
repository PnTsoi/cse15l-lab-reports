# Lab Report 3 Week 6 🚨🚨🚨🚨

## Streamlining ssh Configuration
Since Windows doesn't have a reliable text editor in the command terminal that doesn't create a .txt file, what I did was that I run

``` notepad config.txt ```

and then copy the code into the config.txt:

```
Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lsp22all
    IdentityFile ~/.ssh/id_rsa
```
Since this is not exactly the config file, I will have to copy the content in config.txt to a new file called config.
```
copy config.txt config
```
then I have to delete config.txt
```
del config.txt
```
Now, I will have a config file that has the content of config.txt:

![config](./../Pictures/Lab%203/notepadconfig.jpg)

And I can log in ieng6 like this:

![sshieng6](./../Pictures/Lab%203/sshieng6.jpg)

I can also copy a simple file  from client to server using scp:
![scptoieng6](./../Pictures/Lab%203/scptoieng6.jpg)

## 