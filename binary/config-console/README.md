# PicoCTF_2017: Config Console

**Category:** Binary Exploitation
**Points:** 125
**Description:**

>In order to configure the login messsage for all the users on the system, you've been given access to a configuration console. See if you can get a shell on shell2017.picoctf.com:27124. console Source

**Hint:**

>You can either see where libc is or modify the execution. Is there a way to get the vulnerability to run twice so that you can do both?
There's a place in libc that will give you a shell as soon as you jump to it. Try looking for execve.

## Write-up
