# AWS Portal

It is a script through which a user will be able to login into its various aws instances. He would be able to see a list of instances in various regions and select where he wants to login by defining the private key path
Following is the process :

  - The initial thing the file does is to create a config file named aws_login at the user's home folder.
    - It asks for your aws access_key, secret_key, .pem file path and the regions of the instances you want to list.
    - It then calls for the list of instances (instance-tag-name, instance-id and ip_address) and inserts in the config file.
  - There are two flags that can be entered when calling the script.
    -  -c [CACHE], --cache [CACHE]   Pass "no" for calling new instances data. By default, it is yes.
    -  -k [KEY], --key [KEY]         Provide the ssh-key-path.
  - After the list of instances is shown on the terminal, you can just enter the corresponding index of the instance to login or press 0 to exit.


### Script Made by :
* [Gaurav Verma]
* [Shubham Bhartiya]

[Gaurav Verma]:https://www.linkedin.com/profile/view?id=20880813
[Shubham Bhartiya]:https://www.linkedin.com/profile/view?id=254924970
