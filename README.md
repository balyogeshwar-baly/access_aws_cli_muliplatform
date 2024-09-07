# access_aws_cli_muliplatform

Accessing AWS CLI using Windows, Linux and macOS.

The steps are almost same for all the OS.

  Firstly, it begins with the installation of config files on the OS( https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html ). 
  After that test the installation of installer by entering aws --version. Make sure to run in su or admin mode.
  Create a user with specific permissions and generate Access Keys from Security credentials tab. Be sure to keep the Access Key and Secret Access key.
  Execute aws configure from cli of the OS where AWS CLI has been installed. 
  Enter the Access Key and Secret Access key specifically.
  Specify Region or Output format if needed.
  
You are good to go from here.
