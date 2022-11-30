# My TF module 
This is an example of a TF module

## Usage 
~~~
module "my_ec2_instance" {
 source = "github.com/bruceherve/tf-module-example.git"

 ec2_instance_type = "t3.micro"
 ec2_instance_name = "My instance"
 number_of_instances = 1
 ec2_ami_id = <Your AMI ID to launch the instance>
}

~~~
