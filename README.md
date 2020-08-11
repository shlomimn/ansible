# ansible

echo '1234567890' > /tmp/a.txt

run command:
ansible-playbook -i IPs.yml copy-a2b.yml -vv
