# ruthhprovider "aws" {
 region = "eu-north-1"  # Replace with your desired region
 access_key ="AKIA6GHCJ3KZBBPSXROJ"
 secret_key ="arkl+w1AtU+D5ber5MqSO8Zt+2Edj26Yfp16ari0"
}


resource "aws_instance" "ec2" {
 ami           = "ami-0989fb15ce71ba39e"
 instance_type = "t3.micro"
}
