# test
Run Python app on Centos7 

For run ansible playbook we need:
1. Start VM
2. Login to VM via ssh 
3. Install packages ansible and git:
   ```yum install ansible git -y```
4. Clone repo from github:
   ```git clone https://github.com/777dimas/test.git```
5. Go to folder test:
   ```cd test```
6. Run playbook:
   ```ansible-playbook -v ansible-playbook.yaml```
   
