# Lab 3

## Streamlining ssh Configuration
![Image](fixingConfig.png)

Above is a demonstration creating a file named `config` and inputting credentials to create a faster experince when logging in
![Image](loginingintossh.png)

Now that the `config` file was created you can now type `ssh ieng6` and it will automatically log you in.
![Image](scping.png)

Depicted above is now using the "ieng6" nickname in action where we scp a random file in our directory to the ieng6 server.
## Setting up Github Access from ieng6
![Image](publickey.png)

Above is the public key that I created and stored in github.
![Image](privatekey.png)

Here is where to find the private key I had created in ieng6.
## Copying whole directories with scp -r

![Image](showingLine.png)

When running `scp -r.ieng6:markdown-parseLR` it will copy all the cotents of the respoirtory you curretntly in and store it in a folder named what you desire, so in this case it is name dmarkdown-parseLR.
![Image](lsSSH.png)

Depicted above is showing how the respority is now copied into ieng6