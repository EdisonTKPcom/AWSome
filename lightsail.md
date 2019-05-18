1. Go to the "SSH Keys" tab under your Lightsail Account page
2. Select the Default option under your region and download the key pair file
3. Will be a .pem file, ex. LightsailDefaultPrivateKey-us-west-2.pem
4. Open up your terminal and navigate to the directory where the above file is stored
5. Run chmod 600 [fileName] at the command line to restrict file permission so only you can read it
6. Run ssh -i [fileName] [username]@[Public IP] to establish the connection to Lightsail
7. Username and IP are available under the "Connect" tab on the Lightsail web dashboard for your resource
