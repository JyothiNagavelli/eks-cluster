# eks-cluster
# install aws-iam-authenticator

curl -o aws-iam-authenticator https://s3.us-west-2.amazonaws.com/amazon-eks/1.21.2/2021-07-05/bin/linux/amd64/aws-iam-authenticator

# change permission

chmod +x ./aws-iam-authenticator

#mv aws authenticator
 sudo mv aws-authenticator /usr/local/bin
 
 $ aws-authenticator version
 
