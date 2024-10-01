# linux_reference
ssh -p 15551 endeavour5@endeavourtech.ddns.net

ssh -p <port_number> user@<server_name or ip-address>
//For Endeavour server
user id : endeavour<n>
password: <Idiot_this_is_a_secret>

# scp
Moving from server to local:
scp -3 scp://endeavour@endeavourtech.ddns.net:15551/~/linux-sept2024/sample3/sample.pdf Downloads/

If you are using default port 22:
scp endeavour@endeavourtech.ddns.net:~/linux-sept2024/sample3/sample.pdf ~/linux-sept2024/sample3/
